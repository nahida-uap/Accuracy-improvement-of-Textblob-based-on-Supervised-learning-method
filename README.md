# Accuracy-improvement-of-Textblob-based-on-Supervised-learning-method
TextBlob is a natural lnguage processing tool that can be used to analyze text for sentiment, but has trouble analyzing the texts for appstore-based reviews as Textblob is a NLP tool trained on movie reviews, which contain different features from app reviews. Therefore, it is advantageous to have an accurate sentiment analysis tool for the appstore based review domain. For this goal, we have manually labelled 2000 GooglePlay Store's review texts to build a training dataset, fed the dataset to Textblob classifier, and evaluated the new classifiers trained under two different models, 

- Naïve Bayes and 
- Decision Tree

In order to evaluate the new classifiers performed K-Fold cross validation with k = 10 folds to obtain performance metrics pertaining to accuracy, precision, recall, and f-measure. The decision tree model yielded highest mean accuracy (84%), the highest average precision (87%), and highest average recall (92%) compared to base and Naïve Bayes values.


In summary the contributions of this project include:

- Improved accuracy for app based reviews of NLP tool, Textblob
- Comparative analysis of existing sentiment analysis tool on app based review

 
Results:

![result](https://github.com/nahida-uap/Accuracy-improvement-of-Textblob-based-on-Supervised-learning-method/blob/master/Comparison.png)


Accuracy Comparison:

![Accuracy](https://github.com/nahida-uap/Accuracy-improvement-of-Textblob-based-on-Supervised-learning-method/blob/master/AccuracyComparison.png)


Precision Comparison:

![Precision](https://github.com/nahida-uap/Accuracy-improvement-of-Textblob-based-on-Supervised-learning-method/blob/master/PrecisionComparison.png)


Recall Comparison:

![Recall](https://github.com/nahida-uap/Accuracy-improvement-of-Textblob-based-on-Supervised-learning-method/blob/master/RecallComparison.png)
