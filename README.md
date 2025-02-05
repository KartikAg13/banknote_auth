# Decision Tree from Scratch

This project implements a **Decision Tree Classifier from scratch** using only **NumPy, Pandas, and Matplotlib**, without using Scikit-Learn. The dataset used is the **Banknote Authentication Dataset** from [Kaggle](https://www.kaggle.com/datasets/ritesaluja/bank-note-authentication-uci-data).

## 📌 Features
- **Pure NumPy Implementation** (No Scikit-Learn)
- **Custom Gini Impurity Calculation**
- **Manual Data Shuffling & Splitting**
- **Recursively Built Decision Tree**
- **Performance Evaluation (Accuracy Calculation)**

## 📂 Dataset
The dataset contains 4 numerical features extracted from banknotes:
- **Variance of Wavelet Transformed Image**
- **Skewness of Wavelet Transformed Image**
- **Curtosis of Wavelet Transformed Image**
- **Entropy of Image**

The target column:
- **Class (0: Fake Note, 1: Authentic Note)**

## 🔧 Installation
Clone this repository and install dependencies:
```bash
git clone https://github.com/your-username/decision-tree-from-scratch.git
cd decision-tree-from-scratch
pip install pandas numpy matplotlib
```

## 🚀 Usage
Run the Jupyter Notebook to execute the decision tree implementation.
```bash
jupyter notebook Decision_Tree_From_Scratch.ipynb
```

## 🏗️ Project Structure
```
├── Decision_Tree_From_Scratch.ipynb  # Jupyter Notebook with implementation
├── README.md                          # Project Documentation
├── BankNote_Authentication.csv        # Dataset (Needs to be downloaded)
```

## 📊 Results
- **Accuracy:** ~85-90% on test data
- **Max Depth:** Configurable (default: 3)
- **Visualization:** Scatter plot of feature distribution

## ✨ Next Steps
- Implement **pruning** to prevent overfitting.
- Support **entropy** as an alternative impurity measure.
- Convert the code into a **class-based implementation**.

---
👨‍💻 **Developed by:** [Kartik Agrawal](https://github.com/KartikAg13)