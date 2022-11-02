# Amazon Vine Analysis

## Project Overview
Amazon Vine is an invitation-only program which selects the most insightful reviewers in the Amazon store to serve as Vine Voices. Vine Voices have the unique opportunity to order items free of charge and share their product experiences with Amazon customers to help them make informed buying decisions. We are tasked to analyze Amazon reviews written by Vine Voices to determine if having a paid Vine review makes a difference in 5-star reviews.

## Resources
+ Analysis Software: PySpark 3.1.3, Google Colab Notebook
+ Data: [Amazon AWS Reviews](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt) 
  + U.S. Reviews Dataset: Video Games

## Results

+ How many Vine reviews and non-Vine reviews were there?
  + Vine Reviews: 94
  + Non-Vine Reviews: 40471
![Screenshot (394)](https://user-images.githubusercontent.com/29410712/199115169-62d7311c-91e6-4c8b-a765-4512bc79081c.png)


+ How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  + Vine Reviews with 5-Stars: 48
  + Non-Vine Reviews with 5-Stars: 15663
![Screenshot (397)](https://user-images.githubusercontent.com/29410712/199116461-4af0297c-4343-4c25-b613-51409d5fdbe2.png)


+ What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  + Vine Reviews with 5-Stars: 51.06%
  + Non-Vine Reviews with 5-Stars: 38.70%
![Screenshot (398)](https://user-images.githubusercontent.com/29410712/199116544-3d072040-57e3-4716-899d-66d4730ca49b.png)

## Summary

+ Positivity Bias:
  + Based on this specific dataset of video game reviews, our analysis indicates that there are some bias towards 5-star reviews with the comparison of Vine reviews (paid) and Non-Vine reviews (unpaid). In the analysis above, the reviews that were paid for by Vine had a higher percentage of 5-star reviews than those that were not paid. 51.06% of the Vine reviews that were paid had 5-star ratings while only 38.70% of the Vine reviews that were not paid had 5-star ratings.
+ Additional Analysis:
  + Although there is some bias in video game Vine reviews, there could potentially be less bias in other categories. By doing additional analysis in other categories, it could help in determining if there bias in Vine reviews overall. One could run the same code for different categories to determine if each individual category has biases. 
