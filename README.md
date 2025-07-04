# 🌲 Day 4 - Random Forest Classifier with Confusion Matrix

This project demonstrates the use of a **Random Forest Classifier** to classify the Iris flower dataset.  
We also evaluate the model using a **confusion matrix**, a **classification report**, and **custom predictions** to understand its performance in detail.

---

## 📊 Dataset
- **Source**: Built-in Iris dataset from `sklearn.datasets`
- **Features**:
  - Sepal length
  - Sepal width
  - Petal length
  - Petal width
- **Target Classes**:
  - Setosa
  - Versicolor
  - Virginica

---

## 🤖 Model Used
```python
from sklearn.ensemble import RandomForestClassifier
model = RandomForestClassifier(n_estimators=100, random_state=42)

✅ What This Project Covers

📥 Loading and preparing data

🔪 Splitting into train/test sets

🤖 Training a Random Forest model

📊 Evaluating model with confusion matrix and classification report

🎯 Making predictions on custom input

🧠 Understanding precision, recall, f1-score, and support

📈 Visualizations
Confusion Matrix Heatmap
Clearly shows how well the model distinguishes between flower species.

Classification Report
Metrics like precision, recall, and F1-score help understand performance per class.

📦 Libraries Used
pandas

scikit-learn

matplotlib

seaborn


---

### ✅ How to Add

1. Open your project folder:  
   `day_4_random_forest_visualizer/`

2. Create a new file named:  
   `README.md`

3. Paste the entire content above into that file and save it.

4. Then push to GitHub:

```bash
git add README.md
git commit -m "Add complete and polished README for Day 4"
git push
