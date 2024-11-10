# Overview
Repo này được sử dụng với mục đích nghiên cứu, tạo preset riêng cho dashboard và các metrics đã defined của team MLOps

# Danh sách thuật ngữ
- **Tên**: Tên của thuật ngữ
- **Ý nghĩa**: Indicates whether it’s a class or function.

Reference dataset: ám chỉ data được sử dụng để so sánh với input của model, ở đây ta có thể hiểu là production data
|Tên  |Ý nghĩa|
|:---|:---|
|Reference dataset  |Ám chỉ data được sử dụng để so sánh với input của model, ở đây ta có thể hiểu là production data|

# Mục tiêu
Phát triển preset riêng cho các metrics đã define sẵn của team MLOps

1. Data Quality
Requirements: Model input
- Đề xuất sử dụng preset đã có sẵn


2. Model Explainer
Requirements: Model input, a reference dataset

3. Target drift
Requirements: model predictions and/or target, a reference dataset.


4. Data Drift
Requirements: model inputs, a reference dataset.

5. Model Drift
Requirements: model predictions and true labels.
