# Mall-Customer-Segmentation-Kaggle
ProdigyInfotech Task 2

# 🎯 Customer Segmentation Tutorial in Python

![Kaggle Dataset](https://img.shields.io/badge/Kaggle-Customer%20Segmentation-blue)
![Python](https://img.shields.io/badge/Made%20with-Python-yellow)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Project Overview

This project demonstrates **customer segmentation** using the "Mall Customer Segmentation Data", available on Kaggle. It provides a clear example of how to use clustering (specifically K-Means) to segment customers based on their demographic and spending patterns :contentReference[oaicite:1]{index=1}.

---

## 🗂️ Dataset Description

| Column Name            | Description                                  |
|------------------------|----------------------------------------------|
| `CustomerID`           | Unique identifier for each customer          |
| `Gender`               | Customer’s gender (Male or Female)           |
| `Age`                  | Age of the customer                          |
| `Annual Income (k$)`   | Yearly income in thousands of dollars        |
| `Spending Score (1–100)` | Score assigned based on spending behavior |

---

## 🔍 Key Analysis Steps

1. **Data Loading & Cleaning**  
   Imported CSV, checked for nulls, and dropped unnecessary columns (e.g., `CustomerID`).

2. **Exploratory Data Analysis (EDA)**  
   - Visualized distributions of age, income, and spending scores  
   - Explored gender distribution and scatter plots to understand relationships :contentReference[oaicite:2]{index=2}  

3. **Preprocessing**  
   - Label-encoded gender  
   - Standardized features for improved model performance

4. **PCA (Optional)**  
   - Reduced dimensions to 2 components for visualization and clustering

5. **K-Means Clustering**  
   - Determined optimal cluster count using the elbow method  
   - Fitted K-Means model and assigned cluster labels to each customer

6. **Cluster Profiling**  
   - Analyzed age, income, and spending patterns by cluster  
   - Generated heatmap summaries to highlight distinct segments :contentReference[oaicite:3]{index=3}

---

## 📊 Project Insights

- Identified meaningful customer groups (e.g., high spenders vs. low spenders, young vs. older demographics).
- Visual and statistical clustering helped reveal behavioral patterns.
- Potential strategies:
  - **High-income, low-spenders**: Run targeted promotions
  - **Consistent high-spenders**: Offer loyalty benefits
  - **Average spenders**: Nurture with tailored offers

---

## 🛠 Usage Instructions

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/customer-segmentation.git
   cd customer-segmentation
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Jupyter notebook:

bash
Copy
Edit
jupyter notebook
Explore and run through:

Data preprocessing

PCA transformation

Elbow method to find optimal clusters

K-Means clustering

Segment profiling via heatmaps

📁 Project Structure
r
Copy
Edit
📦 customer-segmentation/
 ┣ 📄 Mall_Customers.csv          <- Dataset
 ┣ 📄 customer_segmentation.ipynb <- Analysis notebook
 ┣ 📄 requirements.txt            <- Python dependencies
 ┣ 📄 README.md                   <- This file
🚀 Enhancements & Next Steps
Experiment with PCA + K-Means for more robust segments

Compare with other clustering techniques like DBSCAN or Hierarchical Clustering

Integrate demographic or social media data for richer segmentation

Deploy a dashboard (Streamlit/Flask) to dynamically explore clusters

🔗 References
Dataset Source: Mall Customer Segmentation Data on Kaggle 
rpubs.com
+3
github.com
+3
github.com
+3
kaggle.com
+7
kaggle.com
+7
kaggle.com
+7
rpubs.com
+1
deepnote.com
+1
deepnote.com

Related Kernel: Demonstrates PCA + K-Means workflow 
deepnote.com

🧑‍💻 Author
Peruri Srinivasa Sai Shanmukh
📬 saishanmukh74@gmail.com
🔗 www.linkedin.com/in/sai-shanmukh-667b36290

