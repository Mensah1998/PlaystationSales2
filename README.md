# 🎮 PlayStation Sales & Metadata Analysis

A data science project analyzing PlayStation game sales across **PS3, PS4, and PS5** using Python. This notebook explores regional sales trends, dataset structure, and visual insights to better understand the performance of games across different markets.

---

## 📌 Project Overview

This project uses a Kaggle dataset containing PlayStation sales and metadata (as of October 2025). The goal is to:

* Load and clean real-world gaming sales data
* Explore regional sales (North America, Japan, etc.)
* Generate visualizations to identify trends
* Build a foundation for deeper analytics or predictive modeling

---

## 🧠 Key Concepts Demonstrated

* Data loading with **Pandas**
* Data inspection and preprocessing
* Working with CSV datasets locally
* Basic data visualization with **Matplotlib**
* Understanding regional sales distributions

---

## 📂 Dataset

The dataset used in this project:

**PlayStation Sales and Metadata (PS3/PS4/PS5) – Oct 2025**

> ⚠️ Note: The dataset is loaded from a local Kaggle directory path:

```python
"C:/Users/user/.kaggle/KaggleDataSets/PlayStation Sales and Metadata (PS3PS4PS5) (Oct 2025).csv"
```

To run this notebook yourself:

1. Download the dataset from Kaggle
2. Place it in your local directory
3. Update the file path if necessary

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas 📊
* Matplotlib 📈

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Install dependencies

```bash
pip install pandas matplotlib
```

### 3. Run the notebook

Open the notebook in Jupyter:

```bash
jupyter notebook PlaystationStats2.ipynb
```

---

## 📊 Example Analysis

The notebook begins by loading the dataset and displaying its structure:

```python
import pandas as pd

df = pd.read_csv("your_file_path.csv")
print(df.head())
```

It then extracts regional sales data such as:

* North America Sales
* Japan Sales
* Other regions (depending on dataset columns)

These are visualized using Matplotlib to highlight trends.

---

## 📎 Notes

* The current notebook uses a **local file path**, which may not work on other systems without modification.
* Consider using relative paths or environment variables for better portability.

---

## 🤝 Contributing

Contributions are welcome. Feel free to fork the repo and submit a pull request.

---

---

## ⭐ Acknowledgements

* Kaggle for providing the dataset
* The Python data science community

---

> If you found this project useful, consider giving it a ⭐ on GitHub!
