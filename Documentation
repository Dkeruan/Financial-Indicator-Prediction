**Project Overview**  


This project focuses on utilizing machine learning techniques, specifically XGBoost, to predict stock performance based on over 200 financial indicators extracted from 10-K filings of US publicly traded stocks. 
By leveraging this rich dataset spanning from 2018 to 2024, we aim to investigate the feasibility of using financial indicators for informed investment decisions.  


**Data Description**  


This dataset repository consists of the following CSV files, each containing financial data for US stocks from 2014 to 2018:  

- 2014_Financial_Data.csv <br/>
- 2015_Financial_Data.csv <br/>
- 2016_Financial_Data.csv <br/>
- 2017_Financial_Data.csv <br/>
- 2018_Financial_Data.csv <br/>

Each dataset includes over 200 financial indicators commonly found in yearly 10-K filings of publicly traded companies. On average, there are approximately 4,000 stocks listed in each dataset. The dataset was compiled using the Financial Modeling Prep API and pandas_datareader.

<br/>

**Data Characteristics:**  

- Missing Values: Some financial indicator values are missing (NaN cells), allowing users to choose appropriate cleaning techniques such as dropna or fillna.  

- Outliers: Outliers, likely caused by mistypings, are present in the datasets. Users can decide on cleaning methods, considering percentile values (1% - 99%).  

- Sector Information: The third-to-last column, "Sector," categorizes each stock into sectors such as Basic Materials, Communication Services, Consumer Cyclical, and more. This facilitates sector-based analyses and comparisons.  

- Price Variation: The second-to-last column, "PRICE VAR [%]," indicates the percent price variation of each stock for the year. The last column, "class," provides binary classification for each stock:  

  - Class 1: Indicates stocks that should be bought at the start of the year and sold at the end for a profit (positive price variation).  

  - Class 0: Indicates stocks that should not be bought, as their value is predicted to decrease (negative price variation).  
  
**Preprocessing Steps:**  

Before analysis, the dataset underwent preprocessing steps, including:  

- Exploratory Data Analysis: Examining the structure of the data to understand its format and characteristics.  

- Label Correction: Correcting errors in labeling and checking for inconsistencies in the target variable.  

