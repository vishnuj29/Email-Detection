# 📧 Email Phishing Detection using Machine Learning

## 📌 Project Overview
Email phishing is one of the most common cyber-attacks used to steal sensitive information such as passwords, banking details, and personal data. This project focuses on building a **machine learning model that can detect phishing emails automatically**.

The model analyzes email content and identifies whether the email is **phishing or legitimate** using machine learning techniques.

This project was implemented using **Python in Jupyter Notebook on a Linux environment**, and the dataset was obtained from **Hugging Face datasets**.

---

## 🎯 Objectives
- Detect phishing emails using machine learning.
- Improve cybersecurity awareness and automated threat detection.
- Build a model capable of classifying emails as **phishing or safe**.
- Perform practical implementation in a **Linux-based environment**.

---

## 🗂 Dataset
The dataset used in this project was collected from **Hugging Face**.

### Dataset Characteristics
- Contains labeled email data.
- Emails categorized into:
  - **Phishing**
  - **Legitimate (Safe Emails)**
- Includes email text features used for training the model.

Dataset Source:  
Hugging Face Datasets

---

## 🛠 Technologies Used

### Programming Language
- Python

### Environment
- Linux (Ubuntu/Kali Linux)
- Jupyter Notebook

### Libraries
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Natural Language Processing (NLP)

---

## ⚙️ Project Workflow

### 1️⃣ Data Collection
- Download dataset from **Hugging Face**.
- Load dataset into **Jupyter Notebook**.

### 2️⃣ Data Preprocessing
- Cleaning email text
- Removing stopwords
- Tokenization
- Converting text into numerical format using **TF-IDF or CountVectorizer**

### 3️⃣ Feature Engineering
- Extract meaningful patterns from email text.
- Convert text into machine learning features.

### 4️⃣ Model Training
Machine learning models used:
- Logistic Regression
- Naive Bayes
- Support Vector Machine (SVM)

### 5️⃣ Model Evaluation
Model performance was evaluated using:
- Accuracy
- Precision
- Recall
- Confusion Matrix

### 6️⃣ Prediction
The trained model predicts whether a new email is:
- **Phishing Email**
- **Legitimate Email**

---



## 📊 Example Output

Input Email:


---

## 🖥 Linux Commands Used


# Update system
sudo apt update

# Install Python and pip
sudo apt install python3 python3-pip

# Install Jupyter Notebook
pip install notebook

# Install required libraries
pip install pandas numpy scikit-learn matplotlib seaborn

# Run Jupyter Notebook
jupyter notebook
---
##  Screenshot
![image alt](https://github.com/vishnuj29/Email-Detection/blob/d52aca0288b196bdbc3c0dff327e08e648b3fe46/Screenshot_2026-03-11_23_24_38.png)
![image alt](https://github.com/vishnuj29/Email-Detection/blob/ed290ba69b54a329d63233c093ef24847d402ead/Screenshot_2026-03-11_23_22_56.png)
