# Exercise: Data Wrangler

Use AWS Data Wrangler to analyze the `yum-yum-ice-cream.csv` data. You'll notice this is the same data produced from Exercise 1.


Procedure for this exercise:
1. Launch the AWS Gateway.
2. Load `yum-yum-ice-cream.csv` to S3. Create a new bucket if you have not already done so.
3. Open up Sagemaker Studio.
4. Under the Launcher tab that is viewable when you first start Sagemaker Studio, click and create the Data Wrangler flow.
5. Transform the `date` field to have `year`, `month`, and `day` as their own features.
6. Create a visualization of the features using `Table Summary`.
7. Create a visualization of the features using `Histogram`.
8. Save the results by exporting to S3.


## AWS Tools
1. Data Wrangler
2. S3
3. Sagemaker Processing Job