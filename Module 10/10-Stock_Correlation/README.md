# Stock Correlation 

In this assignment, you will analyze the following five semiconductor stocks: `HD`, `INTC`, `AMD`, `MU`, `NVDA`, and `TSM`. Then, you will choose the stock with the least correlation to `JNJ` in order to diversify a portfolio. The data was generated using the [GOOGLEFINANCE](https://support.google.com/docs/answer/3093281?hl=en) historical market data script.

To learn more about diversification and how correlation in a portfolio helps to minimize risk, review this [article on diversification](https://www.investopedia.com/terms/d/diversification.asp).

## Instructions

1. Import the Pandas and Plotly Express libraries.

2. Read the CSV file into a DataFrame and set the date column as the index.

3. Use the `pct_change` function to calculate the daily returns.

4. Drop any rows with missing data.

5. Create a correlation matrix. 

6. Create a heatmap using the correlation matrix. 

7. Use the `unstack` function to find the best stock pair for diversification.

8. Based on the results, in a sentence, explain which semiconductor stock would be the best candidate to add to the existing portfolio and why.

## Grading Rubric

[Stock Correlation Rubric rubric](Stock_Correlation_Rubric.pdf)

---

© 2022 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
