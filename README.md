<h1 align="center">🍄 Mushroom Classification Project</h1>

<p align="center">
  <img src="https://media.giphy.com/media/ASd0Ukj0y3qMM/giphy.gif" width="200"/>
</p>

<p align="center">
  Machine Learning models for predicting whether a mushroom is <b>edible</b> or <b>poisonous</b> based on the UCI Mushroom Dataset.
</p>

---

## 🚀 About the Project

This project builds **4 different classification models** using the Mushroom dataset:

- 🟦 **K-Nearest Neighbors (KNN)**
- 🌳 **Decision Tree**
- 🌲 **Random Forest**
- 📈 **Logistic Regression**

Goal:  
➡️ Predict whether a mushroom is **poisonous (p)** or **edible (e)** using categorical features.

---

## 🎯 Features

✔ Full preprocessing (Label Encoding)  
✔ Train/test split  
✔ Model training  
✔ Confusion matrices  
✔ Precision, Recall, F1-score comparison  
✔ Visualizations (heatmap + performance plots)  
✔ Clean ML pipeline  

---

## 🧬 Dataset

Dataset manbasi:  
UCI Machine Learning Repository  
⭐ 23 categorical features  
⭐ No missing values  
⭐ Fully balanced target class  

---

## 📊 Model Comparison (Summary)

| Model | Precision | Recall | F1-Score |
|------|-----------|--------|----------|
| KNN | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ |
| Decision Tree | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ |
| Random Forest | 🏆 **BEST** | 🏆 **BEST** | 🏆 **BEST** |
| Logistic Regression | ⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐ |

> 🏆 **Random Forest** gives nearly **100% accuracy** on this dataset.

---

## 🔥 Visual Examples

### 📌 Correlation Heatmap  
<img src="https://raw.githubusercontent.com/your-username/your-repo-name/main/images/corr.png" width="600"/>

### 📌 Confusion Matrix  
<img src="https://raw.githubusercontent.com/your-username/your-repo-name/main/images/cm_rf.png" width="500"/>

---

## 📁 Project Structure

```
mushroom-classification/
│── data/
│   └── mushrooms.csv
│
│── images/
│   ├── corr.png
│   ├── cm_knn.png
│   ├── cm_dt.png
│   ├── cm_rf.png
│   └── cm_logreg.png
│
│── notebook/
│   └── mushroom_classification.ipynb
│
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone repository

```bash
git clone https://github.com/your-username/mushroom-classification.git
cd mushroom-classification
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run Jupyter Notebook

```bash
jupyter notebook
```

---

## 🧠 Models Used

### 🔹 K-Nearest Neighbors (KNN)
Simple and effective but slower for large datasets.

### 🔹 Decision Tree
Interpretable, fast, may overfit.

### 🔹 Random Forest
⭐ Best performer  
⭐ Multiple decision trees  
⭐ Robust & accurate  

### 🔹 Logistic Regression
Baseline linear model.

---

## 🏁 Results

Random Forest classifier achieves **near-perfect classification** because the dataset is:

- 100% categorical  
- Highly discriminative  
- Clean and well-structured  

---

## 🎥 Demo Animation

<p align="center">
  <img src="https://media.giphy.com/media/4Zo41lhzKt6iZ8xff9/giphy.gif" width="320">
</p>

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first.

---

## ❤️ Author

**Your Name**  
📬 Email: your-email@example.com  
🌐 GitHub: your-username  

---

## ⭐ Don’t forget to star the repo if you like it!

<p align="center">
  <img src="https://media.giphy.com/media/l0MYKDrs6ZVzvDeYI/giphy.gif" width="200"/>
</p>
