​🚀 Nhóm 3 - Dự Án Website Kỷ Niệm & Kết Nối 

​Chào mừng bạn đến với kho lưu trữ mã nguồn chính thức của Nhóm 3. Đây là dự án web được xây dựng nhằm giới thiệu các thành viên trong đội ngũ và tạo không gian tương tác trực tuyến thông minh.

​🌟 Tính năng nổi bật 

​Dự án hiện tại bao gồm hai phân hệ chính:

​1. Trang Giới Thiệu Thành Viên (member.html) 

​Một giao diện hiện đại giúp hiển thị thông tin nhân sự của nhóm một cách trực quan.

​Giao diện Adaptive: Sử dụng Tailwind CSS mang lại trải nghiệm mượt mà trên cả máy tính và điện thoại. ​Hiệu ứng thị giác: Card thành viên có hiệu ứng hover 3D, avatar đổ bóng gradient và animation khi tải trang. ​Quản lý dữ liệu linh hoạt: Thông tin thành viên (tên, chức vụ, ngày sinh, tiểu sử) được quản lý tập trung bằng mảng JavaScript, dễ dàng cập nhật mà không cần can thiệp sâu vào HTML. ​Chỉ số nhận diện: Phân loại chức vụ (Trưởng nhóm, Thư ký, Kỹ thuật...) bằng các Badge màu sắc riêng biệt. ​2. Kênh Chat Thông Minh (chatv2.html) 

​Hệ thống trò chuyện thời gian thực tích hợp trí tuệ nhân tạo (AI).

​Real-time Backend: Kết nối với Firebase Firestore để đồng bộ tin nhắn ngay lập tức. ​Hệ thống Auth: Hỗ trợ Đăng ký/Đăng nhập bảo mật qua Firebase Authentication. ​Tích hợp AI (Gemini Flash 2.0): ​Trau chuốt tin nhắn: Tự động sửa lỗi chính tả và chuyển đổi văn phong lịch sự. ​Dịch thuật đa ngôn ngữ: Dịch nhanh Việt - Anh trực tiếp tại khung soạn thảo. ​Gợi ý trả lời thông minh: AI phân tích ngữ cảnh 10 tin nhắn gần nhất để đưa ra 3 lựa chọn phản hồi nhanh. ​Tóm tắt nội dung: Tính năng độc đáo giúp tóm tắt toàn bộ cuộc hội thoại (30 tin gần nhất) thành các ý chính. ​🛠 Công nghệ sử dụng ​Frontend: HTML5, CSS3, JavaScript (ES6+). ​Styling: Tailwind CSS, FontAwesome 6, Google Fonts (Be Vietnam Pro, Inter). ​Backend as a Service: Firebase (Firestore & Auth). ​AI Engine: Google Gemini API. ​Library: Marked.js (để hiển thị định dạng Markdown cho AI). ​🚀 Hướng dẫn cài đặt 

​Để chạy dự án này trên môi trường local hoặc deploy lên GitHub Pages/Vercel, bạn cần thực hiện các bước sau:

​Cấu hình Firebase: ​Truy cập Firebase Console. ​Tạo dự án mới và lấy thông tin firebaseConfig. ​Dán thông tin vào đoạn code const firebaseConfig = { ... } trong file chatv2.html. ​Cấu hình AI: ​Lấy API Key tại Google AI Studio. ​Thay thế vào biến GEMINI_API_KEY trong file chatv2.html. ​Triển khai: ​Mở các file .html trực tiếp trên trình duyệt hoặc sử dụng Live Server trong VS Code. ​📝 Ghi chú 

​Dự án này được phát triển bởi Nhóm 3 (Lớp 12A3) nhằm mục đích học tập và lưu giữ kỷ niệm. Mọi đóng góp về mã nguồn đều được hoan nghênh.

​© 2026 - Phát triển bởi Nhóm 3.


