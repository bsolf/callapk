# Kết Nối Call Bridge – Hướng dẫn build APK

## Cách 1: Android Studio (khuyên dùng)
1. Cài Android Studio (bản mới nhất).
2. File → Open → chọn thư mục `KetNoiCallBridge` → chờ Gradle sync xong.
3. Build → Build Bundle(s)/APK(s) → Build APK(s).
4. File ra ở `app/build/outputs/apk/debug/app-debug.apk`. Copy sang điện thoại và cài.

## Cách 2: Build online bằng GitHub (không cần cài gì)
1. Tạo repo GitHub (để Private), upload toàn bộ thư mục này lên.
2. Vào tab Actions → "Build APK" → Run workflow.
3. Chạy xong, tải file `KetNoiCallBridge-apk` ở mục Artifacts, giải nén ra `app-debug.apk`.

## Dùng app
1. Mở app → nhập PUBLIC_URL của server + Call Key (KN-XXXXXX, lấy ở mục Máy Android trên web).
2. Bấm BẮT ĐẦU KẾT NỐI, cấp đủ quyền → web hiện 🟢 Call Online.
3. Tắt tối ưu pin cho app (Cài đặt → Pin → Không hạn chế) để app chạy nền ổn định.
4. SMS vẫn dùng app riêng "SMS Gateway for Android".
