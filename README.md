## Movies-sentiment-analysis
The growing flow of content hosted on the Internet provides a great text resources collection. It's a place where people share their experiences, highlight their thoughts (and frustrations) or talk about anything. Such a diverse amount of data sources available creates opportunities for automatic extraction and content analysis. For example, the customers' attitude to the product analysis requires a clear understanding of how the client thinks. Keywords and phrases commonly used in service conversations with customers can give an idea about the product or brand helpful for the business. 
Before trying to classify sentiments, we must, first, ask what they mean. In general, it states that sentiments are the emotions or judgments or ideas evoked or colored by emotions. For this time we are interested in finding out people's positive or negative opinions about films based on their feedback.
The input data of the model is a column of short movies texts reviews (previously pre-processed and converted into feature vectors). Every review is labeled as positive or negative. Then we use the method of the Naive Bayesian classifier - Multinomial Naive Bayes (MNB), which belongs to supervised methods of machine learning. 
As the model output, we get the predicted classification of responses according to positive or negative classes and determine how accurately the distribution of responses is. 
The used IMDb movies dataset is abvailable on kaggle:
```https://www.kaggle.com/lakshmi25npathi/sentiment-analysis-of-imdb-movie-reviews/data```

A summary of prediction results on a classification problem is presented with confusion matrix:
![confusion_matrix](confusion_matrix.png)
