# NYC Open *Big* Data
Author: Mark Bauer

# Introduction


# NYC Open Data Summary Statistics

| Metric              |      Value |
|:--------------------|-----------:|
| Number of datasets  |       2491 |
| Number of agencies  |        201 |
| Number of rows      | 5965739051 |
| Number of views     |   27761756 |
| Number of downloads |   11529518 |

Table xx: Overview metrics of NYC Open Data


![new-datasets.png](figures/new-datasets.png)
Figure xx: New Datasets per Year on NYC Open Data.


![agency-median-rows.png](figures/agency-median-rows.png)
Figure xx: Top 10 Agencies with the Highest Median Number of Rows per Dataset on NYC Open Data


![agency-sum-rows.png](figures/agency-sum-rows.png)
Figure xx: Top 10 Agencies with the Highest Total Number of Rows on NYC Open Data.


# Dataset Analysis

![central-tendency.png](figures/central-tendency.png)
Figure xx: .

## Dataset with the Highest Number of Rows on NYC Open Data
| id        | name                | attribution                     |   count_rows |   viewCount |   downloadCount |
|:----------|:--------------------|:--------------------------------|-------------:|------------:|----------------:|
| rmhc-afj9 | DSNY - PlowNYC Data | Department of Sanitation (DSNY) |    376404531 |        1854 |             504 |


## Top 10 Datasets with the Highest Number of Rows on NYC Open Data
![top-datasets.png](figures/top-datasets.png)


## Top 10 Datasets with the Highest Number of Rows on NYC Open Data (Excluding Taxi Data)
![top-no-taxi.png](figures/top-no-taxi.png)


## Top 10 Datasets with the Highest Number of Rows on NYC Open Data (Only Taxi Data)
![top-taxi-data.png](figures/top-taxi-data.png)


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