# AI_BTL

AI_BTL là một dự án tập trung vào việc phát triển và triển khai các mô hình học máy để phân tích dữ liệu cảm biến.

## Nội dung

- [Giới thiệu](#giới-thiệu)
- [Cấu trúc dự án](#cấu-trúc-dự-án)
- [Hướng dẫn cài đặt](#hướng-dẫn-cài-đặt)
- [Cách sử dụng](#cách-sử-dụng)
- [Đóng góp](#đóng-góp)
- [Giấy phép](#giấy-phép)

## Giới thiệu

Dự án này nhằm xây dựng các mô hình học máy để phân tích dữ liệu từ các cảm biến. Nó bao gồm các tệp mã nguồn và dữ liệu cần thiết để huấn luyện và đánh giá mô hình.

## Cấu trúc dự án

- `Model_C++.cpp`: Mã nguồn C++ cho mô hình.
- `check_data.ipynb`: Notebook Jupyter để kiểm tra và khám phá dữ liệu cảm biến.
- `model_0.bst`, `model_1.bst`, `model_2.bst`: Các tệp mô hình đã được huấn luyện.
- `model_0.json`, `model_1.json`, `model_2.json`: Cấu hình mô hình ở định dạng JSON.
- `move_json_to_bst.py`: Script Python để chuyển đổi tệp JSON thành định dạng `.bst`.
- `sensor_data.csv`: Dữ liệu cảm biến được sử dụng để huấn luyện và đánh giá mô hình.
- `train.py`: Script Python để huấn luyện mô hình.

## Hướng dẫn cài đặt

1. **Clone kho lưu trữ:**

   ```bash
   git clone https://github.com/hoangbpm/AI_BTL.git
   cd AI_BTL
