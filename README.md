# Home_Sales_Analysis

## Overview

For this project I used SparkSQL to find key metrics about provided home sales data. Pyspark was used to create temporty views, partition data, cache and uncache temporary tables, and verified tables are uncached as well.

## Runtimes

### Uncached

![Uncached](https://github.com/pjgill010/Home_Sales_Analysis/assets/118948437/658017f8-d7e7-4ace-9036-c4bb212f6392)

### Cached

![Cached](https://github.com/pjgill010/Home_Sales_Analysis/assets/118948437/d4f71cf1-45bc-4296-8cdc-fb2cf185be85)

### Partitioned

![Partitioned](https://github.com/pjgill010/Home_Sales_Analysis/assets/118948437/f569de17-2e18-4d0f-9588-173d14d6f065)

## Results

Cached data outperformed uncached and partitioned data. Caching is optimal techique for this dataset optimzation. 


