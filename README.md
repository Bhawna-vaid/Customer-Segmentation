# Customer Segmentation and Purchase Prediction

## 📖 Project Overview
This project focuses on analyzing customer behavior from transaction data to identify different customer segments and predict future purchases. The goal is to help businesses understand their customers better and tailor marketing strategies to improve customer engagement, retention, and profitability.

---

## 🎯 Objectives
1. **Data Cleaning**  
   Prepare and clean customer transaction data by handling missing values, removing duplicates, and transforming variables for analysis.

2. **Feature Engineering**  
   Create new features such as:
   - **Customer Lifetime Value (CLV):** Total spending per customer.
   - **Average Order Value (AOV):** Spending per transaction.
   - **Frequency:** Number of transactions per customer.

3. **Customer Segmentation**  
   Apply clustering techniques like **K-Means** to group customers into segments such as high-value, moderate, and low-value customers.

4. **Modeling**  
   Build predictive models like **Decision Tree Regressor** to forecast future customer purchases based on historical behavior.

5. **Insights & Recommendations**  
   Provide actionable strategies for marketing campaigns based on the segmentation results.

---

## 📂 Dataset
The dataset includes the following columns:
- `InvoiceNo`: Unique invoice number
- `StockCode`: Product code
- `Description`: Product description
- `Quantity`: Number of products sold
- `InvoiceDate`: Date and time of purchase
- `UnitPrice`: Price per unit
- `CustomerID`: Unique customer identifier
- `Country`: Customer’s country

The dataset is preprocessed to ensure data consistency and used for clustering and predictive modeling.

---

## 🛠 Tools and Technologies
- **Python Libraries:**
  - `pandas` for data manipulation
  - `numpy` for numerical calculations
  - `matplotlib` and `seaborn` for data visualization
  - `scikit-learn` for machine learning algorithms and evaluation
- **SQL:** Used for data extraction and querying before analysis
- **Jupyter Notebook:** For data exploration and coding environment

---

## 📈 Results
- Identified customer segments based on spending behavior and frequency.
- Developed models to predict customer purchases with high accuracy.
- Provided actionable insights such as personalized promotions and loyalty strategies.

---

## 📦 How to Run This Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/customer-segmentation.git
