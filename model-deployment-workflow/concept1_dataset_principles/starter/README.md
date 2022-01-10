# Exercise: Dataset Principles

Since models are nothing without data, it's important to make sure the fundamentals are strong when creating and shaping your datasets. Here we'll create a regression dataset and split it into the three core dataset types: train, validation, and test.

Your tasks for this exercise are:
1. Create a dataframe with your features and target arrays from `make_regression`.
2. Create a 60% Train / 20% Validation / 20% Test dataset group using the `train_test_split` method.
3. Confirm the datasets are the correct size by outputing their shape.
4. Save the three datasets to CSV