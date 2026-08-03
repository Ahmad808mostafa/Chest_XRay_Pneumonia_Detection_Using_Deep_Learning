# 🩺 Chest X-Ray Pneumonia Detection Using Deep Learning and Transfer Learning

An end-to-end Deep Learning project for automated Pneumonia Detection from chest X-ray images using PyTorch, ResNet50, Transfer Learning, and Fine-Tuning. This project demonstrates a complete medical image classification pipeline, from data exploration and preprocessing to model training, evaluation, and comparison.

---

# 📌 Project Overview

Pneumonia is one of the leading causes of respiratory illness worldwide. Early and accurate diagnosis is essential for effective treatment. In this project, a Deep Learning model was developed to classify chest X-ray images into two categories:

- Normal
- Pneumonia

The project follows a professional Deep Learning workflow, including dataset exploration, preprocessing, image augmentation, transfer learning, fine-tuning, model evaluation, and performance comparison between multiple experiments.

---

# 📂 Dataset

Dataset: Chest X-Ray Images (Pneumonia)

- Total Images: 5,856
- Number of Classes: 2
- Classes:
  - Normal
  - Pneumonia

## 📥 Dataset Source

Kaggle Dataset

https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

### Dataset Structure
Plain text

chest_xray/
│
├── train/
│
├── val/
│
└── test/
---

# 🚀 Project Workflow

- Import Required Libraries
- Dataset Loading
- Dataset Structure Verification
- Dataset Information
- Metadata Creation
- Exploratory Data Analysis (EDA)
- Missing Values Analysis
- Duplicate Data Check
- Class Distribution Analysis
- Dataset Split Analysis
- Image Visualization
- Image Dimension Analysis
- Pixel Intensity Analysis
- Image Preprocessing
- Data Augmentation
- PyTorch Dataset Creation
- DataLoader Preparation
- Class Weight Computation
- Transfer Learning with ResNet50
- Fine-Tuning
- Model Training
- Performance Evaluation
- Confusion Matrix
- ROC Curve
- Experimental Comparison
- Best Model Selection
- Model Saving

---

# 🧠 Model Architecture

- ResNet50 (Pretrained on ImageNet)
- Transfer Learning
- Fine-Tuning (Last Residual Block)
- CrossEntropy Loss
- AdamW Optimizer
- ReduceLROnPlateau Scheduler
- Early Stopping
- Dropout Regularization

---

# 📊 Experimental Results

| Model | Accuracy | Precision | Recall | F1 Score |
|-------|---------:|----------:|--------:|---------:|
| Baseline ResNet50 | 85.10% | 90.09% | 86.92% | 88.48% |
| Fine-Tuned ResNet50 | 91.51% | 90.80% | 96.15% | 93.40% |

The fine-tuned ResNet50 significantly improved the overall performance, demonstrating the effectiveness of transfer learning and fine-tuning for medical image classification tasks.

---

# 📈 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Classification Report
- Confusion Matrix
- ROC Curve
- Area Under Curve (AUC)

---

# 🛠 Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Pillow (PIL)
- OpenCV
- KaggleHub

---

# ⭐ Key Features

- End-to-End Deep Learning Pipeline
- Medical Image Classification
- Binary Classification
- Transfer Learning
- Fine-Tuning
- Data Augmentation
- Experiment Comparison
- Professional Model Evaluation
- Model Saving
- Ready for Deployment

---

# 🔮 Future Improvements

- Compare with EfficientNet-B3
- Compare with DenseNet121
- Implement Grad-CAM Visualization
- Hyperparameter Optimization
- Test-Time Augmentation (TTA)
- K-Fold Cross Validation
- Deploy Using Streamlit
- Deploy Using Flask

---

# 👨‍💻 Author

Ahmed Mostafa

LinkedIn
https://www.linkedin.com/in/ahmed-mostafa-47a961423

GitHub
https://github.com/Ahmad808mostafa

Kaggle
https://www.kaggle.com/a7mad9

---

# 🏷 GitHub Topics

deep-learning 
machine-learning
pytorch 
computer-vision 
medical-imaging 
chest-xray 
pneumonia-detection 
transfer-learning
resnet50 
binary-classification
healthcare-ai 
image-classification

---
