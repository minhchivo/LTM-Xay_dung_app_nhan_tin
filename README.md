1. Mô tả sản phẩm
Tên dự án: Xây Dựng Ứng Dụng Nhắn Tin Bằng C#
Mô tả ngắn: Đây là một ứng dụng nhắn tin hỗ trợ giao tiếp thời gian thực giữa các người dùng. Hệ thống cho phép gửi tin nhắn văn bản, hình ảnh, voice (âm thanh), chia sẻ file (Word, Excel, PDF), và tạo nhóm chat để giao tiếp với nhiều người dùng cùng lúc. Được xây dựng với C#, ứng dụng này cung cấp trải nghiệm nhắn tin tiện lợi và dễ sử dụng với giao diện thân thiện trên Windows Forms.
2. Chức năng của sản phẩm
Gửi văn bản: Cho phép người dùng gửi tin nhắn dạng văn bản cho các tài khoản khác. Tất cả tin nhắn văn bản được lưu trữ và đồng bộ hóa trên Firebase Realtime Database.
Gửi hình ảnh: Hỗ trợ gửi hình ảnh trực tiếp bằng cách tải lên Cloudinary và gửi URL ảnh cho người nhận, cho phép truy cập dễ dàng và an toàn.
Gửi voice âm thanh: Cho phép người dùng ghi âm và gửi các đoạn ghi âm ngắn qua ứng dụng. Tính năng này được hỗ trợ bởi NAudio để ghi và phát âm thanh, và Cloudinary để lưu trữ file âm thanh.
Gửi File: Hỗ trợ gửi các loại file (như Word, Excel, PDF) bằng cách tải lên Cloudinary và gửi URL tải xuống cho người nhận.
Lập nhóm chat: Người dùng có thể tạo nhóm và trò chuyện trực tuyến với nhiều người dùng khác cùng lúc. Firebase Realtime Database được sử dụng để lưu trữ dữ liệu nhóm và tin nhắn nhóm.
Giao tiếp thời gian thực (Real-time Communication): Tất cả các tin nhắn đều được gửi và nhận trong thời gian thực, đảm bảo trải nghiệm tương tác nhanh chóng. Tính năng này được hỗ trợ bởi Firebase Realtime Database và Reactive Extensions, giúp cập nhật UI ngay khi có tin nhắn mới.
3. Yêu cầu về phần cứng và phần mềm
Phần mềm:
Hệ điều hành: Windows 10 hoặc cao hơn.
IDE: Visual Studio 2019 hoặc 2022 với cài đặt .NET Framework 4.7.2 trở lên.
Framework: .NET Framework hoặc .NET Core phù hợp với phiên bản dự án.
Phần cứng:
RAM: Tối thiểu 4GB (khuyến nghị 8GB để có hiệu suất tốt hơn).
Bộ xử lý: Intel i3 hoặc tương đương (khuyến nghị i5 trở lên).
Dung lượng lưu trữ: 500MB dung lượng trống cho dự án và các tài nguyên liên quan.
4. Công nghệ sử dụng
Firebase Realtime Database: Lưu trữ và đồng bộ tin nhắn giữa người dùng theo thời gian thực.
Cloudinary: Lưu trữ và chia sẻ file (hình ảnh, âm thanh, video, tài liệu).
Reactive Extensions (Rx): Theo dõi sự thay đổi của dữ liệu từ Firebase và cập nhật UI thời gian thực.
NAudio: Ghi âm và phát lại các đoạn âm thanh (voice message).
System.Net.Http: Hỗ trợ tải file từ Cloudinary hoặc Firebase, hỗ trợ tải và chia sẻ file.
System.IO: Xử lý file và thư mục, lưu trữ tạm thời các file trước khi tải lên hoặc phát.
Windows Forms Controls: Các điều khiển như ListBox, CheckedListBox, TableLayoutPanel, FlowLayoutPanel, Label, LinkLabel, PictureBox và RichTextBox giúp hiển thị giao diện người dùng cho ứng dụng chat.
Asynchronous Programming (async/await): Xử lý các tác vụ không đồng bộ giúp cải thiện hiệu suất và trải nghiệm người dùng.
5. Mục tiêu của ứng dụng
Ứng dụng nhắn tin này nhằm hỗ trợ người dùng giao tiếp và chia sẻ thông tin nhanh chóng và hiệu quả. Các tính năng đa phương tiện và real-time communication sẽ mang đến trải nghiệm tốt nhất, đáp ứng nhu cầu liên lạc và chia sẻ tài liệu trong nhiều môi trường khác nhau, bao gồm cá nhân và nhóm.

