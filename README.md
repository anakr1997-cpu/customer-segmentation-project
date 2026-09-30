#  Customer Segmentation & Clustering

## Project Overview

An end-to-end customer analytics project using **Python and K-Means clustering** to analyze customer characteristics and identify distinct customer segments based on income and spending behavior.

The analysis uses customer demographic and spending data to explore behavioral patterns and demonstrate how unsupervised machine learning can be used to segment customers for more targeted business strategies.

**Tools:** Python • Jupyter Notebook • Pandas • Seaborn • Matplotlib • Scikit-learn

---

##  Business Questions

- What patterns can be identified in customer demographics and spending behavior?
- How are customers distributed across age, income, and spending score?
- Can customers be grouped into meaningful segments based on income and spending behavior?
- What characteristics distinguish the different customer segments?
- How can customer segmentation support targeted business strategies?

---

##  Analysis & Key Findings

### Customer Overview

The dataset contains **200 customers** with information on:

- Gender
- Age
- Annual Income
- Spending Score

The average customer age was approximately **39 years**, with an average annual income of **$60.56K** and an average spending score of **50.2**.

### Customer Characteristics

The analysis compared customer characteristics by gender.

Average values were:

| Gender | Average Age | Average Income | Average Spending Score |
|---|---:|---:|---:|
| Female | 38.1 | $59.25K | 51.5 |
| Male | 39.8 | $62.23K | 48.5 |

The analysis also examined relationships between numerical variables. Age showed a negative relationship with spending score, while annual income and spending score showed very little linear correlation in the overall dataset.

### Income-Based Segmentation

K-Means clustering was used to segment customers based on **annual income**.

The resulting three income clusters contained:

- Cluster 0: 72 customers
- Cluster 1: 36 customers
- Cluster 2: 92 customers

The clusters primarily differentiated customers by income level, with average incomes of approximately:

- **$33.0K**
- **$99.9K**
- **$66.7K**

### Income & Spending Segmentation

K-Means was then applied using both **annual income and spending score**, producing five customer segments.

The resulting segments showed distinct combinations of income and spending behavior:

| Segment | Avg. Age | Avg. Income | Avg. Spending Score |
|---|---:|---:|---:|
| 0 | 32.7 | $86.5K | 82.1 |
| 1 | 42.7 | $55.3K | 49.5 |
| 2 | 41.1 | $88.2K | 17.1 |
| 3 | 45.2 | $26.3K | 20.9 |
| 4 | 25.3 | $25.7K | 79.4 |

These segments highlight different customer profiles, including higher-income/high-spending customers and lower-income/high-spending customers, as well as lower-spending groups.

### Multivariate Clustering

The project also explored multivariate clustering using:

- Age
- Annual Income
- Spending Score
- Gender

The features were standardized using `StandardScaler` before applying the clustering analysis.

---

## 🤖 Machine Learning Approach

### K-Means Clustering

K-Means was used to group customers based on similarities in their characteristics and spending behavior.

The analysis explored clustering at three levels:

1. **Univariate clustering** — Annual Income
2. **Bivariate clustering** — Annual Income + Spending Score
3. **Multivariate clustering** — Age + Annual Income + Spending Score + Gender

The **elbow method** was used to examine cluster inertia across different numbers of clusters.

---

##  Technical Skills

### Python

- Pandas
- Data loading and exploration
- Data aggregation
- Grouping and descriptive statistics
- Correlation analysis
- Feature preparation

### Data Visualization

- Matplotlib
- Seaborn
- Distribution plots
- KDE plots
- Box plots
- Scatter plots
- Pair plots
- Heatmaps

### Machine Learning

- K-Means clustering
- Cluster analysis
- Elbow method
- Feature scaling
- StandardScaler
- One-hot encoding

---

##  Jupyter Notebook

**[View Customer Segmentation Analysis](Customer_Segmentation_Project.ipynb)**

The notebook contains the complete analysis, including data exploration, visualization, correlation analysis, K-Means clustering, feature scaling, and customer segment analysis.

---

##  Project Takeaway

This project demonstrates my ability to use **Python for exploratory data analysis and unsupervised machine learning** to identify patterns in customer behavior.

I progressed from exploring individual customer characteristics to developing increasingly complex customer segments using income, spending behavior, demographics, and gender.

**Raw Customer Data → EDA → Data Visualization → Feature Analysis → K-Means Clustering → Customer Segments → Business Insights**

---

##  Project Files

- **[Customer Segmentation Analysis](Customer_Segmentation_Project.ipynb)** — Complete Python/Jupyter Notebook analysis.
- **[Visualizations](Customer_Segmentation_Project.ipynb)** — Visual analysis and clustering results are included in the notebook.
