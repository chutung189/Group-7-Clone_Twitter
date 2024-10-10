#Tổng quan
Dự án Twitter Clone sử dụng Node.js, MongoDB, React, Express, và Tailwind tập trung vào việc tạo ra một ứng dụng mạng xã hội tương tự Twitter, với các tính năng cốt lõi như đăng bài, theo dõi người dùng, và tương tác với bài đăng.

##Thành phần chính của dự án:
###Frontend (React + Tailwind):

*React sẽ quản lý giao diện người dùng, với các thành phần tương tác như form đăng nhập, đăng ký, và giao diện dòng thời gian.
Tailwind CSS giúp tạo kiểu cho giao diện một cách nhanh chóng và hiệu quả, đảm bảo giao diện người dùng đẹp mắt, hiện đại và dễ sử dụng.
Người dùng có thể đăng nhập, đăng tweet, xem feed cá nhân, tương tác với các tweet bằng cách like, comment, và retweet.
Backend (Node.js + Express):

*Node.js kết hợp với Express để xây dựng API RESTful xử lý các yêu cầu như tạo người dùng, đăng nhập, đăng bài, và theo dõi người dùng.
Quản lý xác thực người dùng qua JWT (JSON Web Tokens) để đảm bảo bảo mật.
Cơ sở dữ liệu (MongoDB):

*MongoDB được sử dụng để lưu trữ dữ liệu người dùng, tweet, tương tác, và các mối quan hệ theo dõi.
Dữ liệu được tổ chức dưới dạng tài liệu JSON, giúp dễ dàng quản lý các thông tin động như số lượng like, comment, và danh sách người theo dõi.
##Các tính năng chính:
*Đăng ký, đăng nhập và xác thực người dùng.
*Đăng bài viết ngắn (tweet) và xem dòng thời gian các bài đăng.
*Tính năng theo dõi người dùng, like, comment, và retweet.
*Hiển thị feed với các tweet của người dùng đã theo dõi.
*Dự án sử dụng kiến trúc MERN (MongoDB, Express, React, Node.js), dễ mở rộng và duy trì.v

## Công nghệ sử dụng
React.js, MongoDB, Node.js, Express, Tailwind
# Một số chức năng:
*🔐 **Xác thực với JSONWEBTOKENS (JWT)**
*🔥 **React Query để lấy dữ liệu, lưu trữ vào bộ nhớ đệm, v.v.**
*👥 **Người dùng được gợi ý để theo dõi**
*✍️ **Tạo bài viết**
*🗑️ **Xóa bài viết**
*💬 **Bình luận trên bài viết**
*❤️ **Thích bài viết**
*🔒 **Xóa bài viết (nếu bạn là chủ sở hữu)**
*📝 **Chỉnh sửa thông tin hồ sơ**
*🖼️ **Chỉnh sửa ảnh bìa và ảnh đại diện**
*📷 **Tải ảnh lên bằng Cloudinary**
*🔔 **Gửi thông báo**
*🌐 **Triển khai ứng dụng**
