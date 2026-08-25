# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# Online Retail Transaction Analysis

This project analyses online retail transaction data to identify patterns in sales performance, customer purchasing behaviour, product performance and geographic markets.

The project follows an end-to-end data analytics workflow using Python and Tableau. The raw transaction data was cleaned and transformed through an ETL process, explored using descriptive and statistical analysis, and used to develop a K-Means customer segmentation model based on Recency, Frequency and Monetary (RFM) behaviour.

The findings were then communicated through interactive Tableau dashboards and a guided story to support business decision-making around sales performance, customer retention, product demand and international market opportunities.

The project is designed for business stakeholders who want a clearer understanding of customer behaviour and commercial performance without needing to work directly with the underlying transaction data.
## Dataset Content

The project uses the Online Retail Transaction dataset, containing transaction records from an online retail business.

The raw dataset contains **541,909 rows and 8 columns** and includes information about:

- Invoice number
- Product stock code
- Product description
- Quantity purchased
- Invoice date and time
- Unit price
- Customer ID
- Customer country

The dataset covers transactions between **December 2010 and 9 December 2011**, with December 2011 representing a partial month.

During the ETL process, the dataset was cleaned by investigating and handling missing values, exact duplicates, cancelled transactions, invalid quantities and non-positive unit prices. A new `Revenue` feature was also created using:

`Revenue = Quantity × UnitPrice`

Following cleaning and validation, the final dataset contained **524,878 rows and 9 columns** and was exported as `Online_Retail_Cleaned.csv` for use in the exploratory analysis and machine learning stages.