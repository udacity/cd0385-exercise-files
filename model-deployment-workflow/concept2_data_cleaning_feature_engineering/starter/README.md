# Exercise: Data Cleansing and Feature Engineering

In this exercise, we'll be loading in a dataset that has some problems. In order for us to get it ready for our models, we will apply some of the technics we learned.

Apply these changes to the `data.csv` dataset.
1. Load `data.csv` into a dataframe.
2. Output the table info to see if there are any null values.
3. Remove all null values from the dataframe.
4. Change the `date` column from an object to a `datetime64[ns]` type.
5. Change the `weather` column to a category type.
6. One hot encode the `date` column to year, month, and day.
7. Normalized the columns from the `all_features` list so each feature has a zero mean.
8. Create and save the cleaned dataframe, as well as the train/validation/test dataframes to CSV.