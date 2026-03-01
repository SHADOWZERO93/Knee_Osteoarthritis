# 🦴 Knee Image Classification using Deep Learning

## 📌 Project Overview

This project is a **Deep Learning–based image classification system** that predicts the class of knee medical images.
It uses **Transfer Learning with a Convolutional Neural Network (CNN)** to analyze images and classify them into multiple categories.

The goal of this project is to demonstrate how AI can assist in **medical image analysis** by automatically identifying patterns in knee scans.

---

## 🚀 Features

* Image preprocessing pipeline
* Transfer learning model
* Training + validation tracking
* Confusion matrix & classification report
* Prediction function for new images
* Modular notebook workflow

---

## 🧠 Model Architecture

* Base Model: Pretrained CNN (Transfer Learning)
* Trainable Parameters: **164,613**
* Non-Trainable Parameters: **2,257,984**
* Total Parameters: **2,422,597**

The pretrained layers extract visual features while custom layers learn dataset-specific patterns.

---

## 📊 Training Results

* Final Training Accuracy: **55.78%**
* Final Validation Accuracy: **51.04%**

The model shows moderate performance and can be improved with:

* Data augmentation
* Hyperparameter tuning
* Larger dataset

---

## 📂 Dataset Structure

```
dataset/
 ├── 0/
 ├── 1/
 ├── 2/
 ├── 3/
 └── 4/
```

Each folder represents a class label.

---

## ⚙️ Installation

```bash
git clone https://github.com/yourusername/knee-classification.git
cd knee-classification
pip install -r requirements.txt
```

---

## ▶️ Usage

### Train Model

Run training notebook:

```
training.ipynb
```

### Predict Image

```python
prediction = model.predict(image)
```

Output example:

```
[[0.02 0.05 0.71 0.18 0.04]]
```

This means:

* Model confidence for each class
* Highest value = predicted class

---

## 📈 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

---

## 🧪 Future Improvements

* Add Grad-CAM visualization
* Deploy as web app
* Optimize model architecture
* Increase dataset size

---

## 📜 License

This project is for **educational and research purposes only**.

---

## 👤 Author

**Soumyadeep Pal**
Game Designer | AI Enthusiast | Developer

---

⭐ *If you found this project useful, consider starring the repository!*
