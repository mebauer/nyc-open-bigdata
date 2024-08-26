# NYC Open *Big* Data
Author: Mark Bauer

# Introduction


# NYC Open Data Summary Statistics

| Metric              | Value         |
|:--------------------|:--------------|
| Number of datasets  | 2,491         |
| Number of agencies  | 201           |
| Number of rows      | 5,965,739,051 |
| Number of views     | 27,761,756    |
| Number of downloads | 11,529,518    |

Table xx: Summary statistics of NYC Open Data.


![agency-sum-rows.png](figures/agency-sum-rows.png)
Figure xx: Top 10 Agencies by Total Number of Rows on NYC Open Data.



![agency-median-rows.png](figures/agency-median-rows.png)
Figure xx: Top 10 Agencies by Median Number of Rows per Dataset on NYC Open Data.



![boxplot.png](figures/boxplot.png)
Figure xx: Boxplot of Download Counts by Number of Rows on NYC Open Data.



![central-tendency.png](figures/central-tendency.png)
Figure xx: Average Download Count with Error Bars on NYC Open Data.

# Dataset Analysis

| id        | name                | attribution                     |   count_rows |   viewCount |   downloadCount |
|:----------|:--------------------|:--------------------------------|-------------:|------------:|----------------:|
| rmhc-afj9 | DSNY - PlowNYC Data | Department of Sanitation (DSNY) |    376404531 |        1854 |             504 |

Table xx: Dataset with the Highest Number of Rows on NYC Open Data.


![top-datasets.png](figures/top-datasets.png)
Figure xx: Top 10 Datasets with the Highest Number of Rows on NYC Open Data.


![top-no-taxi.png](figures/top-no-taxi.png)
Figure xx: Top 10 Datasets with the Highest Number of Rows on NYC Open Data (Excluding Taxi Data).


![top-taxi-data.png](figures/top-taxi-data.png)
Figure xx: Top 10 Datasets with the Highest Number of Rows on NYC Open Data (Only Taxi Data).


# Code 
- The code to calculate count of rows for each dataset is located in the [data-export.ipynb](https://github.com/mebauer/nyc-open-bigdata/blob/main/data-export.ipynb) notebook.
- Brief data cleaning before the analysis can be found in the [data-cleaning.ipynb](https://github.com/mebauer/nyc-open-bigdata/blob/main/data-cleaning.ipynb) notebook.
- The code to generate the figures can be found in the [analysis.ipynb](https://github.com/mebauer/nyc-open-bigdata/blob/main/analysis.ipynb) notebook.

# Data
Data was retrieved from [NYC Open Data](https://opendata.cityofnewyork.us/).

# Say Hello!
Feel free to reach out.
- LinkedIn: [markebauer](https://www.linkedin.com/in/markebauer/)   
- Portfolio: [mebauer.github.io](https://mebauer.github.io/)
- GitHub: [mebauer](https://github.com/mebauer)
