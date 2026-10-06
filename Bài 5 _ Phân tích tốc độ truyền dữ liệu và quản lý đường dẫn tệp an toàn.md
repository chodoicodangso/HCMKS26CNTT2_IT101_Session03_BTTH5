## **Phần 1: Phân tích & So sánh**

**1\. Bảng so sánh đường dẫn:**

| Tiêu chí | Đường dẫn tuyệt đối | Đường dẫn tương đối |
| :---- | :---- | :---- |
| **Định nghĩa** | Gốc từ ổ đĩa | Tính từ vị trí file code hiện tại. |
| **Tính linh hoạt** | **Kém.** Đổi máy sẽ bị lỗi | **Cao.** Mang sang máy khác vẫn chạy tốt. |
| **Ứng dụng** | Liên kết tài nguyên cố định bên ngoài | Làm dự án, làm việc nhóm, chia sẻ mã nguồn. |

**. Tính thời gian tải file (2GB với mạng 80 Mbps)**  
Dung lượng file \= 2 x 1024 x 1024 x 1024 x 8 \= 17.179.869.184 bits  
Tốc độ mạng \= 80.000.000 bps  
Thời gian tải \= 17.179.869.184 / 80.000.000 \= **214,75 giây**  
**Phần 2: Hành động**  
**1\. Viết lại đường dẫn tương đối (Relative Path):**  
Nếu file code nằm cùng thư mục file tài liệu: .\\tai-lieu-on-tap.pdf.exe  
Nếu file code nằm trong thư mục con của dự án: ..\\tai-lieu-on-tap.pdf.exe  
**2\. Các bước bật "View Options" chống mã độc ẩn đuôi trên Windows:**  
**Bước 1:** Nhấn Windows \+ E để mở **File Explorer**.  
**Bước 2:** Chọn mục **View** trên thanh công cụ phía trên.  
**Bước 3:** Tích chọn **File name extensions** (Trên Win 11 chọn **Show** $\rightarrow$ **File name extensions**).  
**Ý nghĩa:** File sẽ hiện rõ đuôi thật là .pdf.exe (mã độc) chứ không phải .pdf thông thường, giúp phòng tránh kích hoạt virus.

