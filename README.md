Loan Application Data Analysis - Excel Project

📌 Project Description

Imagine you're a data analyst at a finance company specializing in lending various types of loans to urban customers. Your company faces a challenge: some customers who lack a sufficient credit history default on their loans. The goal of this project is to use Exploratory Data Analysis (EDA) to analyze loan applications and identify patterns that influence loan default risks. This analysis will help the company make better loan approval decisions and minimize financial losses.

✅ Business Problem

When a customer applies for a loan, there are two key risks:

False Rejection: If a capable applicant is denied a loan, the company loses business.

False Approval: If an incapable applicant is approved, the company faces a financial loss.

The dataset contains information about loan applications with two key categories:

Customers with payment difficulties: Late payment of more than X days on at least one of the first Y installments.

All other cases: Payments made on time.

Possible loan application outcomes:

Approved: Loan application accepted.

Cancelled: Customer canceled the application.

Refused: Loan application rejected.

Unused Offer: Approved loan but not utilized.

The objective is to understand how customer and loan attributes influence the likelihood of default through EDA in Microsoft Excel.

📊 Data Analytics Tasks

1️⃣ Identifying & Handling Missing Data

Used COUNTBLANK function to identify missing values.

Highlighted columns with >40% missing values using conditional formatting.

Dropped columns with excessive missing data.

Used MODE for categorical data imputation and MEDIAN for numerical values.

Created bar charts to visualize missing data proportions.

2️⃣ Outlier Detection & Handling

Used QUARTILE, IQR, and Scatter Plots to detect outliers.

Removed unrealistic values (e.g., 1000+ years of employment and 11+ children).

Box plots used to visualize outliers.

3️⃣ Data Imbalance Analysis

Used COUNTIF and SUM functions to calculate class imbalance.

Identified severe imbalance: 92% target=0 vs. 8% target=1.

Created pie charts and bar charts to visualize imbalance.

4️⃣ Univariate, Segmented Univariate & Bivariate Analysis

Used Pivot Tables, COUNT, AVERAGE, and MEDIAN for statistical insights.

Univariate Analysis: Distribution of individual variables.

Segmented Univariate Analysis: Compared distributions for different scenarios (default vs. non-default customers).

Bivariate Analysis: Used scatter plots and heatmaps to explore variable relationships.

5️⃣ Correlation Analysis

Used CORREL function to compute relationships between features.

Created heatmaps to visualize correlations.

Identified strong correlations, such as Income vs. Credit Amount and Age vs. Years Employed.

📌 Technologies Used

Microsoft Excel 2019 (Pivot Tables, Statistical Functions, Charts)

Data Cleaning & Preprocessing

Exploratory Data Analysis (EDA)

📁 Project Files

Excel Dataset (Original + Cleaned Data)

Excel Analysis File (Pivot Tables, Charts, Calculations)

Presentation/Report (Summary of Findings)

Excel File Link

Project Video Explanation

📈 Key Insights & Business Impact

Customers with higher income tend to have lower default rates.

Longer employment duration is correlated with better repayment behavior.

Severe data imbalance could impact predictive modeling accuracy.

Loan approval process can be optimized using risk-based interest rates for high-risk applicants.

🚀 Conclusion

This project showcases how Excel can be used for effective data analysis in the finance sector. By cleaning data, handling missing values, detecting outliers, analyzing trends, and computing correlations, we can derive meaningful insights that help financial institutions reduce loan default risks and improve decision-making.
