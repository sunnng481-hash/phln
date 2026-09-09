# phln
# 🎂 Birthday Website – GitHub Pages

Website sinh nhật 3 màn hình:
1. **9 tháng 9** – số chạy và dừng ở 9.
2. **Bánh sinh nhật** – nến cháy, nhấn giữ 10 giây để thổi, sau đó có lời chúc + pháo hoa.
3. **Trang kỷ niệm** – 4 khung ảnh và các ô text có thể chỉnh sửa.

## 🎵 Nhạc
Website có sẵn một bản **Happy Birthday phong cách guitar** do website tạo riêng, nằm ở:
`assets/happy_birthday_guitar.wav`

Không cần tải thêm nhạc để website hoạt động.

## 🚀 Đưa lên GitHub Pages
1. Tạo repository mới trên GitHub.
2. Upload **toàn bộ file và thư mục** trong ZIP.
3. Vào **Settings → Pages**.
4. Chọn **Deploy from a branch**.
5. Chọn branch `main`, thư mục `/ (root)` → Save.
6. Chờ GitHub deploy và mở URL được cung cấp.

## 📸 Thêm ảnh cố định
Trang kỷ niệm có 4 ô chọn ảnh. Đây là cách xem thử trực tiếp trên trình duyệt.
Nếu muốn ảnh nằm cố định trong website cho mọi người xem:
- Tạo thư mục `assets/photos/`
- Đặt ảnh vào đó
- Sửa HTML để trỏ tới `assets/photos/ten-anh.jpg`

## ✍️ Chỉnh chữ
Các phần có `contenteditable="true"` có thể sửa trong `index.html`.
Bạn cũng có thể mở website và chỉnh trực tiếp trên trình duyệt; trình duyệt sẽ lưu nội dung trong localStorage của thiết bị đó.

## 📱 Lưu ý iPhone
iPhone/Safari thường chặn autoplay. Vì vậy nhạc được bắt đầu sau khi người nhận **chạm vào màn hình để sang trang bánh**.
