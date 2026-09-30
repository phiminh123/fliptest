FLIPBOOK SOFT-PAGE DEMO
=======================

Các file:
- index.html
- page1.jpg
- page2.jpg
- page3.jpg
- page4.jpg

Cách thử:
1. Cách tốt nhất là push toàn bộ file lên GitHub Pages.
2. Mở URL GitHub Pages của repo.
3. Đưa chuột vào góc phải của trang.
4. Giữ chuột và kéo CHẬM sang trái để thấy vùng trang uốn/cong và bóng động.

Lưu ý:
- index.html tải StPageFlip từ jsDelivr CDN nên cần Internet.
- Tất cả page đều đặt data-density="soft".
- Nếu chỉ bấm nút Trang sau, animation diễn ra tự động nên cảm giác cong không rõ bằng kéo chuột.

Cách update repo:
git add .
git commit -m "Improve soft page flip effect"
git push

Đổi ảnh:
Thay page1.jpg ... page4.jpg bằng ảnh của bạn nhưng giữ nguyên tên,
hoặc sửa src trong index.html.
