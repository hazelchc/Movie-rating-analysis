# An Honor or a Curse? Effect of Winning Awards on the Evaluation of Movies’ Quality

### Project Abstract
I would like to test whether an increase in status affects the evaluation of quality following the announcement of the award. In this project, I would like to know whether the perceived quality of an Oscar-winning movie changes after the announcement of the award. Leveraging the rich resources on IMDB, I collected all reviews three months before and after the Oscars Award announcement of both winning and nominated-only movies from 2008 to 2019. The results from difference-in-differences analyses show that although both nominated-only and award-winning films have lower ratings after the award announcement, the ratings of award-winning movies experience a sharper decrease.

### Details to replicate the research:
The code is written in Python 3.9.7 and all of its dependencies can be installed by running the following in the terminal (with the requirements.txt file included in this repository):
```
pip install -r requirements.txt
```

1. Data collection 
- The code for scraping IMDB links and reviews for all movies can be found in [crawler.ipynb](https://github.com/hazelchc/Project/blob/main/crawler.ipynb) . Running the code will produce [reviews.csv](https://uchicagoedu-my.sharepoint.com/:x:/g/personal/hazelchui_uchicago_edu/Eb0jEbeHjmZOsIdAMiBb_rcBjPIAtlaBR8F_QuQt6_bMDw?e=9cW7k1).

2. Data cleaning
- The code for cleaning (formatting movie names, handling missing data, constructing pre/post period, counting review number, and merging) the scraped data can be found in [data_cleaning.ipynb](https://github.com/hazelchc/Project/blob/main/data_cleaning.ipynb). Running the code will produce [final_decomp_2.csv](https://uchicagoedu-my.sharepoint.com/:x:/g/personal/hazelchui_uchicago_edu/EYHkT9HcPmVChhTDk3ov4RYBvDRUCoiRVqtHV6-8kRkMxQ?e=NmpWrs).

3. Regression analysis 
- Running the [regression.ipynb](https://github.com/hazelchc/Project/blob/main/regression.ipynb) will generate the regression results.

### How to cite the replication materials 
Chui, H., An Honor or a Curse? Effect of Winning Awards on the Evaluation of Movies’ Quality, (2022), GitHub repository, https://github.com/macs30200-s22/replication-materials-hazelchc.git
