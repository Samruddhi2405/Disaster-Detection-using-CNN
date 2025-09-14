🌍 Disaster Detection and Classification using CNN

📌 Project Overview:

This project demonstrates the use of Convolutional Neural Networks (CNNs) to automatically detect and classify disaster images (e.g., Flood, Fire, Earthquake).
It shows how Deep Learning can assist in Disaster Management by quickly identifying the type of disaster from images.

📂 Dataset:

Dataset: Disaster Images Dataset (Kaggle)
Total Images: ~13,573
Categories:
1) 🌊 Flood
2) 🔥 Fire
3) 🌎 Earthquake

⚙️ Methodology:

1) Collect Dataset → Disaster images from Kaggle.

2) Preprocessing → Resize (128×128), normalize pixel values.

3) Model Training → A CNN model with multiple Conv2D and MaxPooling layers.

4) Evaluation → Validate on unseen images and generate accuracy/loss plots.

🧠 Model Architecture

1) Conv2D → MaxPooling (×3)

2) Flatten Layer

3) Dense Layer (128 neurons + ReLU)

4) Dropout (to avoid overfitting)

5) Output Layer (Softmax for 3 classes)

📊 Results

1) Training Epochs: 5

2) Validation Accuracy: ~73%

3) Model successfully classifies disaster images into 3 categories.

<img width="1148" height="793" alt="predictions1" src="https://github.com/user-attachments/assets/c7b655fe-6e4f-4e9c-aa31-d577b26fc905" />


