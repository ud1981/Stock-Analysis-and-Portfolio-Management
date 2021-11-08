# Stock-Analysis-and-Portfolio-Management
Business Analytics Capstone Project - Stock Analysis and Portfolio Management

There is a high profile client (Alexa) who is very conservative wrt investments and has shared the following lists of stocks where she would like to diversify her portfolio. These include: American Airlines, Apple Inc Ltd, Alaska Air, Amazon, Bausch Health, Credit Suisse, Deutsche Bank, Google, Goldman Sachs, Hawaiian Holdings, Johnson & Johnson, Merck & Co. This needs to be compared with returns from S&P 500 Index.
Requirements and financial objectives of client include:

Forming an NGO with her batchmates in sub-Sahara region after her schooling in US
She is supported emotionally by her family and has huge savings from the money sent by parents for daily expense till date
Shed is reserved, conservative, humble and leads a simple life. Hence, refused to take help from her parents to establish the NGO
Wants to invest money saved during her college to use the matured amount to fund her NGO
She is not eager to disclose any information regarding her investment amount
Wants to invest in stocks that show promise, but are also stable
Wants a comprehensive report on all metrics used to devise the investment strategy
Your task is to provide consultation to this high profile client based on her requirements and financial objectives.
You must use the elements of technical analysis to understand the trend of the underlying stocks. The metrics associated with risk and returns must help you realize whether the security meets the criteria of your investor’s financial goals.
You must use the metrics and the visualizations to compare the performance of the available securities against each other, and also against the market index, S&P500.
The findings should be aligned with the investor persona to select the appropriate stocks for the portfolio. You are expected to validate the same using the Capital Asset Pricing Model (CAPM) before including the stock in the portfolio.
After the selection of suitable stocks, you must apply a suitable predictive model to estimate the returns from the portfolio at the end of the investment period. You must check if the portfolio has the potential to fulfil the financial goals of the investor


--------------------------------------------------------------

Background: Why did I select this Capstone project?

It was most suitable for those working in an Investment Bank having a background of the Stock Market (i.e. Fundamental and Technical Analysis)

Skills required for this Capstone :

<A> Business Analyst skills needed for this project:
1. 5Ws and 1H: A deeper understanding of the 5Ws and How technique that is used for arriving at key insights from a business perspective
2. Business Objective: Once business objective is clear, the next step is to provide business solution
3. Business Solution: Share insight on Stock selection from the list of stocks and share comments on portfolio allocation
4. Data Storytelling: Share a video with your client (i.e. Alexa) on key recommendations. Logic used here - Tell them what you need to tell them, tell them and tell them what you told them.

<B> Technical skills needed for this project:

1. Programming is a necessity for any Analytical project. In this case Python was leveraged
2. Key insights derived using Data Science:
  
i) Data Cleaning: Once the historical information was derived from Yahoo Finance for all S&P 500 stocks and index unnecessary columns and missing data had to be dropped as part of Data cleaning
  
ii) Data Visualization: Visualizing the data as-is using box plots, sub-plots, heat maps
  
iii) Data Interpretation / Perform any Calculation: We calculated the Alpha and Volatility of the stocks versus benchmark index (i.e. S&P 500)
  
iv) Data Normalization: Since all stocks are mapped to different scales, we had to normalize them to a scale between 0 and 1 for comparing their performance on a standard scale
  
v) Data clustering: Bucket these stocks based on k-means algorithm
  
vi) Dimension Reduction using Principal Component Analysis (PCA) : Drop those features that are not adding value
  
vii) Calculate Sharpe ratio validate it using Capital Asset Pricing Model (CAPM)
