# Grocery_Store_Customer_Segmentation
Grocery Store(Smart Cart) Clustering – Customer segmentation using K-Means clustering to analyze shopping behavior and spending patterns.


Smart Cart Clustering is a Machine Learning project that segments customers based on their shopping behavior using K-Means clustering.  
The goal is to identify different types of customers based on spending patterns and improve business decision-making.

---

## 📌 Project Objective

- Perform customer segmentation
- Analyze spending patterns
- Identify high-value customers
- Visualize clusters
- Help businesses optimize marketing strategies

## 🧠 Methodology

The project follows a standard ML pipeline:

1. **Data Loading & Exploration** — Understanding the shape, types, and statistics of the data
2. **Data Preprocessing** — Handling missing values, scaling features
3. **Finding Optimal K** — Using the Elbow Method to determine the best number of clusters
4. **Model Training** — Applying K-Means Clustering
5. **Visualization** — Plotting clusters to interpret segments
6. **Insights** — Deriving business meaning from each segment

---

## 🔍 Results — 4 Customer Segments

| Cluster | Segment Name | Description |

| 0 | Mid-Income Moderate Buyers | Customers with high purchase amounts — top-value buyers |
| 1 | High-Income Premium Shoppers | Moderate spenders — consistent and loyal customers |
| 2 | High-Income Digital-First Buyers | Low purchase amounts — occasional or passive buyers |
| 3 | Lower-Income Cautious Shoppers | Previously active buyers with declining spend |


---

## 🛠️ Tech Stack

- **Python 3**
- **Pandas** — Data manipulation
- **NumPy** — Numerical operations
- **Scikit-learn** — K-Means Clustering, preprocessing
- **Matplotlib & Seaborn** — Data visualization
- **Google Colab** — Development environment

---

## 📈 Project Workflow

1. Data Cleaning
2. Feature Engineering
3. Data Scaling
4. K-Means Model Training
5. Cluster Visualization
6. Business Insights Extraction

---

## 📷 Sample Output

- Elbow Curve
- Cluster Scatter Plot
- Spending Distribution by Cluster

---

## 🚀 How to Run

1. Clone the repository:


**Option 1: Open in Google Colab (Recommended)**

Click the badge above ☝️ or [click here](https://colab.research.google.com/drive/1MgEX8RFNfFsZsNoO8fphApgc0iric2R9?usp=sharing)

**Option 2: Run Locally**

```bash
# 1. Clone the repository
git clone https://github.com/Tanvir-Sheikh-R/Grocery_Store_Customer_Segmentation.git
cd Grocery_Store_Customer_Segmentation

# 2. Install dependencies
pip install numpy pandas matplotlib seaborn scikit-learn kneed yellowbrick

# 3. Launch Jupyter Notebook
jupyter notebook notebooks/Grocery_Store_Customer_Segmentation.ipynb
```

---

## 🔮 Future Improvements

- Try DBSCAN / Hierarchical Clustering
- Deploy as Web App (Streamlit)
- Add Real-time Customer Prediction API
- Build Recommendation System

---

## 👤 Author

MD. Tanvir Sheikh  
Aspiring Machine Learning Engineer
