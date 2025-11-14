# Image-Classification-ViT-VGG16-ResNet50
Lab4 - CS406 UIT

This project trains and compares three image classification models:

- **Vision Transformer (ViT)**
- **VGG16**
- **ResNet50**

After training, a **Streamlit** app is provided to:

- Upload an image
- Run inference on all three models
- Compare **predicted class, confidence, and inference time**
- Visualize **confidence** and **inference time** with bar charts

---

## 1. Environment Setup

You will need two nhóm thư viện:

- **Training dependencies** – để train ViT/VGG16/ResNet50 (thường chạy trong notebook, ví dụ Kaggle).
- **App dependencies** – để chạy Streamlit UI cho inference.

### 1.1. Training dependencies

Các lệnh kiểu notebook (Kaggle / Jupyter):

```bash
!pip install -q transformers datasets kaggle
!pip install -q accelerate
