# Warehouse Order Fulfillment Analysis

![Warehouse picture](https://images.unsplash.com/photo-1586528116311-ad8dd3c8310d?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80)

This Python script uses a BigQuery SQL query to analyze warehouse order fulfillment data and identify areas for improvement in warehouse operations. By calculating the number of orders fulfilled, a business can assess which warehouses are meeting fulfillment goals and which ones are falling short. This information can help increase customer satisfaction and revenue.

## Business Problem

Warehouse order fulfillment is a critical component of a business's success. Customers expect their orders to be delivered on time and in full. Failure to meet these expectations can result in dissatisfied customers and lost revenue. Inefficient warehouse operations can lead to longer fulfillment times and higher costs. It is essential to analyze warehouse order fulfillment data regularly to identify areas for improvement and optimize operations.

## How to Use

To use this script, follow these steps:

1. Install the required packages by running `pip install -r requirements.txt`.
2. Set up authentication for your Google Cloud account by following the instructions [here](https://cloud.google.com/docs/authentication/getting-started).
3. Update the `project_id` and `dataset_id` variables in `fulfillment_analysis.py` with your project and dataset IDs.
4. Run the script by running `python fulfillment_analysis.py`.
