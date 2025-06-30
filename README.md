## 🎯 Objective
Train and evaluate Decision Tree and Random Forest classifiers using the cleaned Titanic dataset to predict passenger survival.

---

## 📁 Dataset Used
- **cleaned_data.csv**: Preprocessed Titanic dataset  
- Features scaled and encoded  
- Null values handled

---

## 🧠 Models Trained

### ✅ Decision Tree
- `max_depth = 3`
- Accuracy: ~78%
- Evaluated using `classification_report`
- Visualized using `plot_tree()`
- Image saved as: `decision_tree_plot_fixed.png`

### ✅ Random Forest
- `n_estimators = 100`
- Accuracy: ~79%
- Cross-validation score: ~81%
- Feature importance extracted using `feature_importances_`

---

## 🔍 Top 5 Most Important Features
1. Sex  
2. Fare  
3. Age  
4. Pclass  
5. SibSp  

---

## 📦 Libraries Used
- pandas  
- scikit-learn  
- matplotlib  

---

## 📂 Files Included
- `DT.ipynb` – main code file  
- `cleaned_data.csv` – input dataset  
- `decision_tree_plot_fixed.png` – saved plot image
- `README.md` – Task description and summary

---
