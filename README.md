# Project demo: An Honor or a Curse? Effect of Winning Awards on the Evaluation of Movies’ Quality

The code is written in Python 3.9.7 and all of its dependencies can be installed by running the following in the terminal (with the requirements.txt file included in this repository):
```
pip install -r requirements.txt
```

### Introduction to the research
In this project, I would like to test whether an increase in status affects the evaluation of quality following the announcement of the award. I am using the difference-in-difference (DD) approach to compare changes in movie ratings over time between movies that won the award and the control movies that were nominated for the same award.

### Details to replicate the findings:
1. Data collection 
- The code for scraping IMDB links and reviews for all movies can be found in [crawler.ipynb](https://github.com/macs30200-s22/replication-materials-hazelchc/blob/main/crawler.ipynb) . Running the code will produce [reviews.csv](https://uchicagoedu-my.sharepoint.com/:x:/g/personal/hazelchui_uchicago_edu/Eb0jEbeHjmZOsIdAMiBb_rcBjPIAtlaBR8F_QuQt6_bMDw?e=9cW7k1).

2. Data cleaning
- The code for cleaning (formatting movie names, handling missing data, constructing pre/post period, counting review number, and merging) the scraped data can be found in [data_cleaning.ipynb](https://github.com/macs30200-s22/replication-materials-hazelchc/blob/main/data_cleaning.ipynb). Running the code will produce [final_decomp_2.csv](https://uchicagoedu-my.sharepoint.com/:x:/g/personal/hazelchui_uchicago_edu/EYHkT9HcPmVChhTDk3ov4RYBvDRUCoiRVqtHV6-8kRkMxQ?e=NmpWrs).

3. Regression analysis 
- Running the [regression.ipynb](https://github.com/macs30200-s22/replication-materials-hazelchc/blob/main/regression.ipynb) will generate the regression table as shown above.

### How to cite the replication materials 
Chui, H., An Honor or a Curse? Effect of Winning Awards on the Evaluation of Movies’ Quality, (2022), GitHub repository, https://github.com/macs30200-s22/replication-materials-hazelchc.git
