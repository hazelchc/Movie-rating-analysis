# An Honor or a Curse? Effect of Winning Awards on the Evaluation of Movies’ Quality

### Project Abstract
****Goal:****

I would like to test whether an increase in status affects the evaluation of quality following the announcement of the award. In this project, I would like to know whether the perceived quality of an Oscar-winning movie changes after the announcement of the award. 

****Data & Methods:****

Leveraging the rich resources on IMDB, I collected all reviews (47,010 reviews in total) three months before and after the Oscars Award announcement of both winning and nominated-only movies from 2008 to 2019. I used the difference-in-difference (DD) approach to compare changes in ratings over time between movies that won the award and the control movies that were nominated for the same award.

****Results:**** 

The results showed that although both nominated-only and award-winning films have lower ratings after the award announcement, ****the ratings of award-winning movies experience a sharper decrease after the award ceremony****.

![image](https://user-images.githubusercontent.com/89876546/220253549-86af04fc-e4cb-4f0f-94fb-a70a953f790a.png)

### Details to replicate the research:
The code is written in Python 3.9.7 and all of its dependencies can be installed by running the following in the terminal (with the requirements.txt file included in this repository):
```
pip install -r requirements.txt
```

1. Data collection 
- The code for scraping IMDB links and reviews for all movies can be found in [crawler.ipynb](https://github.com/hazelchc/Project/blob/main/crawler.ipynb) . Running the code will produce [reviews.csv](https://uchicagoedu-my.sharepoint.com/:x:/g/personal/hazelchui_uchicago_edu/Eb0jEbeHjmZOsIdAMiBb_rcBjPIAtlaBR8F_QuQt6_bMDw?e=9cW7k1).

2. Data cleaning
- The code for cleaning (formatting movie names, handling missing data, constructing pre/post period, counting review number, and merging) the scraped data can be found in [data_cleaning.ipynb](https://github.com/hazelchc/Project/blob/main/data_cleaning.ipynb). Running the code will produce [final_decomp_2.csv](https://uchicagoedu-my.sharepoint.com/:x:/g/personal/hazelchui_uchicago_edu/EYHkT9HcPmVChhTDk3ov4RYBvDRUCoiRVqtHV6-8kRkMxQ?e=NmpWrs).

3. Regression analysis (Difference-in-Differences)
- Running the [regression.ipynb](https://github.com/hazelchc/Project/blob/main/regression.ipynb) will generate the regression results.

### How to cite the replication materials 
Chui, H., An Honor or a Curse? Effect of Winning Awards on the Evaluation of Movies’ Quality, (2022), GitHub repository, https://github.com/macs30200-s22/replication-materials-hazelchc.git
