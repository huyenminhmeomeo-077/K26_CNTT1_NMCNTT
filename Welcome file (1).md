# Phần 1. Phân tích sự cố tài liệu dự án
## 1. Chỉ ra sai lầm trong tư duy của Nam khi dùng file Rich Text lưu trữ mã nguồn

-   Sai lầm 1: Sử dụng định dạng nhị phân độc quyền cho quản lý phiên bản.
-   Sai lầm 2: Thiếu khả năng tương thích trực quan trên nền tảng web cộng tác.
## 2. Giải thích tại sao Markdown an toàn và nhẹ hơn

-    Markdown là văn bản thô , cực kỳ nhẹ 
-   Nếu tệp `.md` bị lỗi một vài byte truyền tải do mạng, chỉ một vài ký tự bị ảnh hưởng và có thể dễ dàng sửa 
-   Vì là văn bản thô , Git có thể dễ dàng theo dõi từng dòng, giúp ghép mã nguồn và hạn chế tối đa xung đột.
# Phần 2. Chuyển đổi đoạn giới thiệu từ World sang Markdown
```
# Dự Án GreenTech — Giải Pháp Công Nghệ Xanh
> **Sứ mệnh:** Xây dựng hệ thống quản lý và tối ưu hóa năng lượng thông minh dành cho khuôn viên Đại học (Smart Campus).
## 1. Giới Thiệu Chung
**GreenTech** là dự án nghiên cứu và phát triển hệ thống giám sát tiêu thụ điện năng của **Học viện Công nghệ Bưu chính Viễn thông (PTIT)**.
Hệ thống ứng dụng công nghệ **IoT** kết hợp với **Thuật toán Phân tích Dữ liệu** để:
* Giảm thiểu lãng phí điện năng.
* Cảnh báo sự cố cháy nổ điện tự động.
* Tiết kiệm chi phí vận hành cho nhà trường.
## 2. Các Tính Năng Chính
### 2.1. Cảm Biến & Thu Nhập Dữ Liệu
1. **Đo dòng điện, điện áp** 
2. **Theo dõi nhiệt độ môi trường** 
### 2.2. Điều Khiển Trực Tuyến
* Bật/Tắt thiết bị từ xa qua giao diện Web 
* Lịch tự động theo thời khoá biểu 
## 3. Danh Sách Thành Viên & Phân Công
| STT | Họ và Tên | Vai trò | Nhiệm vụ chính |
| :---: | :--- | :--- | :--- |


