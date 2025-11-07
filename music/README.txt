🎵 HƯỚNG DẪN SỬ DỤNG THỨ MỤC MUSIC 🎵
==========================================

📁 Thư mục này chứa các file nhạc MP3 để phát tự động khi mở trang web.

🎯 CÁCH THÊM NHẠC:
------------------
1. Copy file MP3 vào thư mục này
2. Đổi tên file thành: song1.mp3, song2.mp3, song3.mp3, ...
3. Refresh trang web

📝 CẬP NHẬT PLAYLIST:
---------------------
Mở file script.js và tìm đến phần "defaultPlaylist", 
sau đó cập nhật danh sách như sau:

const defaultPlaylist = [
    { file: 'music/song1.mp3', name: 'Tên Bài Hát 1', lyrics: null },
    { file: 'music/song2.mp3', name: 'Tên Bài Hát 2', lyrics: null },
    { file: 'music/song3.mp3', name: 'Tên Bài Hát 3', lyrics: null }
];

✨ TÍNH NĂNG TỰ ĐỘNG:
----------------------
- Trang sẽ TỰ ĐỘNG tìm và phát bài hát đầu tiên có trong thư mục
- AI sẽ TỰ ĐỘNG tạo lời bài hát
- Lyrics sẽ hiển thị tự động trong góc trái màn hình

🎶 VÍ DỤ:
---------
Nếu bạn có file: "Nơi Này Có Anh.mp3"
→ Đổi tên thành: song1.mp3
→ Cập nhật trong script.js:
   { file: 'music/song1.mp3', name: 'Nơi Này Có Anh', lyrics: null }

💡 LƯU Ý:
---------
- Chỉ hỗ trợ file MP3
- Tên file không nên có dấu hoặc ký tự đặc biệt
- Trang sẽ tự động phát nhạc sau 1 giây khi load xong
- Nếu trình duyệt chặn auto-play, click vào đĩa nhạc để phát thủ công

🎉 Chúc bạn thưởng thức âm nhạc vui vẻ! 🎵✨

