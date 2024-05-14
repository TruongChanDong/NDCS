# Digit Recognition Project
# Tổng quan
Dự án này nhằm mục đích phát triển một hệ thống nhận dạng chữ số có khả năng nhận dạng chính xác các chữ số viết tay từ 0 đến 9. Hệ thống tận dụng các kỹ thuật học máy, bao gồm mạng thần kinh và máy vectơ hỗ trợ (SVM), để đạt được độ chính xác cao trong phân loại chữ số.

![image](https://github.com/TruongChanDong/NDCS/assets/79720049/829d6ddf-746e-4e32-abb8-8f75d67ac8b6)


# Đặc trưng
- Giao diện vẽ chữ số viết tay: Người dùng có thể vẽ chữ số trực tiếp trên canvas do ứng dụng web cung cấp.
- Chức năng tải lên: Người dùng cũng có thể tải lên hình ảnh chứa các chữ số viết tay để nhận dạng.
- Nhận dạng chữ số theo thời gian thực: Hệ thống cung cấp khả năng nhận dạng theo thời gian thực các chữ số viết tay khi người dùng vẽ hoặc tải hình ảnh lên.
- Độ chính xác cao: Các mô hình nhận dạng chữ số được huấn luyện trên bộ dữ liệu lớn như MNIST để đạt được độ chính xác cao trong phân loại.
# Công nghệ được sử dụng
- Python: Phần backend của ứng dụng được phát triển bằng ngôn ngữ lập trình Python.
- TensorFlow: Thư viện TensorFlow được sử dụng để xây dựng và huấn luyện các mô hình mạng nơron nhằm nhận dạng chữ số.
- Scikit-learn: Thư viện Scikit-learn được sử dụng để triển khai các mô hình SVM để phân loại chữ số.
- OpenCV: OpenCV được sử dụng cho các tác vụ xử lý hình ảnh như thay đổi kích thước hình ảnh và phát hiện đường viền.
- HTML/CSS/JavaScript: Giao diện người dùng của ứng dụng được phát triển bằng HTML, CSS và JavaScript để tạo giao diện người dùng trực quan.
# Bắt đầu
Để chạy ứng dụng cục bộ, hãy làm theo các bước sau:

1.Sao chép kho lưu trữ vào máy cục bộ của bạn.

2.Chạy ứng dụng Flask bằng cách thực thi python app.py.

3.Truy cập ứng dụng trong trình duyệt web của bạn tại: http://127.0.0.1:5000
![image](https://github.com/TruongChanDong/NDCS/assets/79720049/533000ca-d49a-44ba-b20d-af4533410938)


# Những cải tiến trong tương lai
- Triển khai các mô hình học sâu nâng cao hơn để nhận dạng chữ số nhằm cải thiện độ chính xác hơn nữa.
- Nâng cao giao diện người dùng với các tính năng bổ sung như lựa chọn màu sắc và điều chỉnh độ dày nét vẽ.
- Tối ưu hóa quy trình xử lý hình ảnh để nhận dạng chữ số nhanh hơn và hiệu quả hơn.
- Triển khai ứng dụng lên máy chủ web để truy cập trực tuyến.
