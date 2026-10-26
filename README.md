# TC Media Global V2 — Dữ liệu video công khai

Đây là repository dữ liệu công khai dành cho ứng dụng Android **TC Media Global V2**.

Ứng dụng có các mục **Music, Shorts, Tivi và Phim**; danh mục video YouTube được cập nhật bằng GitHub Actions từ repository Android riêng. Đây không phải repository chứa source Android.

- **Trang thông tin:** https://assetskinscom.github.io/tc-media-global-data/
- **Danh mục video:** https://assetskinscom.github.io/tc-media-global-data/data/feed.json
- **Trạng thái đồng bộ:** https://assetskinscom.github.io/tc-media-global-data/data/status.json
- **Chính sách quyền riêng tư:** https://assetskinscom.github.io/tc-media-global-data/privacy.html

Dữ liệu lấy từ những kênh YouTube công khai; video được phát thông qua trình phát nhúng của YouTube. Khả năng xem phụ thuộc vào chủ sở hữu nội dung, YouTube và kết nối mạng. Tivi dùng các nguồn stream của bên thứ ba.

**Lưu ý cho người quản trị:** Các file `data/*.json` là dữ liệu đang hoạt động. Không ghi đè dữ liệu mới bằng snapshot trong ZIP V1/V2. Hệ thống đồng bộ từ `assetskinscom/tc-media-global-android` và cập nhật repo này khi job thành công.

File `TC_Media_Global_V1.apk` (nếu còn trong repo) là bản Android **V1 lưu trữ**, **không phải APK V2**. APK V2 cần build bằng GitHub Actions trong repo Android.
