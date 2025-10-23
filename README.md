# 🍄 Mushroom Classification using SVM and Logistic Regression

This project focuses on building a **machine learning model** to classify mushrooms as **edible** or **poisonous** based on their physical characteristics.  
Two algorithms are implemented and compared: **Support Vector Machine (SVM)** and **Logistic Regression**.

---

## 🧠 Project Overview

Mushrooms have many observable traits such as color, shape, odor, and texture.  
By using these features, we can train a classification model to predict whether a given mushroom is safe to eat or poisonous.  

This project aims to:
- Explore and preprocess the **UCI Mushroom Dataset**.
- Build and evaluate two classifiers: **SVM** and **Logistic Regression**.
- Compare their accuracy and performance metrics.

---

## 📊 Dataset

- **Source:** [UCI Machine Learning Repository - Mushroom Dataset](https://archive.ics.uci.edu/ml/datasets/Mushroom)
- **Instances:** 8124 mushrooms  
- **Features:** 22 categorical attributes (e.g., cap-shape, color, odor)  
- **Target:** `edible` or `poisonous`

Each attribute is encoded to numerical form for use with ML algorithms.

---

## ⚙️ Model Training

### 1. Logistic Regression
A simple linear model used as a baseline classifier.  
Good for interpretability and quick training.

### 2. Support Vector Machine (SVM)
A more powerful non-linear model using the **RBF kernel**, often achieving higher accuracy in classification tasks.

---

## 🧩 Steps

1. **Data Cleaning & Encoding**  
   - Handled missing values.  
   - Converted categorical data using `LabelEncoder`.

2. **Feature Scaling**  
   - Applied `StandardScaler` for optimal SVM performance.

3. **Model Training**  
   - Split data into 80% train / 20% test.  
   - Trained both Logistic Regression and SVM models.

4. **Evaluation**  
   - Measured **accuracy**, **precision**, **recall**, and **F1-score**.  
   - Compared confusion matrices.

---

## 📈 Results

| Model | Accuracy | Precision | Recall | F1-score |
|--------|-----------|------------|---------|-----------|
| Logistic Regression | 95.6% | 95% | 96% | 95% |
| SVM (RBF Kernel) | **98.9%** | **99%** | **99%** | **99%** |

✅ **SVM outperformed Logistic Regression**, achieving higher overall classification accuracy.

---

## 🧰 Technologies Used

- Python 3.x  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib / Seaborn (for visualization)

---

## 📁 Project Structure

# MushroomClassification
