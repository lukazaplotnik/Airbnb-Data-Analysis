# Airbnb Prices in Amsterdam: Data Analysis

### Installation
No additional libraries are needed to run the code beyond the Anaconda distribution of Python. There should be no issues running the code using Python versions 3.x

### Project motivation
The aim of this project is to analyze prices of Airbnb listings in Amsterdam, focusing primarily on comparing average prices (per person per night) in different city districts, and trying to identify value-adding features that might be interesting to the visitors of Amsterdam.

The analysis provides a general overview of the Airbnb market in Amsterdam, and can also serve as a guide to all future visitors, as it answers questions such as where to stay if travelling on budget, or how large is the premium for more central apartments. By using text processing techniques I also analyze guest reviews to find out which parts of the city the visitors think are well-located. For each Amsterdam neighborhood I calculate the percentage of reviews that include positive comments about the location, and then analyze if such statistics are in line with the price differences observed. Through this analysis I also aim to identify districts that are under or over priced given their location.

Location is one of the main factors impacting Airbnb prices, but on the level of individual listings there are obviously several other differentiating aspects. In the last part of my analysis I aim to identify features that add value to Airbnb apartments, by analyzing the information contained in listings’ textual descriptions. I answer questions such as how much extra on average one needs to pay if an apartment is advertised as luxurious, spacious, cosy, modern, etc., or how large is the premium for having a garden or a terrace, or very specific to Amsterdam, how much more expensive it is to stay just next to a canal, or on it, in a houseboat.

In summary, my analysis consists of 3 parts:
- compare average price per person per night between different neighborhoods in Amsterdam;
- analyze whether the average prices in Amsterdam neigborhoods are correlated with the ratio of positive location reviews;
- find out how much extra one needs to pay on average for an apartment advertised (in the Airbnb title) as luxurious, spacious, modern, having a garden, being close to a canal, being a houseboat etc.

### File Descriptions
The analysis was performed using [publicly available](http://insideairbnb.com/get-the-data.html) Airbnb datasets:
- `listings` dataset that includes detailed data of all listings in Amsterdam,
- and `reviews` dataset that collects all corresponding guest reviews since 2009.
According to the website, both datasets have been compiled on July 8, 2019.

Project code with all the analyses, visualizations and conclusions is stored in the Jupyter notebook (Airbnb Prices in Amsterdam.ipynb).

### Results
The results of the analysis are best presented in the accompanying [Medium article](https://medium.com/@lukazaplotnik/where-to-stay-in-amsterdam-airbnb-data-analysis-2b673758885e).

### Acknowledgments
Must give credit to [Inside Airbnb](http://insideairbnb.com/get-the-data.html) for the data. Inside Airbnb is an independent, non-commercial set of tools and data that allows you to explore how Airbnb is really being used in cities around the world. The data behind the Inside Airbnb site is sourced from publicly available information from the Airbnb site. The data has been analyzed, cleansed and aggregated where appropriate to facilitate public discussion. Read more disclaimers [here](http://insideairbnb.com/about.html#disclaimers). The data is shared to public for further analyses under a [Creative Commons CC0 1.0 Universal (CC0 1.0) "Public Domain Dedication"](https://creativecommons.org/publicdomain/zero/1.0/) license.
