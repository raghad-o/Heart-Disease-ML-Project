# Heart Disease Machine Learning Analysis

## Overview
This project is an individual machine learning study on a heart disease dataset from Kaggle.  
he project focuses on exploring, analyzing, and evaluating different classification models for heart disease prediction.

The objective is to evaluate different models and compare their performance through pairwise comparisons using standard evaluation metrics.

Dataset used:  
https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

---
# Workflow

- Data loading and exploration  
- Data cleaning and preprocessing  
- Feature scaling  
- Train/test split (80/20)  
- Training models: Naive Bayes, Decision Tree, KNN (Euclidean & Manhattan)  
- Model evaluation  
- Cross-validation (5-fold)  
- ROC curve and AUC analysis  
- Decision boundary visualization  

---

## Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-score  
- ROC-AUC  

---

## Libraries

- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

---
## Results

### ROC-AUC
- Decision Tree: ~0.83  
- Naive Bayes: ~0.82  

Both models show strong performance with ROC curves close to the top-left corner.

---

### Cross-Validation (5-Fold)
- Decision Tree Mean Accuracy: ~0.72  
- Naive Bayes Mean Accuracy: ~0.72  

---

### KNN Results
- Best K (Euclidean): 5 → Accuracy ~0.85  
- Best K (Manhattan): 25 → Accuracy ~0.82  

Euclidean distance performed slightly better and produced smoother decision boundaries.

---

## Conclusion

K-Nearest Neighbors (Euclidean) achieved the best performance among all tested models for this dataset.

---

## Note

This project is an independent machine learning project and is not part of any group work.
