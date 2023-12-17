# Comparison of Conversion Rates with A/B Testing for Bidding Methods

## Business Problem

Recently, Meta introduced a new bidding strategy named "average bidding" as an alternative to the existing "maximum
bidding" approach. A client has opted to test this new feature and wishes to conduct an A/B test to ascertain whether
average bidding produces a higher conversion rate compared to maximum bidding. The A/B test has been in progress for a
month and the client now awaits analysis of the results. The primary success metric for the client is the number of
purchases. Consequently, the emphasis for statistical testing should be on the purchase metric.

## Dataset Story

This dataset comprises information related to a company's website, encompassing details such as the quantity of ads
viewed and clicked by users, alongside revenue figures derived from these interactions. Two distinct datasets are
available, designated for the control and test groups, respectively. These datasets are organized on separate pages
within the spreadsheet file. Maximum bidding has been implemented for the control group, while the test group
is subjected to average bidding.

## Features

- `Impression` - Number of ad displays
- `Click` - Number of clicks on displayed ads
- `Purchase` - Number of products purchased following ad clicks
- `Earning` - Revenue generated from purchased products