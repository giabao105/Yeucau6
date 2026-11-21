# Yeucau6
Phân tích dữ liệu bất động sản
# 📊 Phân Tích Dữ Liệu Bất Động Sản & Dự Đoán Giá Nhà

## 📖 Giới thiệu
Mini-project này thực hiện phân tích tập dữ liệu bất động sản, trực quan hóa và xây dựng mô hình Học máy (Random Forest) để dự đoán giá nhà. Dự án tích hợp hệ thống tự động sinh báo cáo PDF và một Dashboard tương tác.

## 🚀 Tính năng chính
- Làm sạch và phân tích dữ liệu khám phá (EDA) với `pandas`, `seaborn`.
- Huấn luyện mô hình Random Forest Regressor với `scikit-learn`.
- Sinh báo cáo khoa học tự động xuất định dạng PDF bằng `fpdf`.
- Dashboard Web tương tác trực quan bằng `gradio`.

## 📂 Cấu trúc Repository
- `data.csv`: Tập dữ liệu mẫu (đầu vào).
- `src`: Mã nguồn Google Colab chứa pipeline xử lý dữ liệu, huấn luyện AI và UI Dashboard.
- `BaoCao_PhanTich_GiaNha.pdf`: Báo cáo đánh giá mô hình tự động sinh từ mã nguồn.
- `requirements.txt`: Danh sách các thư viện Python phụ thuộc.
## 🛠 Hướng dẫn chạy dự án
1. Clone repository về máy:
   ```bash
   git clone [https://github.com/giabao105/Yeucau6.git](https://github.com/giabao105/Yeucau6.git)
Cài đặt các thư viện cần thiết:
 ```bash
pip install -r requirements.txt
Mở file analysis_dashboard.ipynb bằng Jupyter Notebook hoặc tải lên Google Colab để chạy từng ô lệnh.
