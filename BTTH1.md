**Bài 1: Quản lý lưu trữ và đường dẫn tệp trong Windows** 

### **Phần 1 (Phân tích):**

Chỉ ra các sai lầm của Nam về vị trí lưu trữ, cách đặt tên file và hiểu lầm về tốc độ mạng. Giải thích tại sao ổ SSD 256 GB thực tế lại hiển thị dung lượng thấp hơn con số 256\.  
\-\>Trả lời:   
Lỗi 1: Do bạn Nam đang lưu trữ trong tệp Windows System32.  
    \+System 32 là thư mục chứa các tập tin thực thi của hệ điều hành. Khi mà lưu file code vào đây sẽ dễ bị xung đột hoặc vô tình xóa nhầm file hệ thống này.   
    \+Nam nên lưu vào ổ đĩa D để dễ dàng quản lí và hạn chế ảnh hưởng đến ổ đĩa C  
Lỗi 2: Do cách đặt tên có khoảng trắng và không tuân thủ cách đặt tên theo python.  
Lỗi 3: Do Nam hiểu lầm về 100Mbps với  tốc độ tải file hiển thị là MB/s 

Vì 1 Byte=8 Bits  
100 Mbps : 8 \= 12.5 MB/s   
Vậy tốc độ là 12.5 MB/s là đúng

**SSD 256 GB lại hiển thị thấp hơn do nhà sản xuất tính theo đơn vị thập phân còn hệ điều hành window hiển thị cách khác nên theo thực tế sẽ thấp hơn dung lượng ban đầu.**

**Phần 2 (Hoàn thiện):**

**Thiết kế lại cây thư mục học tập chuẩn trên ổ D: cho Nam (áp dụng quy tắc 3 cấp và 4 trụ cột). Đề xuất tên file/thư mục theo chuẩn kebab-case.**

**D:\\**  
**└── ptit\\**  
    **├── code\\**  
       **└── python\\**  
           **└── session-01\\**  
               **└── bai-tap-01.py**  
    

