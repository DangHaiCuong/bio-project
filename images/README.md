# Hướng dẫn thêm ảnh profile

## Cách 1: Sử dụng ảnh local (Đơn giản nhất)

1. Copy ảnh của bạn vào thư mục `images/`
2. Đổi tên ảnh thành `profile.jpg` hoặc `profile.png`
3. Mở file `index.html` và tìm dòng:
   ```html
   <img src="images/profile.jpg" alt="Thủy Tiên">
   ```
4. Đảm bảo tên file khớp với ảnh bạn vừa thêm

## Cách 2: Sử dụng link từ Internet

### Upload ảnh lên Imgur (Miễn phí):
1. Truy cập https://imgur.com/upload
2. Kéo thả ảnh của bạn vào
3. Click chuột phải vào ảnh → "Copy image address"
4. Dán link vào file `index.html` thay thế cho `images/profile.jpg`

### Hoặc upload lên GitHub:
1. Tạo repository trên GitHub
2. Upload ảnh vào đó
3. Lấy raw link của ảnh

## Ghi chú:
- Ảnh nên có kích thước vuông (ví dụ: 400x400px) để hiển thị đẹp
- Format hỗ trợ: JPG, PNG, WebP
- Kích thước tối ưu: dưới 500KB

