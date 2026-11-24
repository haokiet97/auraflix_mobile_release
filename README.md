# AuraFlix Mobile — Kênh phát hành

APK chính thức cho **điện thoại Android** của AuraFlix (cài song song với bản TV).

🌐 **Trang giới thiệu & tải nhanh:** <https://haokiet97.github.io/auraflix_mobile_release/>

📘 **Hướng dẫn phát hành:** <https://github.com/haokiet97/auraflix_tv/blob/master/docs/RELEASE_GUIDE_MOBILE.md>

## Tải bản mới nhất

➡️ **https://github.com/haokiet97/auraflix_mobile_release/releases/latest**

| Phiên bản | APK | Dung lượng |
|---|---|---|
| 1.0.0 | `AuraFlixMobile-1.0.0.apk` | 3.07 MB |

## Cài đặt

1. Tải APK ở mục **Releases**.
2. Mở tệp trên điện thoại; nếu bị chặn, bật *Cài đặt → Bảo mật → Cài đặt ứng dụng không rõ nguồn gốc*.
3. Cài đè để giữ nguyên lịch sử xem và yêu thích.

Hoặc qua ADB:

```bash
adb install -r AuraFlixMobile-1.0.0.apk
```

## Cập nhật trong ứng dụng

AuraFlix Mobile tự kiểm tra repo này trong **Cài đặt → Cập nhật ứng dụng**, tải APK có tiến độ,
xác thực SHA-256 rồi mở trình cài đặt hệ thống.

- Package: `com.auraflix.mobile`
- Yêu cầu: Android 5.0 (API 21) trở lên
- Ký bằng debug keystore (bản phát hành nội bộ)

## Lưu ý

Ứng dụng chỉ là trình duyệt nội dung, không lưu trữ hay phát tán phim.
Toàn bộ nội dung và bản quyền thuộc về các nhà cung cấp gốc.
