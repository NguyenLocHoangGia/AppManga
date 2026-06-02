# AppManga
Project Overview

Tên dự án: AppManga — ứng dụng đọc/trình bày manga trên nền tảng di động.
Mục tiêu: Hiển thị nội dung manga, quản lý thư viện người dùng, đồng bộ/đăng nhập, và cung cấp trải nghiệm đọc mượt mà trên Android/iOS.
Công nghệ chính

Framework UI: Flutter (SDK) — giao diện cross-platform.
Backend / Services: Firebase (xuất hiện google-services.json → khả năng dùng Auth/Firestore/Analytics/Cloud Messaging).
Build hệ sinh thái Android: Gradle (build.gradle, gradlew.bat, proguard-rules.pro).
Ngôn ngữ scripts/build: Groovy (Gradle scripts).
Native (Android): Kotlin / Java (bridge/native plugins).
Tooling & khác: Android SDK, ProGuard/R8 (obfuscation), Android resources & assets pipeline.
Ngôn ngữ lập trình

Dart: Ứng dụng Flutter chính.
Kotlin / Java: Phần native Android (platform channels, plugins).
Groovy: Gradle build scripts.
(Có thể có Swift/Objective-C nếu dự án triển khai native iOS phần tương ứng.)
Key Responsibilities

UI/UX Implementation: Thiết kế và hiện thực giao diện đọc, danh sách, chi tiết truyện, và chuyển động mượt.
State Management: Lựa chọn và duy trì state (Provider, Riverpod, Bloc, v.v.) cho logic ứng dụng.
API & Data Integration: Tích hợp nguồn dữ liệu manga (REST/GraphQL hoặc Firebase), xử lý pagination và caching.
Firebase Integration: Cấu hình Auth, Firestore/Realtime DB, Storage, FCM, Analytics theo yêu cầu.
Native Plugins / Platform Channels: Viết/duy trì mã Kotlin/Java (hoặc Swift) cho tính năng native (download, file I/O, DRM nếu có).
Build & Release: Quản lý cấu hình Gradle, keystore, ProGuard/R8, tự động hóa CI/CD và phát hành lên Play Store / App Store.
Performance & Memory: Tối ưu danh sách ảnh, lazy loading, decoding ảnh, giảm lag ở trang đọc.
Offline / Sync: Thiết kế lưu cache offline, đồng bộ hóa trạng thái người dùng khi có mạng.
Testing: Viết unit tests, widget tests, integration tests và kiểm thử thủ công trải nghiệm đọc.
Localization & Accessibility: Hỗ trợ đa ngôn ngữ và các chuẩn truy cập (font scaling, talkback).
Security & Privacy: Bảo vệ dữ liệu người dùng, quản lý quyền truy cập file, tuân thủ chính sách lưu trữ/thu thập dữ liệu.
Monitoring & Maintenance: Log/analytics, crash reporting, cập nhật phụ thuộc và sửa lỗi bảo trì.
