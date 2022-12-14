# Apache Spark: Model building

Now that we've had some practice building models in Apache Spark, it's time to put your skills to the test!

Using the `datasets/Heart.csv` dataset (credit: ISLR), you will build a binary classification model to predict whether or not a patient has heart disease (`AHD`) given the following features:

- `Age`
- `Sex`
- `ChestPain`
- `RestBP`
- `Chol`
- `Fbs`
- `RestECG`
- `MaxHR`
- `ExAng`
- `Oldpeak`
- `Slope`
- `Ca`
- `Thal`

## Data cleaning
1. Your target column (`AHD`) needs to be run through a `StringIndexer`.
2. `ChestPain` and `Thal` need to be run through a `StringIndexer` **and** a `OneHotEncoder` NOTE: You only need one instance of `OneHotEncoder` for both columns


## Train/Test split
1. Split the data into an 80/20 train/test split. Use **42** as your seed for consistency.
2. Paste your best accuracy score from the test set below

**REPLACE THIS WITH YOUR ACCURACY SCORE**

## Publish your notebook
You're going to publish your notebook rather than submitting it in this repo. In DataBricks, select File > Publish and submit your URL to Google Classroom


https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/1379035776332576/1755578770825698/6489547681152576/latest.html