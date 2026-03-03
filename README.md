#  CROWN-CO – Luxury E-Commerce Website

CROWN-CO là website thương mại điện tử mô phỏng cửa hàng bán đồ xa xỉ.  
Dự án được xây dựng hoàn toàn bằng **HTML, CSS và JavaScript thuần (Vanilla JS)**.

Website hoạt động phía client và sử dụng `localStorage` để lưu dữ liệu người dùng.

---

##  Tính Năng Chính

###  1. Single Page Application (SPA)
- Điều hướng bằng hash (#)
- Không reload trang
- Active menu tự động cập nhật
- Các trang:
  - Home
  - Products
  - About

---

### 2. Hệ thống Đăng ký / Đăng nhập
- Tạo tài khoản
- Đăng nhập
- Lưu phiên người dùng
- Dữ liệu được lưu riêng theo từng user bằng localStorage

---

### 3. Giỏ hàng
- Thêm sản phẩm vào giỏ
- Cập nhật số lượng
- Tính tổng tiền theo thời gian thực
- Thanh toán trực tiếp

---
### 4. Tính phí vận chuyển
- Chọn đơn vị giao hàng
- Hiển thị phí ship
- Hiển thị thời gian giao dự kiến (ETA)
- Tính tổng tiền cuối cùng

---

### 5. Quản lý đơn hàng
- Lưu lịch sử đơn hàng
- Theo dõi trạng thái
- Hiển thị tiến trình giao hàng
- SVG tracking minh họa

---

### 6. Tìm kiếm sản phẩm
- Tìm theo từ khóa
- Lưu lịch sử tìm kiếm
- Lưu riêng theo tài khoản

---

###  7. Chat Bot Luxury
- Chat tự động theo từ khóa:
  - Giá sản phẩm
  - Giao hàng
  - Khuyến mãi
  - Liên hệ
  - Chất lượng
- Lưu lịch sử chat theo từng tài khoản
- Hỗ trợ gửi emoji
- Hỗ trợ gửi ảnh (có nén ảnh để tránh vượt quá dung lượng lưu trữ)

---



##  Cơ chế Lưu Trữ

Dữ liệu được lưu bằng `localStorage`:

- vip_chat_messages
- vip_cart
- vip_orders
- vip_last_order
- vip_search_history

Nếu có user đăng nhập, key sẽ được gắn theo email.

---

##  Công Nghệ Sử Dụng

- HTML5
- CSS3
- JavaScript ES6
- LocalStorage API
- SVG

---

## ⚙ Cách Chạy Dự 




##  Lưu Ý

- Đây là dự án frontend mô phỏng.
- Không có backend thực.
- Dữ liệu sẽ mất nếu xóa localStorage trình duyệt.

---

##  Định Hướng Phát Triển

- Kết nối backend (NodeJS / Firebase)
- Thanh toán online
- Dashboard quản trị
- AI chatbot nâng cao
- Bảo mật tài khoản tốt hơn

---

##  Author

CROWN-CO Luxury Edition  
Premium Experience Design
