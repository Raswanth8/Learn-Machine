## A Content-Based Video Recommendation System that Reduces Churn Rate on OTT Media

### Problem Description :

With the world moving towards remote way of living, the data generated in enormous and existing recommendation system is not providing adequate accuracy to the user which results in spontaneous increase in the churn rate. This causes losses to the company which brings us the cruciality of building a better recommendation system with best accuracy. The objective of this case study is to build a recommendation system with better accuracy to provide top content recommendations to the user, thereby reducing the churn rate. Also, we will be able to suggest the best streaming platform that hosts movies similar to that a person likes furthering which their subscription plans can be showcased to the user. This way we understand that churn rate for that particular user is less on that suggested platform.

### Models Used :
- **Recommendation System :**
The next step in the process is to build the machine learning model for the recommendation system. In order to produce better recommendations we have built the system using countvectorizer and cosine similarity. Countvectorizer has been utilized to tokenize the text data values such as Title,Directors,Genre,Country,Language,OTT Platforms, Encoded movie ratings. The above features would be combined into a single feature and passed into Countvectorizer. Upon finishing that, the count matrix would be computed in order to proceed with Cosine Similarity. Cosine Similarity is a metric to distinguish and compare features to each other based upon their similarities and overlap of the particular attribute. 

- **Regression Techniques for computing runtime :**
Regression analysis is a form of predictive modelling technique which investigates the relationship between a dependent (target) and independent variable (predictor). In the case study the analysis is done by taking runtime as target variable and other features as independent variable. To computer regression modelling we have performed 4 different regression techniques namely : Linear Regression. Random Forest regressor, Decision Tree Regressor, Logistic Regression.







