
# Week 6 Project – Machine Learning Model Evaluation & Hyperparameter Tuning

This project demonstrates an in-depth understanding of core machine learning concepts and techniques covered in **Week 6**, including:

## Covered Topics

- **Clustering Algorithms**:
  - K-Means
  - Hierarchical Clustering
  - DBSCAN
  - Gaussian Mixture Models

- **Ensemble Methods**:
  - Bagging, Boosting, Stacking
  - Random Forest, Gradient Boosting

- **Regularization Techniques**:
  - L1 (Lasso), L2 (Ridge), ElasticNet

- **Model Evaluation**:
  - Accuracy, Precision, Recall, F1-Score
  - Confusion Matrix & Visual Comparisons

- **Hyperparameter Tuning**:
  - GridSearchCV
  - RandomizedSearchCV

## Dataset

The [Adult Income Dataset](https://archive.ics.uci.edu/ml/datasets/adult) was used to predict whether a person earns more than $50K/year based on census data.

## Implementation Highlights

- Trained multiple ML models: Logistic Regression, SVM, KNN, Decision Tree, Random Forest, Gradient Boosting
- Applied various regularizations (L1, L2, ElasticNet)
- Compared model performances **before and after tuning** with insightful visualizations
- Used **StackingClassifier** to combine model predictions for improved performance
- Evaluated with standard metrics and visualized with **matplotlib**

## Graphs & Visualization

The notebook includes side-by-side bar charts comparing **baseline vs tuned models** for each metric (Accuracy, Precision, Recall, F1).

## Files

- `week6_adult_income.ipynb` – Main Jupyter notebook
- `week6_adult_income.html` – Rendered notebook as HTML (for viewing without Jupyter)
- `README.md` – This file

## GitHub Pages View

You can preview this notebook as a webpage here:  
 [https://arpitdhasmana.github.io/CelebalTechnologies_week6/](https://arpitdhasmana.github.io/CelebalTechnologies_week6/)

## How to Run

To convert the notebook to HTML:

```bash
python -m nbconvert --to html week6_adult_income.ipynb
```

## Acknowledgments

This work is based on Week 6 of the ML course curriculum. Special thanks to all resources, especially [KDnuggets Hyperparameter Tuning Guide](https://www.kdnuggets.com/hyperparameter-tuning-gridsearchcv-and-randomizedsearchcv-explained).

---
**Author**: Arpit  
**Course**: Machine Learning – Week 6 Project  
