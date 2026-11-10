# Bài tập nhóm 7 
## Phân Tích Mối Quan Hệ Giữa Các Chỉ Tiêu Hóa Lý Và Chất Lượng Cảm Quan Của Rượu Vang Đỏ (Red Wine Quality)
Dự án nghiên cứu và phân tích dữ liệu toàn diện về tập dữ liệu **Red Wine Quality** (Cortez et al., 2009), nhằm đánh giá mối quan hệ thống kê giữa các chỉ tiêu hóa lý với điểm số chất lượng cảm quan của rượu vang đỏ, đồng thời đề xuất giải pháp kiểm soát chất lượng mẻ ủ và kiến trúc học máy ứng dụng trong sản xuất.
- **Nguồn dữ liệu:** URL: https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009
- **Xuất xứ:** Công trình nghiên cứu của *P. Cortez, A. Cerdeira, F. Almeida, T. Matos và J. Reis (2009)* phối hợp giữa Đại học Minho và Ủy ban Giám sát Rượu vang vùng Vinho Verde (CVRVV), miền bắc Bồ Đào Nha.
- **Quy mô dữ liệu gốc:** 1,599 quan sát, 12 thuộc tính (11 biến hóa lý đầu vào và 1 biến chất lượng cảm quan).
- **Bản chất biến mục tiêu (`quality`):** Thang đo thứ bậc (ordinal scale từ 3 đến 8), được xác định bằng **trung vị (median)** của ít nhất 3 lần đánh giá cảm quan nếm thử độc lập bởi hội đồng chuyên gia (blind taste test).
## Quy Trình Phân Tích (4 Giai Đoạn)
### Giai đoạn 1: Thu thập và Đánh giá Dữ liệu Ban đầu

### Giai đoạn 2: Tiền xử lý & Làm sạch Dữ liệu

### Giai đoạn 3: Phân tích Thống kê & Trực quan hóa Chuyên sâu

### Giai đoạn 4: Đánh giá Tác động & Khuyến nghị Ứng dụng
## 💻 Yêu Cầu Môi Trường & Cài Đặt
Dự án yêu cầu **Python 3.9+** (khuyến nghị Python 3.10 – 3.13) cùng các thư viện sau:
```bash
pip install numpy pandas matplotlib seaborn scipy pingouin statsmodels scikit-learn nbformat nbconvert
```
## Tài Liệu Tham Khảo
Cortez, P., Cerdeira, A., Almeida, F., Matos, T., & Reis, J. (2009). Modeling wine preferences by data mining from physicochemical properties. Decision Support Systems, 47(4), 547–553. https://doi.org/10.1016/j.dss.2009.05.016
UCI Machine Learning Repository. (2009). Wine Quality. https://doi.org/10.24432/C56S3T
