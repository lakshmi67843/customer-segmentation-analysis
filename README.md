# Customer Segmentation Analysis

## Project Overview
This project focuses on customer segmentation using the Mall Customers dataset. By applying clustering algorithms such as k-Means, we aim to identify distinct groups of customers based on their spending patterns and personal characteristics. The insights derived from this analysis will help in tailoring marketing strategies to meet the unique needs of each customer segment.

## Dataset
The dataset used in this analysis includes the following key features:
- **Gender:** The gender of the customer (Male/Female).
- **Age:** The age of the customer.
- **Annual Income (k$):** The annual income of the customer in thousands of dollars.
- **Spending Score (1-100):** A score assigned by the mall based on customer behavior and spending patterns.

## Analysis Steps
1. **Data Examination:** Initial inspection of the dataset to understand its structure and any potential data cleaning needs.
2. **Feature Engineering:** Creation of new features such as age groups to enhance clustering accuracy.
3. **Exploratory Data Analysis (EDA):** Visualization of the distribution of key features like age, income, and spending score.
4. **Customer Segmentation:** Application of k-Means clustering to segment customers based on:
    - Annual Income and Spending Score
    - Age and Spending Score
    - Combined features (Age, Annual Income, and Spending Score)
5. **Conclusions:** Summary of findings and recommendations for each customer segment to optimize marketing efforts.

## Technologies Used
- **Python**
- **Pandas** for data manipulation
- **Matplotlib** and **Seaborn** for data visualization
- **scikit-learn** for clustering algorithms
- **Plotly** for interactive 3D visualizations

## How to Use
1. Clone this repository: `git clone https://github.com/AbdulbakiAsur/Customer-Segmentation-Analysis.git`
2. Navigate to the project directory.
3. Install the required libraries using `pip install -r requirements.txt`.
4. Open the Jupyter Notebook `mall_customer_data_analysis.ipynb` to explore the analysis.

## Contact
For any questions or suggestions, please contact me at abdulbakiasur17@gmail.com.

