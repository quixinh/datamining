# Đề tài: Phân tích, Khám phá và Phân loại Tấn công của Bộ Dữ liệu RT-IoT2022

- **Sinh viên thực hiện**: Tạ Hồng Quí (MSSV: 3122410348)  
- **Giảng viên hướng dẫn**: ThS. Nguyễn Thanh Phước

---

## 🔧 Hướng Dẫn Cài Đặt

Để dễ dàng đọc và chạy mã nguồn, Thầy có thể truy cập trực tiếp GitHub: [https://github.com/quixinh/datamining.git](https://github.com/quixinh/datamining.git)

Dưới đây là hướng dẫn thiết lập môi trường dự án, bao gồm Python và các thư viện cần thiết như scikit-learn, TensorFlow, PyTorch, v.v.

### 🧩 Yêu cầu
- **Python**: Phiên bản 3.10

### ✅ Các bước cài đặt

1. **Tạo và kích hoạt môi trường ảo**:
    ```bash
    python -m venv venv
    source venv/bin/activate      # Trên macOS/Linux
    venv\Scripts\activate         # Trên Windows
    ```

2. **Cài đặt các thư viện cần thiết**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Tải mã nguồn dự án**:
    ```bash
    git clone https://github.com/quixinh/datamining.git
    cd datamining
    ```

---

## 📁 Cấu trúc Thư mục `3122410348_`

- `data/`: Chứa dữ liệu huấn luyện cho mô hình.  
- `DOC/`: Lưu trữ bài báo cáo của đề tài.  
- `Document/`: Tài liệu tham khảo về cách thu thập dữ liệu RT-IoT2022.  
- `EDA/`: Chứa file `EDA.ipynb` dùng để khám phá và phân tích dữ liệu ban đầu.  
- `images/`: Lưu trữ các hình ảnh phân tích từ EDA và các biểu đồ khác.  
- `model/`: Lưu các mô hình đã huấn luyện tốt nhất.  
- `result_confusion_matrix/`: Lưu kết quả phân loại (ma trận nhầm lẫn), phục vụ cho đánh giá hiệu suất mô hình.  
- `DataProcessing.py`: Chứa các hàm xử lý dữ liệu.  
- `Preprocessing.py`: Chứa các hàm tiền xử lý dữ liệu.  
- `requirements.txt`: Danh sách thư viện cần cài đặt trước khi chạy chương trình.  
- `utils/`: Chứa các hàm hỗ trợ như vẽ biểu đồ, lưu mô hình, và các tiện ích khác.

---

## 📚 Tài liệu Tham khảo

[1] B. S. và Rohini Nagapadma. *RT-IoT2022*. UCI Machine Learning Repository, 2023. DOI: [10.24432/C5P338](https://doi.org/10.24432/C5P338)  

[2] Sharmila B. S., Jayashree H. R., Pradeep R., & Vijayalakshmi R.  
*Performance evaluation of parametric and non-parametric machine learning models using statistical analysis for RT-IoT2022 dataset*.  
*Journal of Scientific & Industrial Research*, 83(8):864–872, 2024. DOI: [10.56042/jsir.v83i8.7437](https://doi.org/10.56042/jsir.v83i8.7437)

---
