**INTRODUCTION.**

This project is an analysis on world's top 2000 companies ranked by Fortune. It statitiscally analyzes the companies by country, continent, Return on investments, finds correlation between variables,
separates profitable companies from non-profitable and performs a regression analysis in an attempt to predict value of assets based on variance in sales and profits.

The dataset was sourced from Kaggle.

**BODY**

The dataset has the following fields:
1. Company-The name of the Company
2. Sales ($billion)-total sales in the year 2020
3. Profits ($billion)
4. Assets ($billion)
5. Market Value ($billion)-perceived market value by investors in the year 2020
6. Country-home country of the company(where it was incorporated)
7. Continent
8. Latitude
9. Longitude
10. Expenses ($billion)
11. ROI-profit ratio of the companies that year
12. category-the companies grouped into profitable and non-profitable.Profitability being they had an ROI > 1

**STATISTICAL OPERATIONS CARRIED OUT**

1. Correlations-to establish inter-dependency between variables
2. Regression Analysis-establishes what proportion in variance of asset_value is affected by a change in one variable holding another constant to establish predictability
3. Profit ratio-establishes what ROI was achieved by individual companies 
4. Hypothesis-establishes if average sales in N.America are significantly different from Asia

**INSIGHTS**

1. There are 166 non-profitable companies and 1758 profitable companies in the dataset
2. The USA has the largest share of profitable companies followed by Japan then China.
3. Profitable countries in USA have a large count than non-profitable ones.
4. Europe has the largest count of non-profitable companies
5. Japan has the largest share of profitable companies in Asia.
6. S.Africa has the largest share of profitable companies in Africa
7. Profits and Market_Value have a significant positive relationship, when one goes up so does the other significantly.
8. Sales and Profits do have a significant positive relationship as well, when one goes up so does the other significantly.
9. Apple had the largest market value in the dataset
10. GPT Group a REIT in Austaralia, was the most profitable company
11. Global Logistic Properties(Logistics & Investments) was the most profitable company  in Asia, Yahoo(Tech) in N.America, Unibail-Rodamco(a REIT) in Europe, Exxaro Resources(Coal producers)	in Africa.
12. REITS seem to be more profitable than other sectors(from observation)
13. Average sales between Asia and N.America do not differ significantly.
14. Sales and profits are significant predictors of assets
15. On average, For every 1 billion dollar increase in sales, the assets will increase approximately by $ 1.6781 billion, holding profits constant
16. On average, For every 1 billion dollar increase in profits, assets will increase approximately by $ 17.14 billion, holding sales constant
17. Only about 15% of variation in assets can be explained via a change in sales and profits, meaning other unmeasured factors play a significant part.
18. Assets will have an estimated constant value of $ 26.16 billion when both sales and profits are zero.
