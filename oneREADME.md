
# Customer Churn Prediction using Logistic Regression

This project uses **Logistic Regression** to predict customer churn based on customer demographics and account data. The model achieves a strong **93% accuracy**, providing valuable insights into which customers are at risk of leaving a service.

## 📌 Objective

To build a machine learning model that predicts whether a customer will churn using the Customer Churn dataset.

## 🧪 Workflow Summary

### 1. Data Preprocessing
- Loaded the Customer Churn dataset.
- Cleaned the data: removed the `customerID` column and handled missing values.
- Encoded categorical variables using **Label Encoding** and **One-Hot Encoding**.
- Standardized numerical features with **StandardScaler**.

### 2. Exploratory Data Analysis (EDA)
- Visualized customer churn distribution.
- Explored key features like:
  - Contract type
  - Monthly charges
  - Tenure
- Identified patterns such as high churn among customers with month-to-month contracts or short tenure.

### 3. Model Training
- Used **Logistic Regression** from scikit-learn.
- Split the data into training and testing sets (80/20).
- Evaluated model using **accuracy score**, achieving **93% accuracy** on the test data.

## 📈 Results

- **Model Used**: Logistic Regression  
- **Accuracy Achieved**: **93%**  
- **Key Insight**: Customers with short tenure and monthly contracts are more likely to churn.

## 💻 Technologies Used

- Python 3.x  
- pandas, numpy  
- scikit-learn  
- matplotlib, seaborn  
- Jupyter Notebook  


## 📁 Project Structure

```
Customer_Churn_Prediction/
│
├── Customer_Churn_Prediction.ipynb   # Main notebook
├── README.md                         # Project description
```

## 📬 Contact

Feel free to reach out for feedback, questions, or collaboration at https://www.linkedin.com/in/muhammad-hurraira-0993a4346/.
