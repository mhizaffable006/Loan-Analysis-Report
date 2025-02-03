## Loan-Analysis-Report-Using-Power BI

## Introduction
As part of assessment in the Data Analytics class organized by PSP_Analytics, one of the analytics projects I’ll be working on is the Microfinance Dataset. This Microfinance Bank gives out Loan. The Microfinance Bank dataset contains the Loan_ID, Mode of application,	Loan_status,	Principal, Terms,	Effective_date, Due_date,	Paid_off_time and other data of the Microfinance Dataset. The goal of this work is to design a dashboard using the dataset to answer some business questions and showcase insights.
## Data Sourcing
This dataset used in this work is gotten from the Data Analytics Class announcement channel, which was posted by Mr. Kingsley Adisa.

## Data Preparation
We will load the Dataset in Excel format into Powerbi. If data is clean, we can just load it directly or transform it to clean it on PowerBi.

## Data Cleaning/Transformation
Here, we check if the format of each column is correct and correct it where necessary. We also address inconsistencies in the columns to ensure a more accurate dataset for analysis.

  - I ensure numeric columns (e.g., Loan Amount, Repayment) are formatted appropriately.
  - Handle Missing Data.
  - Use the Filter button in column headers to remove irrelevant records.
  - Apply and Load the Cleaned Data.

## Data Exploration/Visualization
This is where we answered specific business questions loan performance analysis by comparison using charts and tiles. Some of these questions include:

  1. Highest Education and Loan ID
  2. Mode of Application by Age
  3. Loan Status by Guarantor
  4. Gender by Loan Status
  5. Mode of Application by Principal

## KEY PERFORMANCE INDICATORS (KPI)
Before going ahead to answer the question, we first need to specify the KPI (Key Performance Indicators). The KPI include the Total Loan Amount, Count yet to Paid, Maximum Amount Borrowed, Minimum Amount Borrowed and Total Amount Owed. This is done by creating measures and using DAX to calculate the Total Loan Amount, Count yet to Paid, Maximum Amount Borrowed, Minimum Amount Borrowed and Total Amount Owed.

  - Total Loan Amount: I used SUM function to get total loan amount
  - Count yet to Paid: COUNT of Indivituals yet to pay in the dataset
  - Maximum Amount Borrowed: MAX of amount borrowed by individuals in the data set
  - Minimum Amount Borrowed: MIN of amount borrowed by individuals in the dataset
  - Total Amount Owed: I used SUM to get the Total Amount Owed by individuals in the dataset
We then use the KPI tile to visualize our KPI. We could also use the Card tile.

  1. Highest Education and Loan ID
  ![loan by higest edu](https://github.com/user-attachments/assets/227ba4ac-07d4-442e-babd-a05818e52ad8)

  
  2. Mode of Application by Age
 ![mod of app by age](https://github.com/user-attachments/assets/74bd6fa2-6fcd-4f8d-a5b6-bc7aefe7cbce)

  
  3. Loan Status by Guarantor
  ![loan status by guarantos](https://github.com/user-attachments/assets/9dec59d8-6973-4b04-a150-0ba287be8da3)

  
  4. Gender by Loan Status
  ![loan status by gender](https://github.com/user-attachments/assets/923d7ce8-a113-49ac-90b9-be9a2eeabca6)

  
  
5. Mode of Application by Principal
  ![principle by app](https://github.com/user-attachments/assets/26021cf2-0141-4b40-8a7c-dd4ea4ab1f44)


## Conclusion
So far, we’ve been able to analyze the Microfinance Bank dataset and to draw valuable insights through the business questions. Based on these findings, we can be able to provide data-driven recommendations to help for loan business growth. The resulting dashboard built from powerbi is shown below:

![Microfinance Dashboard](https://github.com/user-attachments/assets/a23cb912-4f97-45d6-b124-b942eb4b39db)
![slicers](https://github.com/user-attachments/assets/427b1c33-8695-4a76-860e-758af7185d6e)

