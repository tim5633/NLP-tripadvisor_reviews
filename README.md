# NLP-tripadvisor_reviews
## Project Overview
Consider the [hotel_review.csv](https://github.com/simoneSantoni/NLP-orgs-markets/blob/b13e6442bbf5789da7f41fec21c0f6058fdc4681/sampleData/tripadvisorReviews/hotel_reviews.csv) file, containing 20,491 hotel reviews from Tripadvisor. Each row in the file is a review; the first column contains textual reviews; the second column contains ratings. By using topic modelling, We aimed to produce the features to train a classifier that adjudicates between ‘bad rating’ (e.g., 1 or 2 stars) and ‘good rating’ reviews (e.g., 4 or 5 stars).

## Using Gensim, Tomotopy, and PyTorch BERT to:
- explore competing topic models — i.e., models retaining a different number of topics
- select the most appropriate topic model (i.e. the best number of topics) given the nature of the task, which consists of creating the features to train a classifier
- motivate the choice for the best topic model



