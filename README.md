# Final-Project-Tableau

## Project/Goals
Project/Goals
To better understand the relationship between Canadians and the real estate market, I have been asked to provide answers based on data retrieved from the Canadian Open Data Portal. These are specifically:

Weekly earnings from 1.1.2001 to 15.4.2015 (weekly_earnings - CSV)
Housing constructions from 1955 to 2019 (real_estate_numbers - CSV)
House prices from 1.1.2005 to 1.9.2020 (real_estate_prices - EXCEL)
Housing_price_index from November 1979 to September 2020
Office_realestate_index from November 1979 to September 2020
Consumer index from November 1979 to September 2020

## Process
Exploratory Analysis
Many of the files included irrelevant information too difficult to simply filter out in Tableau. Much of the work needed to be done in Excel for the spreadsheets and in Python for the JSON file, where for the JSON file the extracted data is in the "earnings" csv. Not all files in the data folder of the repository were used in Tableau

Providing Visualizations in Tableau
As an extension of exploratory analysis, the data needed to properly be visualized in Tableau, where certain transformations of the data became evident and the process continued back and forth between Tableau and excel, trying to find the best method to achieve calculated results.


## Results
Answering questions (Results)
Results (Option 1)
Show the trend of house prices across Canada in the last 40 years (table housing_price_index).
image

To determine which CPI index to use, they were both charted and I found the 2002 index to have the most data.

Compare the trend after 2005 with actual benchmark prices in table real_estate_prices to see if there are any differences.
image

Compare this trend with the trend of office prices. Which one is getting more expensive, faster?
image

Create a heatmap of Canada with current house prices for each available district.
image

Are the price differences between different districts increasing?
image

Compare the trend of house prices with earnings. Did Canadians spend more of their earnings in 2001 than they did in 2014?
image

Plot consumer_index together with housing_price_index and fit the regression line between them. Can we predict consumer_index from the housing_price_index?
image

## Challenges 
Challenges
Data transformation proved difficult in Tableau and some columns were ultimately calculated in Excel. This was in particular to single values like the the CAGR in the first question and the monthly earnings calculated from weekly earnings.

Geolocation data generated by Tableau does not include regions in Canada, only cities and provinces. Many of the "Regions" needed to be provided a set of latitude and longitude values manually to be properly charted in the Heatmap.

The domain knowledge required to understand the data was daunting at first. Much of the data cannot be related to each other as the units are not comparable and visualizations became too difficult to understand and scrapped.

Many of my peers chose the 2nd option for their project, most having tried the first option and unable to complete the project due to its difficultly. Ultimately, I took on the challenge and, to the best of my ability, delivered answers to as many questions I could. The questions were very specific, so a story or dashboard of multiple visualizations to show the exact same answer seemed unnecessary

## Future Goals
Further understand the data, which does require a certain degree of domain knowledge and experience.

Provide a dashboard and story unspecific to the questions asked, where and understanding of the relationship between Canadians and the real estate market could be expanded upon in ways such as by Region/Province and by the differences between types of real estate (not simply the composite).
