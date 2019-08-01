# Airbnb Prices in Amsterdam: Data Analysis

### Project motivation

The aim of this project is to analyze prices of Airbnb listings in Amsterdam, focusing primarily on comparing average prices (per person per night) in different city districts, and trying to identify value-adding features that might be interesting to the visitors of Amsterdam.

The analysis provides a general overview of the Airbnb market in Amsterdam, answering questions such as where to stay if travelling on budget, or how large is the premium for more central apartments. By using text processing techniques I also analyze guest reviews to find out which parts of the city the visitors think are well-located. For each Amsterdam neighborhood I calculate the percentage of reviews that include positive comments about the location, and then analyze if such statistics are in line with the price differences observed. Through this analysis I also aim to identify districts that are under or over priced given their location.

Location is one of the main factors impacting Airbnb prices, but on the level of individual listings there are obviously several other differentiating aspects. In the last part of my analysis I aim to identify features that add value to Airbnb apartments, by analyzing the information contained in listings’ textual descriptions. I answer questions such as how much extra on average one needs to pay if an apartment is advertised as luxurious, spacious, cosy, modern, etc., or how large is the premium for having a garden or a terrace, or very specific to Amsterdam, how much more expensive it is to stay just next to a canal, or on it, in a houseboat.

In summary, my analysis consists of 3 parts:
- compare average price per person per night between different neighborhoods in Amsterdam;
- analyze whether the average prices in Amsterdam neigborhoods are correlated with the ratio of positive location reviews;
- find out how much extra one needs to pay on average for an apartment advertised (in the Airbnb title) as luxurious, spacious, modern, having a garden, being close to a canal, being a houseboat etc.

### File Descriptions:
- The analysis was performed using Airbnb datasets that are publically available on the following website http://insideairbnb.com/get-the-data.html. The `listings` dataframe includes detailed data of all listings in Amsterdam, and the `review` dataframe collects the guest reviews. According to the website, both datasets have been compiled on July 8, 2019.

- Airbnb Prices in Amsterdam.ipynb: Jupyter notebook with the project code, as well as all analyses, visualizations and conclusions

### Summary of results:
The results of the analysis are best presented in the Medium article [link](https://medium.com/@lukazaplotnik/where-to-stay-in-amsterdam-airbnb-data-analysis-2b673758885e).
