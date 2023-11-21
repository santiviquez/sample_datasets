# Dataset Description
This dataset is a subset of the [The Multilingual Amazon Reviews Dataset](https://huggingface.co/datasets/amazon_reviews_multi) often use to becnhmark language translation ML models.


The present dataset was create to monitor a sentiment analysis prediction class. The details about the dataset subsampling, partitoning, and model can be found in the blog post [Are your NLP models deteriorating post-deployment? Let’s use unlabelled data to find out](https://huggingface.co/blog/santiviquez/performance-estimation-nlp-nannyml).

The reference set is used to establish a baselines for performance. And the analysis data is used to monitor the trained model's performance.

# List of variables is the dataset
* timestamp
* review_id
* product_id
* reviewer_id
* stars
* text
* review_title
* language
* product_category
* real_sentiment (*target*)
* negative_sentiment_pred_proba (*prediction score*)
* neutral_sentiment_pred_proba (*prediction score*)
* positive_sentiment_pred_proba (*prediction score*)
* predicted_sentiment (*prediction*)