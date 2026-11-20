# Alarm Guard (Android / OPPO)

Mở thư mục `AlarmGuard` bằng Android Studio (JDK 17), chờ Gradle Sync (cần mạng để tải Gradle/Android SDK lần đầu), chọn **Build > Build APK(s)**. APK ở `app/build/outputs/apk/debug/app-debug.apk`.

App báo thức riêng: chọn giờ, PIN, báo thức chính xác, âm thanh lặp và màn hình nhập PIN. Khi reo app cố đưa âm lượng báo thức lên tối thiểu 50% sau mỗi 1,5 giây.

**Giới hạn:** Không chặn được hoàn toàn nút âm lượng hoặc bảng âm lượng ColorOS, không chống được tắt nguồn, buộc dừng, thu hồi quyền, hoặc hệ thống giới hạn chạy nền. Android 14+ có thể giới hạn full-screen intent; vào Settings > Apps > Special app access > Full screen intents nếu có. Cấp quyền thông báo, báo thức chính xác và cho phép chạy nền trên OPPO. Kiểm tra thử trước khi dùng để đi học/đi làm.

Không có APK build sẵn vì môi trường tạo mã nguồn chưa có Android SDK/Gradle.
