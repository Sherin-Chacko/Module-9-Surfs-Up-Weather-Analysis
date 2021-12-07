### Module-9-Surfs-Up-Weather-Analysis
SQLite

## 1) OVERVIEW: 

This challenge focuses on the weather temperature in Oahu, Hawaii during the months of June and December, looking at different statistics between the two periods to help determine whether an ice cream/surf shop would have good weather conditions to operate.

SOURCES:

* Data Source: hawaii.sqlite 
* Programming Files: SurfsUp_Challenge.ipynb
* Data Tools: Python SQL toolkit (SQLAlchemy), Object Relational Mapper, Pandas, Numpy
* Software: SQLlite, Python 3.9.2, Flask, Jupyter Notebook

These two tables tell us about the differing weather patterns for the two monthly periods. Some takeaways:

Average temperature between June and December is 75 and 71 degrees respectively, show a moderate temperature and very little fluctuation between the two periods from an average standpoint.
the maximum temperatures of 85 (June) and 83 (December) are also remarkable similar.
the minimum temperature of 56 (December) and 64 (June) show the greatest variance, and reflects a much lower temperature level in December that may not be conducive to ice cream or surfing. However, with standard deviations of 3.25 (June) and 3.74 (December) we would expect a little more variation in the december numbers.

For specificity, I would like to delve into the summary statistics of temperatures recorded by station for each month. This can help determine geopgraphically where in Oahu to build the prospective shop. By comparing the variances in temperatures and the frequencies recorded, we can narrow in on an optimal location.

Secondly, I would like to review other important variables that are correlated with optimal beach and surfing weather. Sunch varibles include precipitation, wave swells and wind condition. Though there may be some contrasting optimal conditions based on surfing vs sunbathing, it is important to identify those conditions and see how they correlate to foot traffic to the beach (depending on the time of year). It would be foolish to only value temperatures as the key indicator for opening a business.
