# 🤖 Machine Learning Lab Notebook

A hands-on Jupyter notebook covering core Machine Learning concepts and algorithms, built as part of university coursework. The notebook progresses from NumPy fundamentals through supervised learning algorithms with real-world datasets.

---

## 📁 Repository Structure

```
├── ML.ipynb              # Main Jupyter Notebook
├── car_dataset.data      # Automobile dataset (CSV, no header)
├── titanic.csv           # Titanic passenger dataset
├── Tennis.csv            # Play Tennis decision dataset
└── README.md
```

---

## 📚 Topics Covered

### 1. NumPy Array Operations
- Creating and modifying integer arrays
- Array statistics: mean, median, min, max, sum, product
- Variance and covariance computation

### 2. Data Preprocessing with Pandas (Automobile Dataset)
- Loading raw CSV data with custom headers
- Handling missing values (`?` → `NaN`)
- Imputing missing values using column mean
- Dropping rows with missing target values (`price`)
- Verifying data completeness post-cleaning

### 3. Exploratory Data Analysis — Titanic Dataset
- Survival count plots and pie charts
- Gender distribution analysis
- Age distribution histograms with KDE
- Box plots: Age vs Survival, Fare vs Passenger Class

### 4. Linear Regression
- Predicting salary from CGPA using Scikit-learn
- Extracting slope (coefficient) and intercept
- Scatter plot of actual vs predicted values

### 5. K-Nearest Neighbors (KNN) Classification
- Binary classification: Pass/Fail based on study and sleep hours
- Decision boundary visualization using mesh grid
- Color-coded region plotting (Fail = Red, Pass = Green)

### 6. Decision Tree (ID3 / Entropy)
- Manual entropy and information gain calculation from scratch
- Applied on the classic **Play Tennis** dataset
- Scikit-learn `DecisionTreeClassifier` (criterion: entropy)
- Tree visualization with `plot_tree`
- Label encoding of categorical features
- Predicting outcome for new weather conditions

---

## 🛠️ Tech Stack

| Library | Purpose |
|---|---|
| `numpy` | Array operations and statistics |
| `pandas` | Data loading, cleaning, manipulation |
| `matplotlib` | Plotting and visualization |
| `seaborn` | Statistical visualizations |
| `scikit-learn` | ML models (Linear Regression, KNN, Decision Tree) |
| `math` | Manual entropy calculations |

---

## ⚙️ Setup & Usage

### Prerequisites
- Python 3.8+
- Jupyter Notebook or JupyterLab

### Installation

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### Running the Notebook

```bash
jupyter notebook ML.ipynb
```

> **Note:** Make sure `car_dataset.data`, `titanic.csv`, and `Tennis.csv` are in the same directory as the notebook before running.

---

## 📊 Datasets Used

| Dataset | Description | Source |
|---|---|---|
| `car_dataset.data` | Automobile attributes and prices | UCI ML Repository |
| `titanic.csv` | Titanic passenger survival data | Kaggle / Seaborn |
| `Tennis.csv` | Weather conditions for playing tennis | Classic ML toy dataset |

---

## 🎯 Key Learnings

- How to clean and preprocess real-world tabular data
- Visualizing distributions and relationships in data
- Implementing and interpreting Linear Regression
- Understanding KNN decision boundaries visually
- Building a Decision Tree manually (entropy + information gain) and with Scikit-learn

---

## 👤 Author

**Shivraj**
B.Tech Student — Manav Rachna University

---

## 📄 License

This project is intended for educational purposes only.
