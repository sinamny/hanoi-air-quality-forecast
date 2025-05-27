# Dự báo Chất lượng không khí Hà Nội (2022–2024)

Dự án này phân tích và dự báo chỉ số chất lượng không khí (AQI) tại Hà Nội bằng cách sử dụng dữ liệu lịch sử và mô hình chuỗi thời gian ARIMA.

## Mục tiêu

Hiểu xu hướng chất lượng không khí dài hạn và dự đoán AQI ngắn hạn để hỗ trợ công tác quy hoạch môi trường và nâng cao nhận thức cộng đồng.

## Phương pháp

* Làm sạch và xử lý dữ liệu (xử lý giá trị thiếu, chuyển định dạng ngày)
* Phân tích dữ liệu khám phá (EDA)
* Kiểm định tính dừng bằng ADF
* Xây dựng và huấn luyện mô hình ARIMA
* Đánh giá mô hình bằng chỉ số RMSE
* Trực quan hóa kết quả dự đoán so với giá trị thực tế

## 🛠Công nghệ sử dụng

* Python
* pandas
* statsmodels
* matplotlib

## Tệp chính

* `Hanoi_Air_Quality_ARIMA.ipynb`: Triển khai toàn bộ quy trình xử lý và mô hình dự báo chuỗi thời gian.
