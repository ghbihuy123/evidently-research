Yêu cầu input đầu vào:
https://docs.evidentlyai.com/user-guide/input-data/column-mapping

Phiên bản Evidently: 0.4.39
https://urldefense.proofpoint.com/v2/url?u=https-3A__u9158452.ct.sendgrid.net_ls_click-3Fupn-3Du001.-2D2FiEhS1OQuB1Fjeox00F-2D2B9kWRsLHuQ-2D2BzAKyUjgnOnrheF-2D2BzLnFxdBmxBTMttvTXpHL0UnVqyrFtcx537LBPQsPB-2D2FWeuTqqtdrueUbbVCRxL8-2D3DhIeN-5FXr6aRcJtmkRKqpnkYZRskROYC15V-2D2F20rpkjGOlt2zJShWXb6NWobFCLTh-2D2BwznJoq-2D2FpeZOhQ239UTwFz-2D2BxF0R98na3mS0af6EWYnvowQBlKbvok5ku3sM9EmFIx0-2D2BI2Nh3w2tp-2D2F4lHJU7EBVcOgg1h9rJ9hgG0LhublKWRQttaUNd-2D2FrfVh4bippjo2BwO9B-2D2F61r4xqHv1ilptQu0IzTpVKg-2D3D-2D3D&d=DwMFaQ&c=joq6fOIUB-9ucnQulzuv2hATl_5_BkeEIagHfFhNlQ8&r=MU3Q9M6gonE1kPqq9ca45muNkRRSNP4sEAslq7EacXE&m=RSn08VbeunPqtbmBRQS9obl2-ZNp6v9tsU_V5LtHSNXQJKxgzeEpzVRHuDn44WYY&s=ZqImCYf5HD8VVb0TopfEedpgiDXSGtenlrb4qXQY1HY&e=

Data Quality, Data Drift đã custom lại theo template metrics của DucLH21 đề xuất
- Đã tính toán được các metrics đã define, xuất ra file JSON

Phát triển thêm phần UI của dashboard, có thể làm 2 hướng
- Phát triển Dashboard HTML giống như của Evidently, bằng cách viết lại hàm render html
- Sử dụng BI tools ở bên ngoài, sử dụng file JSON xuất ra làm Input


Presquite:
- Phải truyền giá trị cho reference data và current data
- Phải define column map

1. Data Quality
Yêu cầu Input:
- Data đầu vào là DataFrame
- Cần define list categorical features và numerical feature
- Phải có current data (reference data là optional)


2. Data Drift
Yêu cầu Input: 
- Data đầu vào là DataFrame
- Cần define list categorical features và numerical feature
- Phải có cả current và reference data

3. Model Quality
- Phải có current data (reference data là optional)
- Data đầu vào là DataFrame
- Cần có ground truth (true label) và kết quả dự đoán\

a. Regression (done)
b. Binary Classification
c. Multiclass Classification 
d. Forecasting
e. Ranking
f. Recommendation


3. Model Drift
(Đang phát triển)

4. Model Explain
(Đang phát triển)
