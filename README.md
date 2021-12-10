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

From the following table, we can observe the statistics for the temperature in the months of January and December.

<img width="716" alt="Screen Shot 2021-12-09 at 11 03 39 PM" src="https://user-images.githubusercontent.com/91294352/145515439-c423f498-60dc-46c1-a975-3db0f2f53190.png">

a) The December temperatures seem to be more variable than those in June.
b) The average recorded temperature in June is about 75 degrees F, nearly 4 degrees higher than the average temperature in December.
c) The median temperature in December is more inline with the average, and there are not many outliers skewing the average temperature higher or lower than the actual recorded frequency.

## 3) SUMMARY:

Even though the temperatures recorded in December seem to vary more than those of June, December would still provide appropriate weather conditions for both surfing and demand in ice cream. We cannot stick on to the temperature factor alone to make a decision.

Additional query can be done as follows:

*STATION vs TEMPERATURE FOR THE MONTHS OF JUNE AND DECEMBER:

<img width="248" alt="Screen Shot 2021-12-09 at 11 13 33 PM" src="https://user-images.githubusercontent.com/91294352/145516250-e2cb77b2-a278-4a5c-9d17-5cb4c5a72793.png"> <img width="231" alt="Screen Shot 2021-12-09 at 11 13 42 PM" src="https://user-images.githubusercontent.com/91294352/145516368-7bf9cc0d-0c75-4a81-9c13-3238f40d5cff.png">

A) The summary statistics of temperatures recorded by station for each month can help us to determine where in Oahu to build the shop. By comparing the variances in temperatures and the frequencies recorded, we can narrow our results on an desired location.

B) Other climatic conditions including precipitation, wind, wave tides are the other factors that should be taken into our consideration while featuring  the optimal location for the shop. We cannot stick on to the temperature factor alone to make a decision.







