# Comparative_Study_of_Countries
Creating a dashboard to compare all the parameters for different countries, to strategize market penetration and to target new customers using Tableau.

# Datasets:

Primary Dataset – Insurance Sample Dataset

Secondary Dataset – Global Financial Development Database

Note: Use Data Blending with Relationships between Country Code, Country, and Year

# Steps to Perform: 

1. Create a geographic map showing the countries' fields. Color the map based on the income column from the secondary dataset.
    i. Include income group filter in the dashboard
2. Include a webpage to show data from the world bank webpage driven by an URL action from a geography graph
    i. The country names in the map will act as the trigger. https://en.wikipedia.org/wiki/Country
3. Create a KPI Table to show the comparison between the selected period and the period prior to the selected one
    i. Create two parameters for Year Selection and Category Selection
   ii. Category parameter includes life insurance share, market share, penetration, ratio of reinsurance accepted, and retention ratio.
  iii. Create a calculated field to calculate the Growth %
   iv. Create a table to show these values
    v. Title should be updated based on the category selection
4. Create Growth Indicator Shapes based on the Growth %
   i. Growth indicator displays Negative, No Change, and Positive as values and corresponding shapes against it
5. Create a trend line to show the selected category values
   i. The line shows an arrow or triangle at the last mark
6. Create a dashboard filter for income group to be applied for all charts with the filter action enabled in the map as well
7. Formatting should be done appropriately

![Comparative_Study_of_countries](https://github.com/ashwinijujare/Comparative_Study_of_Countries/assets/117963460/e55a10e7-736c-4787-8248-d81a1106c823)


# Link to Live Dashboard in Tableau Public
https://public.tableau.com/app/profile/ashwini.jujare/viz/ComparativeStudyofCountries_16754893526960/ComapartiveStudyofCountries?publish=yes
