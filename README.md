# Face Recognition using PCA and Eigenfaces

## 📌 Project Overview
This project implements a **Face Recognition System using Principal Component Analysis (PCA) and Eigenfaces**. It uses the **Olivetti Faces dataset** to reduce image dimensions and recognize faces using K-Nearest Neighbors (KNN).

## 🛠️ Technologies
- Python
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook / Google Colab

## 📊 Dataset
- 400 face images
- 40 people
- Image size: 64 × 64 pixels
- 4096 features per image

## ⚙️ Setup

Clone the repository:

```bash
git clone <https://github.com/akshaykumarb345-beep/Face-Recognition-PCA-Eigenfaces>
cd Face-Recognition-PCA-Eigenfaces
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Or:

```bash
pip install numpy matplotlib scikit-learn jupyter
```

## ▶️ Run the Project

### Google Colab
1. Open the `.ipynb` file in Google Colab.
2. Select **Runtime → Run all**.

### Local
Run:

```bash
jupyter notebook
```

Open the notebook and run all cells.

## 🔬 Methodology

```text
Load Dataset
     ↓
Flatten Images
     ↓
Train/Test Split
     ↓
Mean Face & Centering
     ↓
PCA
     ↓
Eigenfaces
     ↓
Face Reconstruction
     ↓
KNN Face Recognition
     ↓
Accuracy & Confusion Matrix
```

## 📈 Results

The project evaluates performance using:
- Recognition Accuracy
- Classification Report
- Confusion Matrix
- Reconstruction RMSE

## 👥 Team Members
1. Naveenkumar - PES1UG25AM502
2. Akshaya Kumar B – PES1UG25AM467
3. Yashwanth Naik- PES1UG25AM456
4. Kushal K M - PES1UG26AM810

## 🎓 Purpose

This project demonstrates the application of **linear algebra, PCA, eigenvalues, eigenvectors, and machine learning** to a real-world face recognition problem.
