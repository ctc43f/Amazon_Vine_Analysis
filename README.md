Note: the CSV file for the vine_table was too large to upload to Github so I have zipped it and added it to the repository.

# Amazon Vine Analysis
## Overview of the Analysis
We are trying to determine if there is a positivity bias in reviews left on Amazon when the person reviewing the product has been paid by the manufacturer or distributor versus those reviews left by regular consumers purchasing the same products.  You would expect those with a financial interest to be less inclined to criticize a product they were paid to review.  We can compare the summary statistics of the paid and unpaid reviews to look for a significant difference.

For this analysis, I used the sample data set from Amazon on video games.

## Results

### Question 1: How many Vine and non-Vine reviews were there?
Vine reviews:

![Vine Reviews](/Resources/paid_review_count.png)

non-Vine reviews:

![non-Vine Reviews](/Resources/unpaid_review_count.png)

Of the 40,565 total reviews, 94 (0.2%) were Vine reviews.

### Question 2: How many of each type of review were 5 stars?

Vine review summary:

![Vine Review Summary](/Resources/paid_reviews_summary.PNG)

non-Vine review summary:

![non-Vine Review Summary](/Resources/unpaid_reviews_summary.png)

There were 48 5-star Vine reviews versus 15,663 5-star non-Vine reviews.  This metric isn't useful because the population size of both is so disproportionate.  Looking at percentage of total is more useful.

### Question 3: What percentage of reviews of each type were 5-star?

Vine review summary:

![Vine Review Summary](/Resources/paid_reviews_summary.PNG)

non-Vine review summary:

![non-Vine Review Summary](/Resources/unpaid_reviews_summary.png)

51% of Vine reviews were 5-star versus 39% of non-Vine reviews being 5-star.  What is even more telling is that only 1% of Vine reviews give a 1-star rating versus 25% of non-Vine reviews.  It implies paid reviewers either are never exposed to bad products OR that they are inclined to never provide any negative feedback.

