# Final-Project-Tableau

## Project/Goals
Project/Goals
To understand the relationship between Canadians and Real estate market we have been provided some datasets to answer questions. These are following:

Weekly earnings from 1.1.2001 to 15.4.2015 (weekly_earnings - CSV)
Housing constructions from 1955 to 2019 (real_estate_numbers - CSV)
House prices from 1.1.2005 to 1.9.2020 (real_estate_prices - EXCEL)
Housing_price_index from November 1979 to September 2020
Office_realestate_index from November 1979 to September 2020
Consumer index from November 1979 to September 2020

## Process
Exploratory Analysis
Many files had to be filtered out as it contained information which was not germane to our topic. Much work was needed to be done on Excel for the spreadsheets and Python for the JSON file, where for the JSON file the extracted data is in the "earnings" csv. Not every file was used to extract and use data.

Providing Visualizations in Tableau
As continued process for explolatory analysis, data was analysed and visualized properly in tableau where transformations of data was done and the process was continued back and forth between tableau and excel. Tried to get the outcomes using best methods.


## Results
Answering questions (Results)
Results (Option 1)
Show the trend of house prices across Canada in the last 40 years (table housing_price_index).
![image](https://github.com/user-attachments/assets/66dbdca6-fe4b-4a34-8f0b-6fa2b0882f52)


To determine which CPI index to use, they were both charted and I found the 2002 index to have the most data.
![image](https://github.com/user-attachments/assets/448627d6-7b41-436b-af2e-db449cfa78cd)


Compare the trend after 2005 with actual benchmark prices in table real_estate_prices to see if there are any differences.
![image](https://github.com/user-attachments/assets/cad9b16b-fd3f-4e3e-b3ee-42d8faf29e42)


Compare this trend with the trend of office prices. Which one is getting more expensive, faster?
![image](https://github.com/user-attachments/assets/cad9b16b-fd3f-4e3e-b3ee-42d8faf29e42)

Create a heatmap of Canada with current house prices for each available district.
![image](https://github.com/user-attachments/assets/3ef52d79-1dfc-4701-919e-200281e21be4)


Are the price differences between different districts increasing?
![image](https://github.com/user-attachments/assets/1d8a1c8d-b02f-4b96-99cb-c2fb866e2cb0)


Compare the trend of house prices with earnings. Did Canadians spend more of their earnings in 2001 than they did in 2014?
![image](https://github.com/user-attachments/assets/a928d6a8-c4d3-47af-8d6f-684ec294eff8)


Plot consumer_index together with housing_price_index and fit the regression line between them. Can we predict consumer_index from the housing_price_index?
![image](https://github.com/user-attachments/assets/616a4737-0735-4936-b898-f5036d064906)


## Challenges 
Challenges
Data transformation was hard in Tableau and some columns were finally calculated in Excel. This was in particular to singular values like the CAGR(compound annual growth rate) in the first question and the monthly earnings calculated from weekly earnings.

Geolocation data generated by Tableau does not include regions in Canada, only cities and provinces. Many of the "Regions" needed to be provided a set of latitude and longitude values manually to be properly charted in the Heatmap.

The domain knowledge required to understand the data was very hard. Much of the data cannot be related to each other as the units cannot be collated and visualizations became too difficult to understand and were scrapped.


## Future Goals
Further understand the data, which does require a certain degree of domain knowledge and experience.

Provide a dashboard and story unspecific to the questions asked, where and understanding of the relationship between Canadians and the real estate market could be expanded upon in ways such as by Region/Province and by the differences between types of real estate (not simply the composite).
