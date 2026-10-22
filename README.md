# Thực Hành DS201 - Học Sâu & Ứng Dụng (Deep Learning & Applications)

Repository lưu trữ các bài thực hành môn **DS201**.

---

## 📂 Danh mục bài tập

### [Buổi 2: Convolutional Neural Networks (CNN)](./Buoi%202)
- **ThucHanh2.1.ipynb**: Bài 1 — Huấn luyện mạng **LeNet-5** trên tập dữ liệu **MNIST**.
- **ThucHanh2_Bai2_3_4.ipynb**: Gộp các bài thực hành huấn luyện trên tập dữ liệu **VinaFood21** (21 lớp món ăn Việt Nam):
  - **Bài 2**: Mô hình **GoogLeNet** (Inception-v1).
  - **Bài 3**: Mô hình **ResNet-18**.
  - **Bài 4**: Mô hình **ResNet-50 Pretrained** từ Hugging Face.

#### 📊 Bảng tổng hợp kết quả đánh giá (Buổi 2 - VinaFood21 Test Set)

| Mô hình | Accuracy | Precision (macro) | Recall (macro) | F1-score (macro) |
| :--- | :---: | :---: | :---: | :---: |
| **GoogLeNet** | 0.2695 | 0.3029 | 0.2695 | 0.2512 |
| **ResNet-18** | 0.3152 | 0.3037 | 0.3152 | 0.2885 |
| **ResNet-50 (Pretrained)** | **0.5552** | **0.5944** | **0.5552** | **0.5345** |
