# Neural Network Model for Predicting Students Final Exam Grades

This project focuses on **Developing a custom Neural Network model for predicting final exam grades** of students from the **Department of Computing**, Faculty of Applied Sciences, **Rajarata University of Sri Lanka**. The model is trained using supervised learning techniques. 

---

## 📌 Project Goal
The main goal of this project is to:
- Build and evaluate a **neural network model** to predict students’ final exam results.
- Help identify students who may need additional support before final exams.
- Provide useful insights for educators and institutions to improve learning outcomes.

---

## 📊 Dataset
- The dataset contains student information along with their final exam results.
- Features include:
  - Weekly study hours per subject
  - Course credits
  - Attendance rate
  - Assignment Marks
- **Target variable:** Final exam grade (A, B, C, D, or E)
- **Scope:** Dataset is collected from students of the **Department of Computing, Faculty of Applied Sciences, Rajarata University of Sri Lanka.**


---

## ⚙️ Machine Learning Task
- **Problem Type:** Multiclass Classification
- **Target Labels:** A, B, C, D, E
- **Objective:** Train a custom neural network to predict the correct final exam grade..

---

## 📦 Requirements

- Python
- Google Colab runtime
- TensorFlow/Keras 
- Matplotlib, Seaborn
- Pandas, scikit-learn

---

## ⚙️ Methodology
### Data Preprocessing:
  - Handling missing values
  - Balancing class distribution
  - Encoding categorical values
  - Train/test split 
  - Normalization

### Model Architecture
  - An input layer
  - Three hidden layers(activation: ReLU)
  - An output layer - represent five classes.(activation: Softmax)
  - Optimizer: Adam
  - Loss function: Categorical Cross-Entropy

### Evaluation Metrics
  - Accuracy
  - Precision, Recall, F1-Score
  - Confusion Matrix

---

## 📊 Results
  - Predict students final exam results within the Department of Computing.

---

## 👨‍💻 Developed by:
**Rakunathan Priyatharsan**  
Bachelor of Science in Information Technology
Rajarata University of Sri Lanka  

---


