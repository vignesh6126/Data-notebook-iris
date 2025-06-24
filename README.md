# 🌼 Iris Dataset - Exploratory Data Analysis (EDA)

This Google Colab notebook demonstrates basic exploratory data analysis (EDA) on the **Iris Dataset**, a classic dataset used in machine learning and statistics. The EDA process involves loading the dataset, generating summary statistics, and visualizing the distribution of features using histograms.

## 📁 Dataset

- **Source:** [Iris Dataset](https://bit.ly/4nejNue)
- **Format:** CSV
- **Features:**
  - `sepal_length`
  - `sepal_width`
  - `petal_length`
  - `petal_width`
  - `species` (setosa, versicolor, virginica)

## 📌 Objectives

- Load and inspect the dataset
- Generate basic statistics (mean, median, standard deviation, etc.)
- Visualize the distributions of numeric features using histograms

## 🛠️ Libraries Used

- [`pandas`](https://pandas.pydata.org/)
- [`matplotlib`](https://matplotlib.org/)

## 🚀 Getting Started

You can open the notebook directly in Google Colab:

👉 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/19yB3LkREChnIIPWi2X0Da2fPiSqfW4sz)

Or run locally using the following steps:

### Prerequisites

Make sure you have Python and the required libraries installed.

```bash
pip install pandas matplotlib
```

### Running the Notebook

1. Clone this repo or download the `.ipynb` file.
2. Run using Jupyter Notebook or Google Colab.

---

## 📊 Exploratory Steps

### ✅ Step 1: Load Data
- Using `pandas.read_csv()` to load data from URL

### ✅ Step 2: View Basic Stats
- `.head()`, `.describe()`, `.mean()`, `.median()`, `.std()`

### ✅ Step 3: Plot Histograms
- Distribution of each numeric feature plotted using `matplotlib`

---

## 📚 References

- [UCI Machine Learning Repository - Iris Dataset](https://archive.ics.uci.edu/ml/datasets/iris)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Documentation](https://matplotlib.org/stable/index.html)

---
