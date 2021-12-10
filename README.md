### Module-9-Surfs-Up-Weather-Analysis
SQLite

## 1) OVERVIEW OF THE ANALYSIS: 

This challenge focuses on the weather temperature in Oahu, Hawaii during the months of June and December, looking at different statistics between the two periods to help determine whether an ice cream/surf shop would have good weather conditions to operate.

SOURCES:

* Data Source: hawaii.sqlite 
* Programming Files: SurfsUp_Challenge.ipynb
* Data Tools: Python SQL toolkit (SQLAlchemy), Object Relational Mapper, Pandas, Numpy
* Software: SQLlite, Python 3.9.2, Flask, Jupyter Notebook

## 2) RESULTS:

From the following two tables, we can observe the statistics for the temperature in the months of January and December.

<img width="716" alt="Screen Shot 2021-12-09 at 11 03 39 PM" src="https://user-images.githubusercontent.com/91294352/145515439-c423f498-60dc-46c1-a975-3db0f2f53190.png">

a) The December temperatures seem to be more variable than those in June.
b) The average recorded temperature in June is about 75 degrees F, nearly 4 degrees higher than the average temperature in December.
c) The median temperature in December is more inline with the average, and there are not many outliers skewing the average temperature higher or lower than the actual recorded frequency.

## 3) SUMMARY:

Even though the temperatures recorded in December seem to vary more than those of June, December would still provide appropriate weather conditions for both surfing and demand in ice cream. We cannot stick on to the temperature factor alone to make a decision.

Additional query can be done as follows:

*STATION vs TEMPERATURE FOR THE MONTHS OF JUNE AND DECEMBER:

<img width="248" alt="Screen Shot 2021-12-09 at 11 13 33 PM" src="https://user-images.githubusercontent.com/91294352/145516250-e2cb77b2-a278-4a5c-9d17-5cb4c5a72793.png">







Average temperature between June and December is 75 and 71 degrees respectively, show a moderate temperature and very little fluctuation between the two periods from an average standpoint.
the maximum temperatures of 85 (June) and 83 (December) are also remarkable similar.
the minimum temperature of 56 (December) and 64 (June) show the greatest variance, and reflects a much lower temperature level in December that may not be conducive to ice cream or surfing. However, with standard deviations of 3.25 (June) and 3.74 (December) we would expect a little more variation in the december numbers.

For specificity, I would like to delve into the summary statistics of temperatures recorded by station for each month. This can help determine geopgraphically where in Oahu to build the prospective shop. By comparing the variances in temperatures and the frequencies recorded, we can narrow in on an optimal location.

Secondly, I would like to review other important variables that are correlated with optimal beach and surfing weather. Sunch varibles include precipitation, wave swells and wind condition. Though there may be some contrasting optimal conditions based on surfing vs sunbathing, it is important to identify those conditions and see how they correlate to foot traffic to the beach (depending on the time of year). It would be foolish to only value temperatures as the key indicator for opening a business.
