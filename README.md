# Big Data Homework - "Alexa, can you handle big data?"

### Before You Begin

1. Create a new repository for this project called `big-data-challenge`. **Do not add this homework to an existing repository**.

2. Clone the new repository to your computer.

3. Inside your local git repository, create a directory for the level of challenge Challenge you choose. Use folder names corresponding to the challenges: **level-1** or  **level-2**.

4. Download a Google Colab Notebook as a `ipynb` file and add it to this folder. This will be the main script to run for analysis. Be sure to also add any SQL queries you used to a `.sql` file and add it to your repo.

5. Push the above changes to GitHub or GitLab.


## Background

In this assignment you will put your ETL skills to the test. Many of Amazon's shoppers depend on product reviews to make a purchase. Amazon makes these datasets publicly available. However, they are quite large and can exceed the capacity of local machines to handle. One dataset alone contains over 1.5 million rows; with over 40 datasets, this can be quite taxing on the average local computer. Your first goal for this assignment will be to perform the ETL process completely in the cloud and upload a DataFrame to an RDS instance. The second goal will be to use PySpark or SQL to perform a statistical analysis of selected data.

There are two levels to this homework assignment. The second level is optional but highly recommended.

1. Create DataFrames to match production-ready tables from two big Amazon customer review datasets.
2. Analyze whether reviews from Amazon's Vine program are trustworthy.


* Summary analysis 
1. Created DataFrames to match the production-ready tables from two of the big Amazon customer review datasets.
2. For both of the ".ipynb files" - the schema text file for tables: customer, products, review_id and vine tables was populated.
3. Observations while performing statistical analysis on Amazons vine review process. The analysis did not detect any potential bias or any untrustworthy information pertaining to Vine membership.

