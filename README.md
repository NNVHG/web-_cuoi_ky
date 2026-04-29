# ⌨️ Bàn Phím Tối Cổ - Mechanical Keyboard Shop

[cite_start]Chào mừng đến với **Bàn phím tối cổ** - Một trang web thương mại điện tử chuyên cung cấp các sản phẩm bàn phím cơ, keycap và phụ kiện custom. Dự án này được xây dựng tập trung vào trải nghiệm người dùng (UX/UI) với giao diện hiện đại, trực quan và dễ sử dụng.

[cite_start]Trang web được thực hiện bởi các thành viên thuộc "Động tối cổ", lớp D22CNTT02.

## 🚀 Tính Năng Chính (Key Features)

* [cite_start]**Giao diện thân thiện:** Trình bày sản phẩm theo các danh mục rõ ràng như Hàng Bán Chạy, Hàng Mới, Keycap, Phụ kiện và phân loại theo các hãng lớn (Akko, Logitech, Razer, DareU, Asus, Corsair).
* [cite_start]**Trang chi tiết sản phẩm:** Mỗi sản phẩm đều có trang chi tiết riêng (`chitietsp_html`), hiển thị rõ thông số kỹ thuật, giá cả, và đánh giá chi tiết (Ví dụ: Asus ROG Claymore II, AKKO 3084B Plus).
* [cite_start]**Chức năng Đăng ký / Đăng nhập:** Tích hợp tính năng xác thực người dùng cơ bản mô phỏng trực tiếp trên trình duyệt bằng `LocalStorage`.
* [cite_start]**Hiệu ứng tương tác:** * Nút "Back to Top" (Về đầu trang) tiện lợi khi cuộn trang dài.
  * [cite_start]Hiệu ứng `Scroll Reveal` (hiển thị nội dung mượt mà khi cuộn trang) giúp trang web trở nên sống động hơn.

## 🛠️ Công Nghệ Sử Dụng (Tech Stack)

Dự án thuần Frontend, tập trung vào việc xây dựng cấu trúc và định dạng trực quan:
* [cite_start]**HTML5:** Xây dựng cấu trúc đa trang (Multi-page application).
* [cite_start]**CSS3:** Thiết kế giao diện phản hồi, hiệu ứng gradient, animation (như hiệu ứng đổi màu chữ ở footer) và tùy biến scrollbar.
* [cite_start]**JavaScript (Vanilla & jQuery):** Xử lý logic Đăng nhập/Đăng ký, bắt sự kiện cuộn trang và hoạt ảnh.
* [cite_start]**FontAwesome:** Thư viện icon vector.

## 📂 Cấu Trúc Thư Mục (Directory Structure)

```text
nnvhg-web-_cuoi_ky/
[cite_start]├── index.html          # Trang chủ [cite: 1]
[cite_start]├── shop.html           # Trang danh sách sản phẩm (Cửa hàng) [cite: 1]
[cite_start]├── gioithieu.html      # Trang kiến thức về bàn phím cơ [cite: 1]
[cite_start]├── vechungtoi.html     # Trang thông tin thành viên dự án [cite: 1]
[cite_start]├── dangnhap.html       # Trang đăng nhập [cite: 1]
[cite_start]├── dangky.html         # Trang đăng ký [cite: 1]
[cite_start]├── chitietsp_html/     # Thư mục chứa trang chi tiết cho từng sản phẩm [cite: 1]
[cite_start]├── css/                # Chứa toàn bộ file style (trangchu.css, shop.css, chitietsp.css,...) [cite: 1, 2]
[cite_start]├── img/                # Thư mục chứa hình ảnh sản phẩm, banner, logo các hãng [cite: 2, 3, 4]
[cite_start]└── js/                 # Chứa mã JavaScript [cite: 13]
