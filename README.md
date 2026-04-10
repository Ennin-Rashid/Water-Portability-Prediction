# 💧 Water Quality & Potability Prediction

**Group 2 | Data Science Capstone Project**

## 📌 Project Overview
A machine learning project that predicts whether water is safe to drink based on 
physicochemical properties such as pH, hardness, chloramines, and turbidity. 
Three classifiers were trained and compared: KNN, Decision Tree, and Random Forest.


## 👥 Team Members
- Harriet Adama
- Esther Oboh Asamoah  
- Ngah Chloehelle
- Rukayat Omotosho-Sanni
- Rashid Ennin

## 📊 Dataset
- **Source:** [Kaggle Water Potability Dataset](https://www.kaggle.com/datasets/adityakadiwal/water-potability)
- **Samples:** 3,276 water samples
- **Features:** 9 water quality parameters
- **Target:** Potability (1 = safe, 0 = unsafe)

## 🔧 Models Used
- K-Nearest Neighbors (KNN)
- Logistic Regression
- Decision Tree
- Random Forest

## 📈 Results Summary
| Model | Accuracy | AUC-ROC |
|---|---|---|
| KNN | 53.5% | 0.482 |
| Decision Tree | 63.7% | 0.605 |
| Random Forest | 69.4% | 0.686 |

**Best model: Random Forest** (100 estimators, all features + 3 engineered safety flags)

## 📁 Files
- `Water_Quality_and_Potability_Prediction.ipynb` - Main Jupyter notebook
- `water_potability.csv` - Dataset
- `GROUP 2 - DATA SCIENCE CAPSTONE PROJECT.pdf` - Technical report

## 🚀 How to Run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook Water_Quality_and_Potability_Prediction.ipynb
