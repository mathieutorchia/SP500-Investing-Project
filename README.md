# SP500-Investing-Project

## Intro

In this notebook, we will explore the long-term effects of periodically investing in the stock market, as well as how inflation affects your bottom line. Please visit www.mathieutorchia.com to read an article about the findings from this python notebook.

### Downloadable Content
Before starting to code, you must download the csv file "cpi_monthly_USA.csv" which has a record of the monthly CPI in the United States from 1947 to 2024 (available to download from this page).

## Jupyter Notebook Code

### Importing Packages
In this section, I simply import the necessary packages used throughout the notebook. I also set the values of 4 key variables which are used in subsequent blocks of code:
- **start_date**: When our typical investor starts to purchase stocks.
- **end_date**: When our typical investor stops to purchase stocks.
- **initial_investment**: The initial sum of money the investor decides to invest in the market at once.
- **monthly_investments**: The additional monthly investment that the investor will commit to investing.

### Data Preperation
In this section, we are simply gathering, cleaning, organizing, and merging three important data sets together:
- **S&P 500**: This data set records historical data on the S&P 500 such as the opening price, closing price, volume, etc. of a given day.
- **CPI**: This data records the monthly CPI in the United States from 1947 to 2024.
- **Dividend**: This uses the *Beautiful Soup* web scraping package to web scrape the dividend data from the S&P 500.

We merge these three data sets together to create our main dataframe: merged_df. Additionally, we create new columns to help us with our future analysis (like calculating the interest rate, the nominal/real net worth, etc.)

### Analysis
Finally, we plot a few different plots to help us answer the following questions:
1. How has the CPI evolved over time.
2. What is the difference between nominal and real net worth after investing for 40 years? In other words, how detrimental is inflation to an investor's long term bottom line.
3. How do 3 different investing strategies compare in the long run?


## Conclusion
Thank you for visiting my github page. If you have any questions or requests, feel free to reach out.
