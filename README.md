# Accuracy-improvement-of-Textblob-based-on-Supervised-learning-method
TextBlob is a natural lnguage processing tool that can be used to analyze text for sentiment, but has trouble analyzing the texts for appstore-based reviews as Textblob is a NLP tool trained on movie reviews, which contain different features from app reviews. Therefore, it is advantageous to have an accurate sentiment analysis tool for the appstore based review domain. For this goal, we have manually labelled 2000 GooglePlay Store's review texts to build a training dataset, fed the dataset to Textblob classifier, and evaluated the new classifiers trained under two different models, 

- Naïve Bayes and 
- Decision Tree

In order to evaluate the new classifiers performed K-Fold cross validation with k = 10 folds to obtain performance metrics pertaining to accuracy, precision, recall, and f-measure. The decision tree model yielded highest mean accuracy (84%), the highest average precision (87%), and highest average recall (92%) compared to base and Naïve Bayes values.


In summary the contributions of this project include:

- Improved accuracy for app based reviews of NLP tool, Textblob
- Comparative analysis of existing sentiment analysis tool on app based review

 
    Base			                  Naïve Bayes			            Decision Tree	
Folds	  Acc.	Precision	Recall	    Acc.	Precision	Recall	    Acc.	Precision	Recall
1	      0.66	0.747	0.789	          0.84	0.852	0.927	          0.86	0.887	0.912
2	      0.74	0.827	0.827	          0.805	0.872	0.867	          0.84	0.887	0.899
3	      0.75	0.870	0.789	          0.755	0.810	0.870	          0.825	0.9	0.857
4	      0.64	0.851	0.687	          0.83	0.852	0.936	          0.84	0.8625	0.932
5	      0.62	0.780	0.697	          0.815	0.824	0.936	          0.84	0.851	0.936
6	      0.66	0.812	0.727	          0.83	0.853	0.924	          0.86	0.867	0.951
7	      0.66	0.8125	0.703	        0.795	0.821	0.917	          0.835	0.864	0.917
8	      0.66	0.777	0.776	          0.8	0.811	0.928	            0.82	0.832	0.928
9	      0.71	0.887	0.75	          0.775	0.814	0.907	          0.83	0.8625	0.92
10	    0.63	0.743	0.732	          0.825	0.8625	0.914	        0.82	0.862	0.907
Avg	    0.7015  078919	0.80309	    0.807	0.83711	0.91201	      0.837	0.867394	0.91606
F1		      0.79613			                0.87266			                0.89061	


Accuracy Comparison:

[https://github.com/nahida-uap/Accuracy-improvement-of-Textblob-based-on-Supervised-learning-method/blob/master/AccuracyComparison.png]


Precision Comparison:

[https://github.com/nahida-uap/Accuracy-improvement-of-Textblob-based-on-Supervised-learning-method/blob/master/PrecisionComparison.png]


Recall Comparison:

[https://github.com/nahida-uap/Accuracy-improvement-of-Textblob-based-on-Supervised-learning-method/blob/master/RecallComparison.png]
