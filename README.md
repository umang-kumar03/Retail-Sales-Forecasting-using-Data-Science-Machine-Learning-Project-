# Walmart-Store-Sales-Forecasting-Using-Machine-Learning-Algorithms

## Introduction
In today's dynamic and competitive retail landscape, the ability to accurately predict future sales is paramount for business success. Store owners and managers need reliable tools to anticipate customer demand, optimize inventory management, and make data-driven decisions that can ultimately boost profitability. One such tool that has gained significant traction in recent years is machine learning (ML), specifically the use of advanced algorithms to predict weekly sales with a high degree of accuracy.

Store Sales Forecasting using machine learning algorithms is a cutting-edge approach that leverages historical sales data, and external factors to provide forecasts that are not only precise but also adaptable to changing market conditions. By harnessing the power of machine learning, businesses can gain a competitive edge by aligning their supply chain, staffing, and marketing strategies with anticipated demand, resulting in improved customer satisfaction and increased revenue.

In this project, we will conduct an analysis of Walmart sales data for 45 stores over the time period from February 5, 2010, to October 26, 2012. The dataset includes various features such as store information, department details, economic indicators such as the Consumer Price Index, unemployment rate, weather information, promotional markdowns, fuel prices, and more. Our primary objective is to employ machine learning algorithms to forecast weekly sales for each store, leveraging this extensive set of features.

## Problem Definition
In the face of underperforming sales and the pressing need for growth, this project centers on devising a comprehensive strategy to augment store sales and attract a higher volume of customers within the next three months. The store finds itself operating within a fiercely competitive retail landscape, which necessitates innovative approaches to meet desired sales targets and expand its market presence. Over this short-term horizon, the objective is to realize a 5% surge in customer numbers.

Our success benchmarks revolve around two primary goals. The first is to increase weekly sales by 10%, this will be achieved through a strategic expansion plan, entailing the establishment of new store branches across diverse regions. These new locations are expected to contribute significantly to the overall sales growth. The second goal is to enhance customer engagement and experience, as customer satisfaction and loyalty are pivotal. We aim to achieve this through enhanced customer engagement strategies and an enriched shopping experience, ensuring customers return and recommend the store to others.
But several constraints shape the parameters of this project. The foremost constraint revolves around financial resources, where budgetary limitations prevail. Limited funds must be allocated wisely, earmarked for the dual purpose of opening new store branches and implementing strategies geared towards amplifying sales. Another pivotal constraint pertains to legal and ethical compliance. All marketing and sales activities must adhere strictly to legal and ethical standards, ensuring that the strategies employed align with industry regulations and uphold the store's reputation.

The project will concentrate on the 45 existing stores, with particular emphasis on regions that have demonstrated the highest sales potential. By focusing efforts on these key areas and considering the outlined constraints and objectives, we aim to revitalize the store's performance and foster sustainable growth over the next three months.

# Retail Sales Forecasting using Machine Learning

## Project Overview
This project focuses on forecasting retail store sales using Machine Learning techniques. The objective is to analyze historical sales data, identify key factors affecting sales, and build predictive models to forecast future weekly sales accurately.

The project uses Walmart retail sales data and applies data preprocessing, feature engineering, exploratory data analysis (EDA), machine learning modeling, and performance evaluation to generate business insights.

---

## Business Objective
- Predict future weekly sales of retail stores.
- Understand the impact of holidays, store size, fuel prices, unemployment, and promotional markdowns on sales.
- Support data-driven business decisions for inventory management and sales planning.

---

## Dataset Information
The project uses the following datasets:

- **train.csv** – Historical weekly sales data
- **stores.csv** – Store information such as store type and size
- **features.csv** – Economic indicators and promotional information

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost

---

## Project Workflow

### 1. Data Collection
Loaded sales, store, and feature datasets.

### 2. Data Preprocessing
- Missing value handling
- Data type conversion
- Dataset merging
- Feature creation

### 3. Exploratory Data Analysis (EDA)
- Sales trend analysis
- Holiday impact analysis
- Store-wise sales comparison
- Correlation analysis

### 4. Feature Engineering
- Year extraction
- Month extraction
- Categorical feature encoding

### 5. Model Building
Implemented and compared:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor

### 6. Model Evaluation
Evaluation metrics:
- MAE
- RMSE
- R² Score

---

## Key Findings
- Store size significantly impacts weekly sales.
- Holiday periods generally lead to higher sales.
- Seasonal trends improve forecasting accuracy.
- Machine learning models provide accurate sales predictions for business planning.

---

## Repository Structure

Retail-Sales-Forecasting/

├── datasets/

│ ├── train.csv

│ ├── stores.csv

│ └── features.csv

├── retail_sales_forecasting.ipynb

├── requirements.txt

└── README.md

---

## Author

**Umang Kumar**

M.Sc. Mathematics, IIT Delhi

Aspiring Data Analyst | Data Science Enthusiastv
