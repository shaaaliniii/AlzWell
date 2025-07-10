# 🧠 YARN: Alzheimer's Disease Detection System

AlzWell is a machine learning-based diagnostic tool for the early detection of Alzheimer's disease using MRI scans. The project leverages deep learning techniques to analyze brain imaging data and predict the likelihood of Alzheimer's, aiming to assist doctors and researchers with accurate, non-invasive analysis.

---

## 🚀 Features

- 🧠 Predicts Alzheimer’s stage using brain MRI data
- 📊 Uses preprocessed medical image datasets
- 🧠 Implements CNN (Convolutional Neural Networks)
- 🧪 Displays model evaluation metrics: accuracy, loss, etc.
- 📁 Streamlined through a simple Python-based interface

---

## 🛠️ Tech Stack

- **Python 3**
- **TensorFlow / Keras**
- **NumPy, Pandas, Matplotlib**
- **OpenCV (for image preprocessing)**
- **Jupyter Notebook / Streamlit** (optional frontend)
- **Scikit-learn** (for evaluation)

---

## 📂 Dataset

- Source: [Kaggle](https://www.kaggle.com/datasets/jboysen/mri-and-alzheimers) / [Open Access Series of Imaging Studies (OASIS)](https://www.oasis-brains.org/)
- Contains labeled MRI images categorized as:
  - **Non-Demented**
  - **Mild Demented**
  - **Moderate Demented**
  - **Very Mild Demented**

---

## 📊 Model Overview

- CNN-based architecture trained on preprocessed MRI slices
- Image resizing, grayscale conversion, and normalization applied
- Uses data augmentation to improve model generalization
- Evaluated using accuracy, precision, recall, and F1-score

---

## 📚 Research References
OASIS-3: MRI Dataset used

Related IEEE Papers on early Alzheimer's detection via ML

## 🧪 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/shaaaliniii/AlzWell.git
   cd AlzWell
    ```
2. Install dependencies:
    ```bash
   pip install -r requirements.txt
    ```
3. Train the model:
    ```bash
   python train.py
    ```
4. Evaluate / test predictions:
    ```bash
   python evaluate.py
    ```
    
## Results
![unnamed (7)](https://github.com/user-attachments/assets/79060d55-00aa-4410-bf60-83863356c06f)
<img width="512" height="247" alt="unnamed" src="https://github.com/user-attachments/assets/7668b4b2-6a97-4d22-b252-a7884db75c53" />
<img width="512" height="268" alt="unnamed (1)" src="https://github.com/user-attachments/assets/ea060dd2-892e-44e0-8003-597962dfa14e" />
<img width="512" height="218" alt="unnamed (4)" src="https://github.com/user-attachments/assets/365f9d01-2496-4c6d-b290-8111934c0486" />
![unnamed (2)](https://github.com/user-attachments/assets/9c83ddc0-3ea5-4625-b0ea-67355d5bfb85)
![unnamed (3)](https://github.com/user-attachments/assets/0dbde0b1-68ae-47a0-afab-381c1916eaa3)
![unnamed (4)](https://github.com/user-attachments/assets/ff600c81-0567-4fda-94c2-ec7e1c4ae579)
![unnamed (5)](https://github.com/user-attachments/assets/f5746937-c5f8-40b6-9200-4fd6bfe16434)
![unnamed (6)](https://github.com/user-attachments/assets/f0c6130c-58ab-4479-ad31-8a990ed26a87)
<img width="379" height="512" alt="unnamed (2)" src="https://github.com/user-attachments/assets/0839c4a4-bbd4-4b2e-98b6-e6b73f0d7ca9" />


## 🙋‍♀️ Author
Shalini Singh
📍 IIIT Naya Raipur | 💻 CSE | 🧠 ML Enthusiast
GitHub: shaaaliniii





   
   
