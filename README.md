# Water Potability Prediction

A complete, production-grade data science workflow for predicting water potability using machine learning.

## 📋 Overview

This project analyzes physicochemical properties of water samples to determine whether they are safe for drinking (potable). Using a comprehensive end-to-end machine learning pipeline, we evaluate multiple models and identify the key factors that influence water potability.

**Dataset Features:**
- pH
- Hardness
- Solids
- Chloramines
- Sulfate
- Conductivity
- Organic Carbon
- Trihalomethanes
- Turbidity
- Potability (Target variable)

## 🚀 Quick Start

### Prerequisites
- Python 3.7+
- Jupyter Notebook or JupyterLab
- pandas, numpy, scikit-learn, matplotlib, seaborn

### Installation

```bash
# Clone the repository
git clone https://github.com/Ennin-Rashid/Water-Portability-Prediction.git
cd Water-Portability-Prediction

# Install required packages
pip install -r requirements.txt
```

### Running the Notebook

```bash
jupyter notebook Water_Potability_Analysis.ipynb
```

## 📊 Project Workflow

The notebook follows a complete data science pipeline:

1. **Data Loading** – Import water potability dataset
2. **Exploratory Data Analysis (EDA)** – Analyze distributions, correlations, and target balance
3. **Data Preprocessing** – Handle missing values and normalize features
4. **Model Training** – Compare multiple algorithms
5. **Model Evaluation** – Assess performance with multiple metrics
6. **Feature Importance Analysis** – Identify key predictors

## 🔬 Models Evaluated

### Baseline: Logistic Regression
- Simple, interpretable linear model
- Includes preprocessing pipeline with imputation and standardization
- Balanced class weights to handle imbalanced data

### Production Model: Random Forest
- Ensemble method with 300 estimators
- Superior performance and robustness
- Provides feature importance rankings
- Handles non-linear relationships effectively

## 📈 Key Results

**Random Forest Performance:**
- Accuracy & ROC-AUC scores on test set
- 5-fold stratified cross-validation for robust evaluation
- Confusion matrix analysis for error patterns

**Top Feature Drivers of Water Potability:**
1. Solids
2. Sulfate
3. Organic Carbon
4. pH

## 📁 Project Structure

```
Water-Portability-Prediction/
├── Water_Potability_Analysis.ipynb    # Main analysis notebook
├── water_potability.csv                # Dataset (required)
├── README.md                           # Project documentation
└── requirements.txt                    # Python dependencies
```

## 🛠️ Dependencies

- **pandas** – Data manipulation
- **numpy** – Numerical computing
- **scikit-learn** – Machine learning models and preprocessing
- **matplotlib** – Data visualization
- **seaborn** – Statistical data visualization

## 💡 Usage

1. Ensure `water_potability.csv` is in the project directory
2. Open `Water_Potability_Analysis.ipynb` in Jupyter
3. Run cells sequentially to:
   - Explore data patterns
   - Train models
   - Generate visualizations
   - Evaluate performance

## 📊 Visualizations Included

- Target distribution (class balance)
- Feature histograms (30 bins)
- Correlation heatmap
- Confusion matrix
- Feature importance bar plot

## ✅ Model Deployment

The Random Forest model is suitable for deployment after:
- Threshold tuning for business-specific requirements
- Continuous monitoring of predictions
- Periodic retraining with new data
- Model drift detection

## 📝 Notes

- Training uses stratified train/test split (70/30) to maintain class distribution
- Median imputation handles missing values
- Random Forest includes class weights to address potential imbalance
- Cross-validation (5-fold) provides robust performance estimates

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Improve model performance
- Add new features or preprocessing techniques
- Enhance visualizations
- Optimize the pipeline


## 👤 AUTHORS
## 👥 Team Members
- Harriet Adama
- Esther Oboh Asamoah  
- Ngah Chloehelle
- Rukayat Omotosho-Sanni
- Rashid Ennin
