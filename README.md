# 🌪️ Disaster Image Classification using CNN & EfficientNetB0  

## 📌 Overview  
This project focuses on **classifying disaster images** (Flood, Fire, Earthquake, Cyclone, etc.) using **Deep Learning**.  
We start with a **Simple CNN model** and later enhance performance using **EfficientNetB0 (transfer learning)**.  

---

## 📂 Dataset  
- **Source:** [Kaggle – Disaster Images Dataset](https://www.kaggle.com/datasets/varpit94/disaster-images-dataset)  
- **Size:** ~13,573 images across multiple disaster categories.  
- **Preprocessing:**  
  - Images resized to **224×224**.  
  - Normalization applied.  
  - Data split: **80% Training, 20% Validation**.  

---

## 🧠 Models Implemented  

### 1️⃣ Simple CNN  
- 3 Convolutional Layers + Pooling  
- Dense layers with ReLU activation  
- Softmax output layer  
- **Validation Accuracy:** ~73%  

### 2️⃣ EfficientNetB0 (Transfer Learning)  
- Pretrained on ImageNet  
- Fine-tuned last 20 layers  
- Added Dense + Dropout layers  
- **Validation Accuracy:** ~85–90%  

---

## 📊 Results  
- **Simple CNN:** 73% validation accuracy  
- **EfficientNetB0:** 85–90% validation accuracy  
- EfficientNetB0 shows **better generalization & less overfitting**  

📸 Example Predictions:  
- Input Image → Predicted Disaster Category  
- Model correctly classifies test images like **Flood, Fire, Earthquake, Cyclone**  

---

## 📈 Training Curves  

- **Simple CNN:** Moderate accuracy, slight overfitting  
- **EfficientNetB0:** Higher accuracy, smoother convergence  

---

## 🚀 How to Run  

### In Google Colab  
1. Upload dataset to Google Drive  
2. Mount Drive in Colab  
3. Run the provided notebook  

```bash
# Clone repo
!git clone https://github.com/<your-username>/disaster-classification.git
cd disaster-classification
