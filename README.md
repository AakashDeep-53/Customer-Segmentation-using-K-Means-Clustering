# Customer Segmentation using K-Means Clustering

This project uses **K-Means Clustering** to segment customers into different groups based on their **age, annual income, and spending score**.

The idea is to identify customers with similar purchasing behaviour so that businesses can better understand their customers and plan targeted marketing strategies.

## 📌 About the Project

The project uses the **Mall Customers dataset**, which contains information about customers such as:

* Customer ID
* Gender
* Age
* Annual Income
* Spending Score

Since there is no predefined target variable, this is an **unsupervised Machine Learning** problem.

## 🔍 What This Project Does

* Loads and explores the customer dataset
* Performs **Exploratory Data Analysis (EDA)**
* Visualizes customer characteristics and relationships
* Selects relevant features for clustering
* Uses the **Elbow Method** to determine a suitable number of clusters
* Applies **K-Means Clustering**
* Assigns customers to different segments
* Visualizes the resulting customer clusters
* Analyses the characteristics of each customer group

## 🤖 Machine Learning

The project uses **K-Means Clustering**, an unsupervised learning algorithm that groups data points based on their similarity.

Customers with similar income and spending behaviour are placed into the same cluster. This helps identify different customer segments, such as customers with higher spending behaviour or customers with lower spending activity.

## 🛠️ Technologies Used

* **Python**
* **NumPy** – numerical operations
* **Pandas** – data manipulation and analysis
* **Matplotlib** – data visualization
* **Seaborn** – statistical visualization
* **Scikit-learn** – K-Means clustering
* **Google Colab / Jupyter Notebook**

## 📂 Project Structure

```text
Customer-Segmentation-using-K-Means-Clustering/
│
├── Project_13_Customer_Segmentation_using_K_Means_Clustering.ipynb
├── Mall_Customers.csv
└── README.md
```

## 📊 Dataset

The project uses the **Mall Customers dataset**, which contains demographic and spending-related information about customers.

The main features used for segmentation are:

* `Age`
* `Annual Income (k$)`
* `Spending Score (1-100)`

## 🎯 Objective

The main objective is to identify meaningful customer groups based on their characteristics and spending behaviour.

These segments can help businesses understand their customers and make more informed decisions regarding **marketing, customer targeting, and personalised offers**.

## 🚀 Future Improvements

The project can be further improved by:

* Trying other clustering algorithms such as DBSCAN or Hierarchical Clustering
* Using additional customer features
* Comparing different clustering techniques
* Building a simple dashboard to visualize customer segments

## 👩‍💻 Author

**Aakash Deep**

B.Tech – Computer Science & Engineering (AI & ML)
Heritage Institute of Technology, Kolkata
