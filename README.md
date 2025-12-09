# Iris Flower Classification using Decision Tree 

This project builds a Machine Learning model to classify Iris flower species using **Scikit-learn's DecisionTreeClassifier**.  
It demonstrates a complete end-to-end workflow of supervised learning including dataset loading, data splitting, model training, evaluation, and visualization.

---

##  Objective

The goal of this project is to train a Decision Tree classifier to identify the three Iris species:
- Setosa  
- Versicolor  
- Virginica  

It strengthens understanding of:
- Feature–target separation  
- Stratified train-test split  
- Model fitting  
- Evaluation metrics (Accuracy, Precision, Recall, F1-score)  
- Confusion matrix visualization  

---

##  Project Structure

```
Iris_DecisionTree_Classification.ipynb    # Main Notebook
requirements.txt                          # Dependencies
README.md                                 # Project Documentation
```

---

##  Technologies Used

- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 🚀 How to Run the Notebook

### 1️ Clone the repository
```bash
git clone https://github.com/rajesh00618/iris_classification_task3
cd iris_classification_task3
```

### 2️ Install dependencies
```bash
pip install -r requirements.txt
```

### 3️ Launch Jupyter Notebook
```bash
jupyter notebook Iris_DecisionTree_Classification.ipynb
```

---

##  Model Performance

| Metric | Score |
|--------|-------|
| Accuracy | 93.33% |
| Precision (macro) | 0.9333 |
| Recall (macro) | 0.9333 |
| F1-score (macro) | 0.9333 |

The model perfectly identifies Setosa, with slight confusion between Versicolor and Virginica due to overlapping features — a common behavior in Iris models.

---

##  Confusion Matrix

A labeled heatmap is included to visualize prediction performance across all classes.

---

##  Expected Outcomes

- A functional notebook that runs top-to-bottom without errors
- Proper use of stratified split
- Decision Tree trained with default settings
- Metrics printed and confusion matrix plotted
- Markdown explanations for each step

---

##  Author

**Gurugubelli Rajesh**  
GitHub: [@rajesh00618](https://github.com/rajesh00618)



---
