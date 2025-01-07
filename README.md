## Giới thiệu
Dự án này được phát triển bởi Hoàng Quang Huy - 21021663

Đây là một dự án phát triển một ứng dụng di động dự báo thời tiết.

Với ứng dụng này, bạn có thể xem các thông tin thời tiết hiện tại, dự báo thời tiết trong những ngày sắp tới và nhiều tính năng khác.

Framework: React Native và Expo

APIs: Open Weather App, Google Air Quality và Google Pollen API

## Tính năng chính
1. Xem dữ liệu thời tiết hiện tại và dự báo (bao gồm nhiệt độ, độ ẩm, tốc độ gió, áp suất không khí, lượng mưa, chất lượng không khí, chu kỳ mặt trời và mặt trăng, ...).
2. Sử dụng vị trí hiện tại qua GPS hoặc tìm kiếm địa điểm theo tên và Google Map.
3. Cung cấp danh sách các địa điểm yêu thích để giúp người dùng tìm kiếm nhanh hơn.
4. Hiển thị bản đồ nhiệt (heatmap) cho các dữ liệu thời tiết để trực quan hơn.
5. Gửi thông báo trực tiếp và hàng ngày về thời tiết.
6. Tạo widget thời tiết trên màn hình chính.
7. Chia sẻ ứng dụng với người khác qua mạng xã hội.
8. Lựa chọn ngôn ngữ, đơn vị đo lường và chủ đề màu sắc theo sở thích.

## Hướng dẫn set up chi tiết
- Tạo một tệp .env và thêm các khóa API vào, ví dụ:
```
API_KEY=OPEN_WEATHER_API_KEY
GOOGLE_KEY=GOOGLE_API_KEY
```

Sau khi clone dự án, chạy các lệnh sau để cài đặt các module cần thiết:

```
    npm install
    npx expo install
```

Cuối cùng, để chạy dự án, sử dụng lệnh:

```
    npx expo start
```

## Cách build ứng dụng
- Để sử dụng tính năng widget và thông báo, bạn cần build ứng dụng.
- Lưu ý rằng chúng tôi chỉ sử dụng tùy chọn build cục bộ của Expo, vì vậy các tùy chọn khác có thể không hoạt động.
- Đây là một số lỗi thường gặp trong quá trình build và cách khắc phục:
1. Không tìm thấy vị trí SDK: thêm biến đường dẫn đến vị trí SDK.
2. Không tìm thấy "RNSS Screen": tìm và tải tất cả các module cần thiết.
3. Không tìm thấy splashscreen_background: thêm màu có tên splashscreen_background vào tệp colors.xml.


##
Ứng dụng được phát triển trong thời gian rất ngắn, do đó khó tránh khỏi lỗi. Nếu bạn gặp lỗi, hãy liên hệ với tôi qua GitHub hoặc thông qua Repo Issue.