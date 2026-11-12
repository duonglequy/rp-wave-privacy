# Chính sách quyền riêng tư – R&P Wave

Cập nhật lần cuối: 12/11/2026

R&P Wave ("ứng dụng") là ứng dụng nội bộ của Công ty TNHH R&P Electronics (R&P Electronics Company Limited, "công ty", "chúng tôi") dành cho Ban giám đốc: xem số liệu ERP, duyệt chứng từ và nhận thông báo. Ứng dụng không phục vụ khách hàng hay công chúng; chỉ người có tài khoản ERP do công ty cấp mới đăng nhập được.

## 1. Dữ liệu chúng tôi xử lý

| Dữ liệu | Mục đích |
|---|---|
| Tài khoản ERP (tên đăng nhập, họ tên, vai trò và quyền) và mã OTP xác thực | Đăng nhập, quyết định người dùng được xem và duyệt gì |
| Mã thiết bị do ứng dụng tạo, loại thiết bị (iOS/Android), phiên bản ứng dụng | Quản lý thiết bị đã đăng nhập, thu hồi thiết bị |
| Mã đăng ký thông báo đẩy (FCM/APNs) | Gửi thông báo duyệt chứng từ và cảnh báo |
| Địa chỉ IP và thời điểm truy cập | Bảo mật và ghi nhật ký kiểm soát truy cập vào ERP |
| Quyết định duyệt/từ chối của bạn kèm ghi chú | Ghi vào chứng từ trong ERP |

Số liệu kinh doanh (doanh thu, biên lợi nhuận gộp ước tính, báo giá nhà cung cấp, chứng từ chờ duyệt) là dữ liệu của công ty, hiển thị trên màn hình theo quyền của bạn. Ứng dụng **không lưu** các số liệu về chi phí, báo giá hay tệp báo giá vào bộ nhớ máy. Ứng dụng chặn chụp màn hình và quay màn hình, và xem trước trong danh sách ứng dụng gần đây bị làm mờ.

Face ID / vân tay / khoá màn hình chỉ do hệ điều hành xử lý để mở khoá ứng dụng và xác nhận quyết định duyệt; ứng dụng không nhận được dữ liệu sinh trắc học.

Chúng tôi **không** thu thập vị trí, danh bạ, ảnh, micro hay camera. Ứng dụng không có quảng cáo, không dùng công cụ theo dõi hay phân tích của bên thứ ba, không bán hay chia sẻ dữ liệu cho mục đích tiếp thị.

## 2. Dữ liệu được lưu ở đâu

- Dữ liệu ERP nằm trên máy chủ của công ty, đặt tại khu vực AWS Singapore (ap-southeast-1), và được truyền qua kết nối mã hoá HTTPS.
- Google Firebase Cloud Messaging (FCM) và Apple Push Notification service (APNs) chỉ dùng để chuyển thông báo đến thiết bị. Nội dung thông báo được giữ ngắn; mã đăng ký thông báo được chuyển cho các dịch vụ này theo cơ chế của hệ điều hành.
- Trên thiết bị chỉ lưu mã phiên đăng nhập (trong Keychain của iOS hoặc kho khoá của Android) và các lựa chọn giao diện (ngôn ngữ, giao diện sáng/tối).

## 3. Thời gian lưu giữ

- Mã phiên và mã thiết bị: đến khi bạn đăng xuất, công ty thu hồi thiết bị hoặc phiên hết hạn.
- Mã đăng ký thông báo: xoá khỏi máy chủ khi bạn đăng xuất hoặc thu hồi thiết bị, hoặc khi dịch vụ thông báo báo mã không còn hiệu lực.
- Nhật ký truy cập (IP, thời điểm): giữ theo chính sách bảo mật của công ty để điều tra sự cố, tối đa 12 tháng.
- Chứng từ và quyết định duyệt là hồ sơ kế toán – kinh doanh của công ty, giữ theo quy định pháp luật về kế toán.

## 4. Quyền của bạn và việc xoá dữ liệu

- Đăng xuất trong ứng dụng (Cài đặt) sẽ xoá phiên và mã thông báo của thiết bị đó khỏi thiết bị và máy chủ.
- Quản trị viên có thể thu hồi từng thiết bị hoặc khoá tài khoản bất kỳ lúc nào.
- Tài khoản ERP do công ty quản lý, không tạo được trong ứng dụng. Việc xoá hoặc chỉnh sửa tài khoản, hoặc yêu cầu xem dữ liệu cá nhân của bạn, gửi tới admin@rpc.vn; chúng tôi trả lời trong vòng 30 ngày. Một số bản ghi (ví dụ chứng từ bạn đã duyệt) phải được giữ theo pháp luật.
- Chế độ "Dùng thử" dùng dữ liệu mẫu nằm trong ứng dụng, không cần tài khoản, không gửi gì tới máy chủ.

## 5. Trẻ em

Ứng dụng dành cho nhân sự cấp quản lý của công ty và không hướng tới người dưới 18 tuổi.

## 6. Thay đổi chính sách

Khi có thay đổi, chúng tôi cập nhật trang này và ngày "Cập nhật lần cuối".

## 7. Liên hệ

Công ty TNHH R&P Electronics (R&P Electronics Company Limited)
Email: admin@rpc.vn · Website: https://www.rpc.vn
