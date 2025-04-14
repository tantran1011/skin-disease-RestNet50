# 🧴 Skin Disease Classification using ResNet50

![resnet50](https://img.shields.io/badge/model-ResNet50-blue)  
![accuracy](https://img.shields.io/badge/accuracy-97%25-green)  
![status](https://img.shields.io/badge/kaggle-bronze%20medal-orange)

## 📌 Project Overview

This project tackles the problem of **skin disease classification** using deep learning. We utilize a **pretrained ResNet50** model and fine-tune it on a curated dataset of skin images to predict various types of skin diseases.

Achieved a validation accuracy of **97%**, with the notebook receiving **26 upvotes** on Kaggle and earning a 🥉 **Bronze Medal**.

> 📍 Kaggle notebook: [View here](https://www.kaggle.com/code/tantranduc/skin-disease-resnet50-acc-97)  
> 📍 Dataset used: [Link to dataset](https://www.kaggle.com/datasets/subirbiswas19/skin-disease-dataset)

---

## 🚀 Tech Stack

- Python
- TensorFlow / Keras
- ResNet50 (transfer learning)
- NumPy, Pandas, Matplotlib
- Scikit-learn

---

## 🧠 Model Approach

1. **Data Preprocessing**:
   - Resized all images to `224x224`
   - Applied data augmentation: rotation, zoom, flips
   - Normalized pixel values

2. **Model**:
   - Used `ResNet50` pretrained on ImageNet
   - Removed top layer and added custom classification head
   - Trained with early stopping and model checkpointing

3. **Evaluation**:
   - Accuracy: **97%**
   - Confusion matrix, precision/recall for each class

---

## 📊 Results

| Metric        | Value     |
|---------------|-----------|
| Accuracy      | 97%       |
| Kaggle Votes  | 26 👍      |
| Medal         | 🥉 Bronze |

---

## 🧰 How to Run

```bash
git clone https://github.com/tantran1011/skin-disease-resnet50.git
cd skin-disease-resnet50

# Open the notebook
jupyter notebook skin-disease-resnet50-acc-97.ipynb
