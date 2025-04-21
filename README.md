# CREDIT-CARD-FROUD-DETECTION-MODEL

# 💳 Credit Card Fraud Detection using Machine Learning

This project is about detecting fraudulent credit card transactions using a machine learning model trained on real-world anonymized data.

## 📁 Dataset

We used the **Credit Card Fraud Detection** dataset from [Kaggle](https://www.kaggle.com/datasets/kartik2112/frauddetection).  
- It contains transactions made by European cardholders in September 2013.
- Total records: **284,807**
- Fraudulent transactions: **492** (Only ~0.17%)

> ⚠️ The dataset is highly imbalanced, which means there are way more normal transactions than fraudulent ones.

---

## 📌 Project Goal

To build a machine learning model that can:
- Learn patterns from past transaction data.
- Predict whether a new transaction is **fraudulent** or **legitimate**.

---

## 🛠️ Tools & Technologies Used

- Python 🐍
- Google Colab (for testing and training)
- pandas, numpy (data handling)
- seaborn, matplotlib (data visualization)
- scikit-learn (ML model & evaluation)

---

## 📊 Steps Performed

1. **Data Loading**  
   Loaded and explored the dataset to understand class distribution.

2. **Data Preprocessing**  
   - Normalized the `Amount` column using `StandardScaler`.
   - Dropped unnecessary columns like `Time`.

3. **Model Training**  
   Used a **Random Forest Classifier**, a powerful and easy-to-understand ML model.

4. **Model Evaluation**  
   - Evaluated using metrics like **Accuracy**, **Precision**, **Recall**, and **F1-score**.
   - Visualized results with a **Confusion Matrix**.

---

## 📈 Results

The model was able to detect fraud with good accuracy and recall.  
> ⚠️ In fraud detection, **Recall** is very important as we want to catch as many frauds as possible.

---

## 🧠 What I Learned

- How to handle **imbalanced datasets**.
- Importance of **feature scaling**.
- Building and evaluating a machine learning model end-to-end.
- Visualizing and interpreting results in a clear way.

---

## 🚀 How to Use

1. Download the dataset from [here](https://www.kaggle.com/datasets/kartik2112/frauddetection).
2. Open the notebook in [Google Colab](https://colab.research.google.com).
3. Upload `creditcard.csv` when prompted.
4. Run all the cells to train and test the model.

---

## 🙌 Acknowledgements

- Dataset by **Kaggle** and original creators.
- Inspired by real-world fraud detection use-cases in the banking industry.

---

## 👨‍💻 Author

Hi, I'm **Malik Ashhar Ali**, a passionate Computer Science undergraduate with a strong interest in AI and Machine Learning. I enjoy solving real-world problems using technology and have built multiple ML and data-driven projects. I'm also an active participant in college events and a member of the cultural committee.  

Feel free to connect or explore more of my work!

---

Feel free to fork this project, give it a ⭐, or suggest improvements!  
Happy Learning! 😊

