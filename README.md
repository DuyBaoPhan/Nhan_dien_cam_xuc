Giới thiệu
  Dự án này triển khai hệ thống nhận diện cảm xúc từ khuôn mặt sử dụng Haar Cascade để phát hiện khuôn mặt và mô hình học máy để nhận diện cảm xúc. Hệ thống hoạt động trên các ảnh đầu vào hoặc luồng video từ camera mà không cần giao diện PyQt5, tập trung vào việc xử lý và phân tích hình ảnh trực tiếp.

Tính năng
  Nhận Diện Khuôn Mặt: Sử dụng file haarcascade_frontalface_default.xml từ OpenCV để phát hiện khuôn mặt.
  Nhận Diện Cảm Xúc: Sau khi phát hiện khuôn mặt, hệ thống sử dụng mô hình học máy để phân loại cảm xúc như vui, buồn, tức giận, sợ hãi, v.v.
  Xử Lý Video Thực Tế: Có khả năng xử lý và nhận diện cảm xúc từ luồng video trực tiếp qua camera.

Các Thư Viện Cần Thiết
  Python 3.x
  OpenCV (cho việc phát hiện khuôn mặt và xử lý video)
  TensorFlow/Keras hoặc PyTorch (cho mô hình nhận diện cảm xúc)
  Pandas (để lưu trữ dữ liệu và quản lý lịch sử)
