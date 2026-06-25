# 🚀 Polynomial Regression Pipeline

An end-to-end Machine Learning project demonstrating the use of **Polynomial Regression** with a **Scikit-learn Pipeline** to model non-linear relationships in data.

---

## 📖 Project Overview

Traditional Linear Regression struggles to capture complex non-linear patterns. This project uses **Polynomial Feature Engineering** combined with **Linear Regression** inside a Scikit-learn Pipeline to fit curved trends and generate more accurate predictions.

The workflow is automated through a pipeline, making the code cleaner, reusable, and production-friendly.

---

## ✨ Key Highlights

✅ Polynomial Feature Transformation

✅ Scikit-learn Pipeline Implementation

✅ Model Training & Prediction

✅ Synthetic Data Generation

✅ Data Visualization

✅ Clean and Reusable Workflow

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| NumPy | Numerical Computation |
| Pandas | Data Handling |
| Matplotlib | Visualization |
| Scikit-learn | Machine Learning |

---

## ⚙️ Workflow

```text
Data Generation
       ↓
Polynomial Features
       ↓
Pipeline Creation
       ↓
Model Training
       ↓
Prediction
       ↓
Visualization
```

---

## 📊 Model Pipeline

```python
Pipeline([
    ('poly', PolynomialFeatures(degree=3)),
    ('model', LinearRegression())
])
```

---

## 🎯 Learning Outcomes

- Understanding Polynomial Regression
- Feature Engineering with PolynomialFeatures
- Building ML Pipelines
- Automating Machine Learning Workflows
- Visualizing Non-Linear Relationships

---

## 📈 Sample Output

The model successfully learns non-linear patterns and generates a smooth polynomial curve that closely fits the data.

---

## 🔮 Future Enhancements

- Hyperparameter Tuning
- Cross Validation
- Real-world Dataset Integration
- Streamlit Deployment
- Model Comparison (Linear, Ridge, Lasso)

---

## 👩‍💻 Author

**Anushka Verma**  
MCA Student | Data Science Enthusiast  
HBTU Kanpur

⭐ If you found this project useful, consider giving it a star!
