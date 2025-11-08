# 🧬 Skin Cancer Classification with Explainable AI (Grad-CAM)

This project focuses on detecting skin cancer using deep learning and Explainable AI.
Two pretrained CNN models — **MobileNetV1** and **InceptionV3** — were trained on skin lesion images to classify cancer vs non-cancer cases.
To make the model’s predictions interpretable, **Grad-CAM** was applied to visualize which regions contributed most to the classification.

---

## ✅ Features

* ✅ Skin cancer classification using **MobileNetV1** and **InceptionV3**
* ✅ Performance comparison between models
* ✅ **Grad-CAM** heatmaps for Explainable AI
* ✅ High accuracy and interpretable predictions
* ✅ Useful for research, medical assistance, and AI transparency

---

## 🛠 Tech Stack

* Python
* TensorFlow / Keras
* OpenCV
* Matplotlib
* NumPy & Pandas

---

## 📁 Project Workflow

1. Dataset preprocessing (resizing, normalization, augmentation)
2. Training MobileNetV1 and InceptionV3
3. Model evaluation using accuracy, F1-score, and confusion matrix
4. Applying **Grad-CAM** to generate visual explanations
5. Displaying heatmaps over original images

---

## 📊 Results

* Both models successfully classified skin lesion images
* Grad-CAM visualizations highlight critical regions used in prediction
* Helps improve trust and transparency in medical decision-making

---

## 📌 Explainable AI (Grad-CAM)

Grad-CAM generates a heatmap that shows **where the model is looking**, making the prediction more transparent for doctors and researchers.

Example output:

* ✅ Original image
* ✅ Heatmap
* ✅ Overlay showing important areas

---

## 🔧 How to Run

```bash
pip install tensorflow opencv-python numpy matplotlib
python train.py
python gradcam_visualize.py
```

---

## 📌 Applications

* Medical diagnosis support
* Research in medical image analysis
* Explainable AI demonstrations
* Model interpretability in healthcare

---

