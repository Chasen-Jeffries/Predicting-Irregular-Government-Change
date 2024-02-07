# 🌍 Predicting Major Political Instability

## 📋 Project Overview
This project aims to forecast the impact of political instability in countries worldwide. Utilizing a dataset spanning 20 years and encompassing 30 variables primarily from the World Bank, the project will employ various machine learning models to assess the risk of such events. The variables are categorized into three groups: economic factors, international relations, and political factors.

## 📊 Data
- **Sources**: World Bank, IMF, Barro-Lee...
- **Period**: 20 years (2000-2020) ⏳
- **Variables**: 30, categorized into economic 💹, international relations 🌐, and domestic factors 🏛️

## 🔬 Methodology

### 🔄 Data Preprocessing
- Split variables into three groups.
- Normalize and preprocess data for model compatibility.

### 🛠 Feature Engineering
- Create additional features to capture complex dynamics.

### 🤖 Model Development
For each variable group, develop the following models:
1. Logistic Regression
2. XGBoost
3. SVM
4. RNN
5. GNN

### 📈 Model Training and Validation
- Use training, validation, and test splits.
- Employ cross-validation for hyperparameter tuning.
- Evaluate models using precision, recall, F1 score, ROC-AUC.

### 🎛 Ensemble Model
- Combine outputs from the 15 models (5 models x 3 groups).
- Final ensemble model predicts the likelihood of irregular government change.

### Final Model Evaluation
- Assess predictive accuracy, reliability, and interpretability.

### 🔍 Interpretation and Analysis
- Analyze which factors most influence predictions.
- Provide insights into model decisions.

## 💻 Technical Considerations
- **Python Libraries**: pandas, scikit-learn, TensorFlow/PyTorch, PyTorch Geometric/DGL.
- **Computational Resources**: Adequate for training complex models.

## 📚 Documentation and Reporting
- Thoroughly document the methodology, findings, and challenges encountered.
- Prepare a comprehensive report or presentation for stakeholders, detailing the project's outcomes and implications.
