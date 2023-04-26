# Warehouse Order Fulfillment Analysis

![Warehouse picture](https://img.freepik.com/free-photo/interior-large-distribution-warehouse-with-shelves-stacked-with-palettes-goods-ready-market_342744-1481.jpg?w=1380&t=st=1682543392~exp=1682543992~hmac=d2937ae5b1de59229633f87bc806531ff207216143f00ae6a5664d1a48acff29)

This Python script uses a BigQuery SQL query to analyze warehouse order fulfillment data and identify areas for improvement in warehouse operations. By calculating the number of orders fulfilled, a business can assess which warehouses are meeting fulfillment goals and which ones are falling short. This information can help increase customer satisfaction and revenue.

## Business Problem

Warehouse order fulfillment is a critical component of a business's success. Customers expect their orders to be delivered on time and in full. Failure to meet these expectations can result in dissatisfied customers and lost revenue. Inefficient warehouse operations can lead to longer fulfillment times and higher costs. It is essential to analyze warehouse order fulfillment data regularly to identify areas for improvement and optimize operations.

## How to Use

To use this script, follow these steps:

1. Install the required packages by running `pip install -r requirements.txt`.
2. Set up authentication for your Google Cloud account by following the instructions [here](https://cloud.google.com/docs/authentication/getting-started).
3. Update the `project_id` and `dataset_id` variables in `fulfillment_analysis.py` with your project and dataset IDs.
4. Run the script by running `python fulfillment_analysis.py`.
