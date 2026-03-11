# 🔍 Steel Surface Defect Classification using Deep Learning

---

## 📖 Overview
This project presents a Deep Learning based system designed to automatically identify defects present on steel surface images.  
The goal is to support industrial quality inspection by reducing manual effort and increasing detection reliability using AI.

The system applies transfer learning with multiple pretrained convolutional neural network models and evaluates their performance on steel defect datasets.

---

## 🎯 Project Goals
- Build an automated defect classification pipeline  
- Use pretrained deep learning architectures for better accuracy  
- Compare multiple models to identify best performing architecture  
- Improve manufacturing inspection efficiency using AI  

---

## 🗂 Dataset Information
The project uses the **NEU Metal Surface Defect Dataset**, which contains labeled images of different types of steel defects including:

- Surface cracks  
- Inclusions  
- Scratches  
- Patches  
- Rolled scale defects  
- Pitted defects  

The dataset is loaded and extracted dynamically during execution.

---

## 🧠 Deep Learning Models Used

### 🔹 Baseline CNN Model
A custom convolutional neural network built using Keras Sequential API to establish baseline performance.

---

### 🔹 VGG16 Transfer Learning Model
- Pretrained ImageNet weights  
- Custom classification layers added  
- Selective layer fine-tuning applied  

---

### 🔹 ResNet50 Transfer Learning Model
- Residual learning architecture  
- Multi-stage fine-tuning strategy  
- Progressive training optimization  

---

## ⚙️ Techniques Implemented
- Transfer Learning  
- Model Fine Tuning  
- Data Augmentation  
- Mixed Precision Training for GPU acceleration  
- Learning Rate Scheduling  

---

## 📊 Performance Evaluation
Model performance is evaluated using:

- Accuracy Score  
- Precision & Recall  
- F1 Score  
- Confusion Matrix Visualization  
- Model Comparison Graphs  

---

## 🧪 Technology Stack
- Python  
- TensorFlow & Keras  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook  

---

## 📁 Repository Structure
```
Steel-Surface-Defect-Classification/
│
├── steel surface defect classification.ipynb
└── README.md
```

---

## ▶️ Execution Steps

### Step 1 — Install Dependencies
```
pip install tensorflow numpy pandas matplotlib scikit-learn
```

---

### Step 2 — Run Notebook
Launch Jupyter Notebook and execute:
```
steel surface defect classification.ipynb
```

---

### Step 3 — Dataset Upload
Upload dataset ZIP file when prompted during execution.

---

## 🏭 Industrial Applications
- Automated steel quality inspection  
- Smart manufacturing systems  
- AI-based industrial monitoring  
- Defect detection automation pipelines  

---

## 🔮 Future Scope
- Real-time inspection system  
- Integration with industrial hardware cameras  
- Cloud-based defect monitoring dashboard  
- Edge device deployment  

---
