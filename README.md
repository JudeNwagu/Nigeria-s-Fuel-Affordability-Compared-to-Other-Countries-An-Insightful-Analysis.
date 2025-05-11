# Nigeria-s-Fuel-Affordability-Compared-to-Other-Countries-An-Insightful-Analysis.

![Alt Text](https://github.com/judoski366/Nigeria-s-Fuel-Affordability-Compared-to-Other-Countries-An-Insightful-Analysis./blob/main/oil%20price.jpg)

---
## Table Of Content
 - [Introduction](#Introduction)
 - [ASK](#ASK)
 - [PREPARE](#PREPARE)
 - [PROCESS](#PROCESS)
 - [ANALYZE](#ANALYZE)
 - [SHARE](#SHARE)
 - [ACT](#ACT)


## Introduction
Nigeria, known as the “Giant of Africa” and a major oil-producing nation, is currently experiencing the impact of rising fuel prices. Many Nigerians are feeling the strain of increasing fuel costs as global prices fluctuate. This has led to questions about how fuel affordability in Nigeria compares to other countries and the real-life implications for individuals and the overall economy.

Picture being able to fill up your tank without worrying about the cost. While this is a reality in some countries, for others, high fuel prices are a significant burden. So, where does Nigeria fit into this global fuel economy?

In this analysis, we will take a closer look at Nigeria’s fuel pricing and minimum wage, compare it with other countries, and examine the economic effects this has on everyday Nigerians.

As a data analyst, I leveraged the six stages of data analysis to uncover the broader picture of fuel affordability and its economic impact in nigeria across Selected countries. Here’s how I applied each stage

---

## ASK
### Project Objectives
- This project aims to understand how fuel affordability impacts the economic well-being of citizens, particularly in oil-producing versus non-oil-producing nations.
- To focused on examining the relationship between minimum wage, fuel prices, and the number of working hours needed to afford a liter of petrol.


---

## PREPARE
### Data Collection:

The data for this project was obtained from Global Petrol Prices for the cost of petrol and Trading Economics for minimum wage data of all countries used in this project. The Excel file contains 16 rows and 12 columns, which include the following:

- Country: This column lists the names of the countries included in the dataset and serves as the primary identifier for comparing various economic and labor metrics across different nations.
- Average Working Hours (Weekly): This indicates the average number of hours that individuals work in a week within each country, providing insight into labor patterns and work-life balance.
- Average Working Hours (Monthly): This shows the average total working hours per month, derived from the weekly average multiplied by the number of weeks in a month, helping to understand the overall workload of individuals monthly.
- Monthly Wage ($): This column lists the average monthly earnings of workers in each country, expressed in US dollars.
- Average Hourly Wage ($): This represents the average earnings per hour of work in each country, calculated by dividing the monthly wage by the average number of working hours in that month, providing insights into the labor market and compensation structure.
- Monthly Wage (N): This displays the average monthly wage expressed in Nigerian Naira, allowing for analysis of wage levels in the context of Nigeria’s economy.
- Average Hourly Wage (N): This indicates the average hourly wage in Nigerian Naira, derived from the monthly wage (N) divided by the average monthly working hours, helping in understanding the hourly earning potential in the local currency.
- Cost of Petrol/Liter ($): This shows the price of petrol per liter in US dollars, providing insight into fuel affordability and economic conditions.
- Cost of Petrol/Liter (N): This lists the cost of petrol per liter expressed in Nigerian Naira, allowing for localized analysis of fuel costs in Nigeria and understanding the economic burden of fuel prices on consumers.
- Petrol Liter/HMW (Hours of Minimum Wage): This indicates the number of liters of petrol that can be purchased with one hour of minimum wage earnings, serving as a measure of fuel affordability relative to income.
- Hours of Work Needed to Buy 1 Liter: This shows the average number of hours a worker must work to afford a single liter of petrol, highlighting the economic strain of fuel costs on individuals and assessing the impact of fuel prices on quality of life.
- Liters by Hourly Wage: This calculates how many liters of petrol can be purchased with one hour of work based on the average hourly wage, offering a direct comparison of fuel affordability across different countries in relation to income.


---
## PROCESS
### Data Transformation:

I used Microsoft Excel and Tableau to work with the data. In Excel, I used formulas to calculate the average monthly working hours, average hourly wage, cost of petrol per liter, and petrol liters per hour. I transformed the data by converting hourly wages into a format that allowed for easy comparison between countries in terms of work hours required to buy a liter of fuel. Additionally, I ensured that each dataset was transformed into the appropriate data type for analysis before importing it into Tableau for visualization.


---
## ANALYZE
### Data Exploration: 
Using statistical analysis and visualization tools, I explored how fuel affordability, minimum wage, and working hours vary between oil-producing and non-oil-producing countries.

### Key Insight
In analyzing fuel affordability across various nations, it becomes evident that Nigeria faces a unique challenge despite its status as Africa’s largest oil producer and a member of OPEC.

- Minimum Wage and Fuel Price Disparity:
The majority of countries in this dataset have a minimum wage above ₦100,000. However, Nigeria, along with Cameroon, Angola, and Ghana, falls below this threshold. This is concerning for Nigeria, an oil-producing nation, as its minimum wage remains under ₦100,000, while the cost of fuel per liter is ₦770 — higher than in other oil-rich nations like Iran, Libya, and the UAE, where fuel is more affordable.

![iamge alt text](https://github.com/judoski366/Nigeria-s-Fuel-Affordability-Compared-to-Other-Countries-An-Insightful-Analysis./blob/main/Minimum%20Wage.PNG)

- Fuel Affordability Per Liter and Hourly Minimum Wage:
Oil-producing countries such as Libya, Iran, UAE, and Algeria are leading in fuel affordability. Libya allows 63 liters of petrol per hour of minimum wage, followed by Iran (29 liters), UAE (28 liters), and Algeria (2 liters). Government subsidies help keep fuel prices low for citizens in these nations. Non-OPEC countries like the UK, Canada, and the US also demonstrate strong fuel affordability, with 8 liters per hour in the UK and Canada, and 7 liters in the US, despite higher fuel prices. On the lower end, China, Angola, South Africa, and Nigeria only offer 1 liter of fuel per hour of minimum wage, with Nigeria lagging behind due to high fuel prices and low wages, indicating the need for policy reforms to improve affordability and economic resilience.

![image alt text](https://github.com/judoski366/Nigeria-s-Fuel-Affordability-Compared-to-Other-Countries-An-Insightful-Analysis./blob/main/per%20liter%20cost.PNG)

- Fuel Affordability and Working Hours:
A closer look at fuel affordability in terms of the hours of work required to buy a liter of petrol reveals that Nigerians must work 1 hour and 45 minutes to afford a liter of petrol. This is significantly higher than other oil-producing countries like Libya (1 minute), Iran (2 minutes), and the UAE (2 minutes). Even non-oil-producing countries like the UK (7 minutes), Canada (7 minutes), and the USA (8 minutes) show a more favorable affordability ratio than Nigeria, despite their higher fuel prices.

![image alt text](https://github.com/judoski366/Nigeria-s-Fuel-Affordability-Compared-to-Other-Countries-An-Insightful-Analysis./blob/main/Hourly%20work%20needed.PNG)

- Economic Resilience and Consumer Burden:
In countries like the UK, US, and Canada, the combination of higher minimum wages and better economic structures ensures that citizens face less strain from fuel costs. In contrast, Nigeria’s high fuel prices coupled with low wages place a significant burden on its citizens, reducing economic resilience and purchasing power.


---
## SHARE
### Dashboard Creation: 
I created a Tableau dashboard to display comparative charts on fuel prices, work hours required, and minimum wages across different nations. The dashboard emphasized Nigeria’s high fuel costs despite being an oil-producing country.
Data Storytelling: I also included concise insights, interactive KPIs, and explanatory notes to help stakeholders understand the economic impact of fuel affordability in various regions.

![image alt text](https://github.com/judoski366/Nigeria-s-Fuel-Affordability-Compared-to-Other-Countries-An-Insightful-Analysis./blob/main/Dashboard%201%20(15).png)


---
## ACT
### Recommendations: 
- Based on the analysis, I recommended policy actions such as reviewing Nigeria’s fuel subsidy program and exploring ways to better align fuel prices with wages to reduce the burden on citizens.
- Business Impact: The insights could influence decisions related to energy policy, economic planning, and future fuel subsidy reforms in oil-producing countries.

### Conclusion
The analysis shows a significant difference in fuel affordability between oil-producing and non-oil-producing countries. Countries like Libya, Iran, UAE, and Algeria benefit from government subsidies, making fuel more affordable for their citizens. On the other hand Nigeria, despite being a major oil producer, faces challenges with high fuel costs and low wages. Non-OPEC nations such as the UK, US, and Canada have better affordability due to higher minimum wages, even with higher fuel prices. This emphasizes the urgent need for policy reforms in Nigeria, such as wage adjustments or fuel subsidies, to reduce the financial burden on its citizens and enhance overall economic resilience.

Thank you for taking the time to read my analysis! I truly appreciate your interest and support. If you’d like to stay connected and explore more insights or collaborate, feel free to connect with me on my - [LinkedIn](https://www.linkedin.com/in/nwagu-jude/), [Twitter/X](https://x.com/@jcndata). Your engagement means a lot, and I look forward to sharing more valuable content with you

