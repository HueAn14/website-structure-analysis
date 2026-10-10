# [Bài tập] Phân tích và Xây dựng Cấu Trúc Website Template

## Phần 1: Báo Cáo Phân Tích Cấu Trúc Trang Web Thực Tế

- **Trang web lựa chọn phân tích:** [TechCrunch](https://techcrunch.com) - Tạp chí tin tức công nghệ và khởi nghiệp hàng đầu thế giới.
- **Ảnh chụp trang web gốc phân tích:**

![Ảnh chụp màn hình trang web gốc](images/screenshot-original.png)

### Chi tiết cách bố trí các thành phần:
1. **Header (Đầu trang):**
   - Đặt ở vị trí trên cùng trang web.
   - Chứa thương hiệu/Logo chính (`TechCrunch`), slogan khẩu hiệu mô tả định vị trang tin và nút kêu gọi hành động (Đăng ký nhận bản tin).
   - Tác dụng: Nhận diện thương hiệu ngay từ cái nhìn đầu tiên, tạo ấn tượng chuyên nghiệp.

2. **Navigation Menu (Thanh điều hướng):**
   - Đặt cố định dính ngay phía dưới Header (`position: sticky`).
   - Gồm các mục điều hướng phân loại nội dung chính: *Trang chủ*, *Công nghệ*, *Khởi nghiệp*, *Trí tuệ nhân tạo (AI)*, *Liên hệ*.
   - Tác dụng: Giúp người đọc dễ dàng di chuyển nhanh giữa các luồng chủ đề quan tâm.

3. **Content Section (Phần nội dung chính):**
   - Bố cục theo mô hình 2 cột (Main Layout: 70% nội dung chính - 30% thanh bên) sử dụng CSS Flexbox.
   - **Cột chính (Main Content):** Trình bày bài viết tiêu điểm gồm nhãn chủ đề (`badge`), tiêu đề lớn, metadata (tác giả, ngày đăng), ảnh minh họa nổi bật (`images/article.jpg`) và các đoạn văn bản phân tích chi tiết.
   - **Cột phụ (Sidebar):** Chứa widget danh sách các bài viết xu hướng đọc nhiều và tóm tắt phân tích.

4. **Footer (Chân trang):**
   - Đặt ở đáy website với nền màu tối tương phản.
   - Bao gồm thông tin bản quyền (`© 2026 TechCrunch Daily. All rights reserved.`) và danh sách các liên kết pháp lý (Giới thiệu, Điều khoản, Bảo mật, Hỗ trợ).

---

## Phần 2: Cấu Trúc Mã Nguồn Đã Xây Dựng Lại

```text
website-structure-analysis/
├── index.html       # Cấu trúc HTML semantic (header, nav, main, article, aside, footer)
├── style.css        # Định dạng bố cục Flexbox, màu sắc, font chữ và responsive
├── images/
│   ├── article.jpg              # Ảnh minh họa nội dung bài viết
│   └── screenshot-original.png  # Ảnh trang web gốc đã phân tích
└── README.md        # Báo cáo phân tích chi tiết
```
