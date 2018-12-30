# Elo Merchant Challenge

### Description
Imagine being hungry in an unfamiliar part of town and getting restaurant recommendations served up, based on your personal preferences, at just the right moment. The recommendation comes with an attached discount from your credit card provider for a local place around the corner!

Right now, Elo, one of the largest payment brands in Brazil, has built partnerships with merchants in order to offer promotions or discounts to cardholders. But do these promotions work for either the consumer or the merchant? Do customers enjoy their experience? Do merchants see repeat business? Personalization is key.

Elo has built machine learning models to understand the most important aspects and preferences in their customers’ lifecycle, from food to shopping. But so far none of them is specifically tailored for an individual or profile. This is where you come in.

In this competition, Kagglers will develop algorithms to identify and serve the most relevant opportunities to individuals, by uncovering signal in customer loyalty. Your input will improve customers’ lives and help Elo reduce unwanted campaigns, to create the right experience for customers.

### Evaluation
Root Mean Squared Error (RMSE)
Submissions are scored on the root mean squared error. RMSE is defined as:
![alt text](https://cdn-images-1.medium.com/max/1600/1*9hQVcasuwx5ddq_s3MFCyw.gif)

where y hat is the predicted loyalty score for each card_id, and y is the actual loyalty score assigned to a card_id. Predictions will be made for those represented in **test.csv** and **sample_submission.csv**.

### Deadlines 
* **February 19, 2019** - Entry deadline. You must accept the competition rules before this date in order to compete.

* **February 19, 2019** - Team Merger deadline. This is the last day participants may join or merge teams.

* **February 19, 2019** - External Data Disclosure deadline. All external data used in the competition must be disclosed in the forums by this date.

* **February 26, 2019** - Final submission deadline.

All deadlines are at **11:59 PM UTC** on the corresponding day unless otherwise noted. The competition organizers reserve the right to update the contest timeline if they deem it necessary.

### Data
#### File descriptions
* **train.csv** - the training set
* **test.csv** - the test set
* **sample_submission.csv** - a sample submission file in the correct format - contains all card_ids you are expected to predict for.
* **historical_transactions.csv** - up to 3 months' worth of historical transactions for each card_id
* **merchants.csv** - additional information about all merchants / merchant_ids in the dataset.
* **new_merchant_transactions.csv** - two months' worth of data for each card_id containing ALL purchases that card_id made at merchant_ids that were not visited in the historical data.
