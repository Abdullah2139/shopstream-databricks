You are the data engineer at **ShopStream**, an e-commerce company that sells everything from mechanical keyboards to yoga mats. The company has two data problems that every real business eventually hits:

1. **Batch**: six months of historical orders, customers, and products sitting in CSV files that need to become clean, queryable tables.
2. **Streaming**: a live feed of new orders that lands as JSON events every few seconds and needs to flow into the same tables, continuously.

You will build the complete pipeline for both, on Databricks, for free. By the end you will have a working lakehouse with bronze, silver, and gold layers, a live dashboard, a streaming ingestion path with Auto Loader, one declarative Lakeflow pipeline that handles batch and streaming together, and a scheduled production job with task dependencies. Everything in this project runs on Databricks Free Edition.
