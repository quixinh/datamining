# Đề tài: Phân tích, Khám phá và Phân loại Tấn công của Bộ Dữ liệu RT-IoT2022

- **Sinh viên thực hiện**: Tạ Hồng Quí (MSSV: 3122410348)  
- **Giảng viên hướng dẫn**: ThS. Nguyễn Thanh Phước

## Hướng Dẫn Cài Đặt
Để dễ dàng đọc file, Thầy truy cập link github: https://github.com/quixinh/datamining.git là trực quan nhất. 

Hướng dẫn thiết lập môi trường dự án, bao gồm Python, scikit-learn, TensorFlow, PyTorch và các thư viện phụ thuộc khác.

### Yêu cầu
- **Python**: Phiên bản 3.10

### Các bước cài đặt

1. **Tạo và kích hoạt môi trường ảo**:
  ```bash
  python -m venv venv
  source venv/bin/activate  # Trên macOS/Linux
  venv\Scripts\activate     # Trên Windows
  ```
2. **Tải mã nguồn dự án**:
  ```bash
  git clone https://github.com/quixinh/datamining.git
  cd datamining
  ```
3. **Cài đặt các thư viện cần thiết**:
  ```bash
    pip install -r requirements.txt
  ```
Nếu sử file được clone từ github thì file có tên `datamining` thay vì `3122410348_TaHongQui` như yêu cầu. Sau đó tiếp tục bước 3.
## Cấu trúc Thư mục `datamining` or `3122410348_TaHongQui`.  

- **data/**: Chứa dữ liệu huấn luyện cho mô hình. Link dataset: [https://archive.ics.uci.edu/dataset/942/rt-iot2022]
- **DOC/**: Lưu trữ bài báo cáo của đề tài.  
- **Document/**: Tài liệu tham khảo về cách thu thập dữ liệu RT-IoT2022.  
- **EDA/**: Chứa file `EDA.ipynb` dùng để khám phá và phân tích dữ liệu ban đầu.  
- **images/**: Lưu trữ các hình ảnh phân tích từ thư mục EDA và các hình ảnh khác.  
- **model**: Vị trí lưu các mô hình tốt nhất đã huấn luyện.  
- **result_confusion_matrix/**: Lưu kết quả phân loại (ma trận nhầm lẫn), giúp trực quan hóa quá trình phân tích và nhận diện sự thay đổi trong huấn luyện.  
- **DataProcessing.py**: Chứa các hàm xử lý dữ liệu.  
- **Preprocessing.py**: Chứa các hàm tiền xử lý dữ liệu. 
- **model.py**: vị trí xây dựng hàm huấn luyện mô hình (def).  
- **main.ipynb**: Thực nghiệm các mô hình.   
- **requirements.txt**: Danh sách thư viện cần cài đặt trước khi thực thi chương trình (cài bằng `pip install -r requirements.txt`).  
- **utils**: Chứa các hàm hỗ trợ như vẽ biểu đồ, lưu mô hình, và các tiện ích khác.  

## Tài liệu Tham khảo

[1] B. S. và Rohini Nagapadma. *RT-IoT2022*. UCI Machine Learning Repository, 2023. DOI: [https://doi.org/10.24432/C5P338](https://doi.org/10.24432/C5P338).  

[2] Sharmila B. S., Jayashree H. R., Pradeep R., và Vijayalakshmi R. *Performance evaluation of parametric and non-parametric machine learning models using statistical analysis for RT-IoT2022 dataset*. Journal of Scientific & Industrial Research, 83(8):864–872, 2024. DOI: [10.56042/jsir.v83i8.7437](https://doi.org/10.56042/jsir.v83i8.7437).