**Home Sales Data Analysis with PySpark**

This project leverages SparkSQL to analyze home sales data and determine key metrics. You'll explore Spark's powerful features, such as temporary views, data partitioning, caching, and uncaching, to optimize queries and measure performance.

*Features*

Load and preprocess home sales data using PySpark.

Create and query temporary views to calculate:
Average prices for homes based on criteria (e.g., bedrooms, bathrooms, size, year built).

Metrics per "view" rating for homes with average prices ≥ $350,000.

Use partitioning and caching to optimize query performance.

Compare cached vs. uncached query runtimes.

Save and read the partitioned dataset in Parquet format.

_Query Key Metrics:_

* Average price for four-bedroom homes sold per year.

* Average price of homes with three bedrooms, three bathrooms for each year built.

* Average price of homes meeting specific criteria (e.g., size, floors) per year built.

* Average price of homes per "view" rating, filtered for prices ≥ $350,000.

_Performance Optimization:_

Cache and validate the home_sales table.

Measure and compare runtimes of queries on cached vs. uncached data.

Partition data by date_built and query the partitioned Parquet dataset.

_Cleanup:_

Uncache the home_sales table and verify.
