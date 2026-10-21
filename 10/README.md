# 💌 Bức Thư Chúc Mừng 20/10 — Dành Tặng Người Đặc Biệt

Trang web đơn trang (Single Page Application) được thiết kế theo phong cách tối giản (minimalism), ngọt ngào, tinh tế với gam màu hồng pastel dịu êm (dreamy blush pink, sakura, hồng đất), kết hợp sắc chữ mận gỗ sang trọng, font chữ có chân quý phái (Cormorant Garamond, Playfair Display) và chuyển động mượt mà.

---

## 🌟 Tính Năng Nổi Bật

1. **Màn hình khóa phong bì cổ điển (Vintage Sealed Envelope):**
   - Họa tiết phong thư với con dấu sáp đỏ (wax seal) và dấu mộc bưu điện 20.10.
   - Ô nhập "Ngày tháng năm sinh" hỗ trợ nhập linh hoạt (ví dụ: `20/10/2000`, `20/10`, `20-10-2000`).
   - Hiệu ứng phản hồi rung nhẹ tinh tế cùng lời nhắc dịu dàng khi nhập sai (*"Hình như chưa đúng lắm, thử lại nhé..."*).
   - Khi nhập đúng: con dấu sáp bung nở, phong thư mở ra và chuyển cảnh mượt mà sang bức thư giấy vintage.

2. **Hiệu ứng gõ chữ (Typewriter Effect):**
   - Từng ký tự xuất hiện tuần tự với nhịp điệu tự nhiên (nghỉ nhẹ ở dấu phẩy, dấu chấm, xuống dòng) như thể có người đang nắn nót viết thư tay cho cô ấy.
   - Con trỏ nhấp nháy êm dịu, tự động ẩn đi và hiện chữ ký viết tay mềm mại khi hoàn thành.
   - Nút "Xem toàn bộ" nếu người đọc muốn xem ngay lập tức.
   - Nút "Đọc lại bức thư" để thưởng thức lại hiệu ứng gõ chữ.

3. **Chi tiết thị giác & Tương tác:**
   - Cánh hoa và bụi sáng pastel bay lơ lửng chuyển động chậm trên nền Canvas 60fps.
   - Họa tiết hoa lá một nét (botanical line art) ở các góc thư.
   - Trình phát nhạc nền du dương (nhạc không lời êm dịu) với nút bật/tắt ở góc trên.
   - Nút "Gửi trọn bình yên" tạo hiệu ứng trái tim bay lượn nhẹ nhàng.
   - Tương thích hoàn hảo (responsive) trên mọi kích thước màn hình từ điện thoại dọc đến máy tính.

---

## 🛠 Hướng Dẫn Tùy Biến Thông Tin (Chỉ mất 30 giây)

Mở tệp `index.html` bằng bất kỳ trình chỉnh sửa văn bản nào (Notepad, VS Code,...), kéo xuống phần `<script>` (khoảng dòng 270) và chỉnh sửa object `CONFIG`:

```javascript
const CONFIG = {
  // 1. Đổi ngày sinh của bạn ấy (chấp nhận cả ngày/tháng/năm hoặc ngày/tháng)
  validBirthdays: [
    "20/10/2000",   // Ví dụ: Ngày sinh của bạn ấy
    "20/10",
    "20102000"
  ],

  // 2. Tên hoặc danh xưng gọi bạn ấy:
  recipientTitle: "Gửi một người đặc biệt,", // Hoặc: "Gửi Mai Anh,", "Gửi em,"

  // 3. Tên người gửi ở chữ ký:
  senderSignature: "Một người luôn dõi theo",

  // 4. Lời chúc 20/10 (bạn có thể viết lại theo cảm xúc riêng nếu muốn)
  letterParagraphs: [
    "Có những ngày giữa tháng Mười, khi tiết trời chuyển mình dịu lại...",
    ...
  ]
};
```

---

## 🚀 Cách Sử Dụng
Chỉ cần nhấp đúp vào tệp `index.html` để mở ngay trên trình duyệt (Chrome, Edge, Safari, Firefox), hoặc tải lên GitHub Pages / Vercel / Netlify để gửi link cho cô ấy qua tin nhắn!
