# Bank Loan Analysis Project

The Bank Loan Analysis Project provides stakeholders with actionable insights into loan applications, approvals, and related metrics. This project uses Power BI for visualization and SQL for data manipulation to create an interactive report that helps evaluate loan performance and make decisions.

**Bank Loan Analysis**: [**Live Dashboard**](http://surl.li/lnvtpi)

## Acknowledgments

This project was created using the data set provided and with guidance from [**DATA TUTORIAL YOUTUBE CHANNEL**](http://surl.li/ppajho) Check out their content for more learning and insights.


## Data Source

The loan data used in this project was sourced from an internal banking database containing detailed records of the bank's lending activities.

## Tools Used

- **SQL**: Used for retrieving, processing, and analyzing data from the bank's database.
- **Power BI**: Used for creating dynamic, interactive dashboards and visualizations to represent loan-related metrics and trends.

## Dashboards

### 1. Summary Dashboard
This dashboard provides a high-level overview of the bank's loan portfolio, highlighting key performance indicators (KPIs) and the quality of the loan portfolio.

**KPIs include:**
- Total Loan Applications (MTD and MoM)
- Total Funded Amount (MTD and MoM)
- Total Amount Received (MTD and MoM)
- Average Interest Rate (MTD and MoM)
- Average Debt-to-Income Ratio (DTI) (MTD and MoM)

Additionally, the dashboard differentiates between "good loans" and "bad loans" to evaluate the portfolio's overall health.

### 2. Overview Dashboard
This dashboard showcases a variety of loan-related metrics through visualizations, including:

- Monthly Trends by Issue Date
- Regional Analysis by State
- Loan Term Analysis
- Employment Length Analysis
- Loan Purpose Breakdown
- Home Ownership Analysis

These visualizations provide insights into trends, loan distributions, and borrower demographics.

### 3. Details Dashboard
The detailed dashboard dives into specific loan data, offering deeper insights into the borrowers' profiles and loan performance. Key data fields include:

- Loan ID
- Address State
- Employment Length
- Employee Title
- Grade/Sub Grade
- Home Ownership
- Issue Date
- Loan Status
- Purpose
- Term
- Verification Status
- Annual Income
- Debt-to-Income Ratio (DTI)
- Installment
- Interest Rate
- Loan Amount

These data points are essential for evaluating the creditworthiness, loan structure, and repayment likelihood of borrowers.



## Implementation

- **Data Import**: The loan data was imported from Excel into SQL Server.
- **SQL Queries**: SQL queries were used to retrieve and process the raw data.
- **Power BI**: Interactive dashboards and visualizations were created using Power BI with the processed data.

## Data Validation

A thorough data validation process ensured the accuracy and integrity of the insights:

1. **SQL Query Verification**: SQL queries were executed to retrieve raw data, which served as the benchmark.
2. **Data Consistency Checks**: The results from Power BI were compared against SQL query outputs.
3. **KPI Logic Validation**: SQL scripts were used to replicate KPI calculations, ensuring the accuracy of Power BI computations.
4. **Cross-Verification**: The data transformed in Power BI was cross-verified with the original SQL Server data.

These validation steps ensured the data was accurate and reliable for decision-making.

## Conclusion

The **Bank Loan Analysis Project** provides valuable insights into the bank's lending activities through intuitive and interactive visualizations. By employing robust data validation techniques, this project ensures accurate and reliable analysis for informed strategic decisions.
