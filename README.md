# Amazon Review Analysis for JBL Charge 4 Speaker -Sentiment Analysis-NLP
 
 
 ## Introduction
 
In this project the reviews (ratings, review titles, review texts, color and number of comments) for the JBL Charge 4 Waterproof Portable Bluetooth Speaker have been obtained by scraping Amazon.com website. Then the data has been cleaned up and transformed, analyzed and visualized. Also the cleaned up data has been saved as a sqlite file. Machine Learning models Naive Bayes Multinominal Classifier and K-Nearing Neighbors have been employed to analyze the sentiment of the reviewers and predict how they have rated the product and if their review has received any feedback (comments).


## The Data

The data used in this project have been scraped from https://www.amazon.com/ and stored as a dataframe in pandas. The cleaned data has been then stored as a sqlite file.


## Tools Used

splinter and chromedriver.exe have been used for scraping. Python and its modules such as pandas, numpy, matplotlib, seaborn, etc have been used for analysis of the data. Also sklearn module of python has been used to create Naive Bayes Multinominal classifier and KNN machine learning models.

## Data Analysis and Visualizations

The rating distribution for the JBL Speaker in the dataset has been illustrated in the figure below.
<p align="center">
<img src="https://github.com/kavehamini/Amazon-Review-Analysis-JBL-Charge-4-Speaker-Sentiment-Analysis-NLP/blob/master/1.png" width="500" height="500">
</p>
As it can be observed, most of the reviewes have rated the product with 5 stars (awesome).

The figure below depicts that most of the reviews with good and awsome ratings have not received any comments (feedback).
<p align="center">
<img src="https://github.com/kavehamini/Amazon-Review-Analysis-JBL-Charge-4-Speaker-Sentiment-Analysis-NLP/blob/master/2.png" width="500" height="500">
</p>
In the figure below, number of each rating for each color of JBL Speaker has been shown. as it can be seen, most of theratings are 5 stars (awesome).
<p align="center">
<img src="https://github.com/kavehamini/Amazon-Review-Analysis-JBL-Charge-4-Speaker-Sentiment-Analysis-NLP/blob/master/3.png">
</p>
And in the next figure, the number of awesome (5star)/not awesome ratings for each color of JBL Speaker has been depicted.
<p align="center">
<img src="https://github.com/kavehamini/Amazon-Review-Analysis-JBL-Charge-4-Speaker-Sentiment-Analysis-NLP/blob/master/4.png">
</p>
The pie chart showing the distribution of colors of speakers in the dataset indicates that most of the speakers are black.
<p align="center">
<img src="https://github.com/kavehamini/Amazon-Review-Analysis-JBL-Charge-4-Speaker-Sentiment-Analysis-NLP/blob/master/5.png">
</p>
An Investigation of the length of the reviews for the JBL Speaker show that most of the satisfied buyers have left shorter reviews.
<p align="center">
<img src="https://github.com/kavehamini/Amazon-Review-Analysis-JBL-Charge-4-Speaker-Sentiment-Analysis-NLP/blob/master/7.png">
</p>
Also 92% of the buyers are satisfied with their purchse and have rated the product good (3 stars or more).
<p align="center">
<img src="https://github.com/kavehamini/Amazon-Review-Analysis-JBL-Charge-4-Speaker-Sentiment-Analysis-NLP/blob/master/8.png">
</p>
It has been observed that the better the rating the shorter the length of the review.
<p align="center">
<img src="https://github.com/kavehamini/Amazon-Review-Analysis-JBL-Charge-4-Speaker-Sentiment-Analysis-NLP/blob/master/9.png">
</p>
## Machine Learning and Sentiment Analysis

Naive bayes Multinominal Classifier and KNN have been used as the Machine Learning models to analyze the reviews. feedback,awesome (5 star rating), good (3 star or more rating) and rating have been used as the dependent variable to be predicted (y). Review titles after removal of stop words and vectorization have been used as the independent variable (X).

The performace for all models has been good with above 85% accuracy and replacing the review title with review text to predict good variable ( 3 star or better reviews) did not change the accuracy of the model.


## Conclusion

The amazon review data were successfully scraped, analyzed and visualized. Also machine learning models ofNaive bayes Multinominal Classifier and KNN were employed to analyzed the sentiment of the reviewers.  


## Author

This project has been inspired by many similar projects on GitHub.com and has been performed by Kaveh Amini (kvhmni@gmail.com).