#  Dog Breed Classification 

This project implements a **deep learning pipeline** to identify dog breeds from images using **TensorFlow** and **Transfer Learning**.  
The model is trained and evaluated on the **[Dog Breed Identification Dataset from Kaggle](https://www.kaggle.com/c/dog-breed-identification/data)**.

---

## 🚀 Project Overview

The project demonstrates:
- Image preprocessing and augmentation using `tf.data`
- Transfer Learning with **MobileNetV2**
- Training, validation, and testing workflows
- Model evaluation and visualization of accuracy/loss
- Predictions on unseen dog images

---

## 📂 Dataset
- **Source:** [Kaggle Dog Breed Identification](https://www.kaggle.com/c/dog-breed-identification/data)  
- **Total Images:** ~20,000 labeled images across 120 breeds  
- **Format:** JPEG images with a `labels.csv` file mapping each ID to a breed  

---

## 🧠 Model Architecture
- **Base Model:** MobileNetV2 (pretrained on ImageNet)
- **Input Size:** 224×224
- **Optimizer:** Adam
- **Loss Function:** Sparse Categorical Crossentropy
- **Metrics:** Accuracy

---

## 📊 Results
| Metric | Value |
|--------|--------|
| Training Accuracy | 92% |
| Validation Accuracy | 88% |
| Test Accuracy | 86% |

> Accuracy may vary slightly depending on hardware and training parameters.

---

## ⚙️ Tech Stack
- **Language:** Python  
- **Frameworks:** TensorFlow, Keras  
- **Libraries:** NumPy, Pandas, Matplotlib, Pillow, tqdm  
- **Environment:** Jupyter Notebook  

---

## 🧾 Project Structure
📁 dog-breed-classification/
│
├── end-to-end-dog-vision.ipynb # Main notebook for training and evaluation
├── requirements.txt # All dependencies
├── README.md # Project description
└── /dataset Placeholder for Kaggle dataset files
