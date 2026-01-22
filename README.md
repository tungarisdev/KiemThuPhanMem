08/01/2025
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/34ecb92a-b1a4-4707-915d-18468a153aac" />

09/01/2025
## Cách chạy chương trình
1. Mở project bằng IDE (IntelliJ / Eclipse)
2. Chạy file `StudentAnalyzerTest`
3. Kiểm tra kết quả test (PASS)

## Kiểm thử đơn vị
- Đã kiểm thử trường hợp bình thường
- Trường hợp biên
- Trường hợp dữ liệu sai

22/01/2025
Báo cáo kiểm thử hiệu năng với JMeter

## Website kiểm thử
https://vnexpress.net

## Công cụ
Apache JMeter

## Kịch bản kiểm thử

### Thread Group 1 – Cơ bản
- 10 users
- Loop: 5
- GET trang chủ

### Thread Group 2 – Tải nặng
- 50 users
- Ramp-up: 30s
- GET trang chủ + trang con

### Thread Group 3 – Tùy chỉnh
- 20 users
- Duration: 60s
- GET 2 trang con

## Kết quả
- Response Time
- Throughput
- Error Rate

Chi tiết xem trong thư mục results/
