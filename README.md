# Breast Cancer Prediction using Machine Learning
This project uses multiple machine learning algorithms to predict breast cancer based on medical data. The effect of SMOTE (Synthetic Minority Oversampling) was analyzed to handle class imbalance.

## 🔧 Tools & Technologies Used
- Python
- Scikit-learn
- Pandas, NumPy
- Matplotlib / Seaborn
- SMOTE (from imblearn)

## 📊 Results Before Applying SMOTE

| Model         | Accuracy | Precision | Recall  | F1-Score | Support |
|---------------|----------|-----------|---------|----------|---------|
| KNN           | 0.9474   | 0.9440    | 0.9440  | 0.9440   | 114     |
| Naive Bayes   | 0.9649   | 0.9673    | 0.9581  | 0.9623   | 114     |
| Decision Tree | 0.9474   | 0.9440    | 0.9440  | 0.9440   | 114     |
| AdaBoost      | 0.9737   | 0.9742    | 0.9697  | 0.9719   | 114     |
| Random Forest | 0.9649   | 0.9673    | 0.9581  | 0.9623   | 114     |
| XGBoost       | 0.9561   | 0.9554    | 0.9510  | 0.9531   | 114     |

## 📈 Results After Applying SMOTE

| Model         | Accuracy | Precision | Recall  | F1-Score | Support |
|---------------|----------|-----------|---------|----------|---------|
| KNN           | 0.9474   | 0.9538    | 0.9348  | 0.9429   | 114     |
| Naive Bayes   | 0.9737   | 0.9797    | 0.9651  | 0.9716   | 114     |
| Decision Tree | 0.9298   | 0.9292    | 0.9207  | 0.9246   | 114     |
| AdaBoost      | 0.9561   | 0.9554    | 0.9510  | 0.9531   | 114     |
| Random Forest | 0.9561   | 0.9554    | 0.9510  | 0.9531   | 114     |
| XGBoost       | 0.9386   | 0.9412    | 0.9278  | 0.9337   | 114     |


## ▶️ How to Run
1. Clone the repository  
2. Install dependencies using `pip install -r requirements.txt`  
3. Run Jupyter Notebook or Python script inside `notebooks/`

