# Chuẩn đoán SARS-CoV-2 (COVID-19)

### Dataset

Dataset chứa 1252 ảnh chụp CT dương tính với SARS-CoV-2 (COVID-19) và 1229 ảnh chụp CT cho bệnh nhân không bị nhiễm SARS-CoV-2, tổng cộng gồm 2481 ảnh

> Nguồn: [SARS-COV-2 Ct-Scan Dataset](https://www.kaggle.com/plameneduardo/sarscov2-ctscan-dataset).

### Cách triển khai
1. Chia dataset thành 3 bộ: 
    - `train`: chiếm 80% dataset
    - `validate`: sẽ được trích ra từ tập train
    - `test`: chiếm 20% dataset

2. Bài toán sẽ được giải quyết theo 2 hướng: học máy và học sâu

### Cách đánh giá
- Accuracy score
- Confusion matrix
- Precision, Recall và F1-score
- ROC Curve
