# Functional-Analytics-Projects-
This Repository contains the following files 1.Amazon products review Sentiment Analysis 2. Women's Clothing (E-Commerce): Customer-Recommendation and Review-Rating Prediction

## Amazon products review Sentiment Analysis
Context: This dataset is provided by Datafiniti's Product Database and it includes product information, rating and reviews for all products.

We have tried to implement a sentiment analysis based on the ratings and the reviews.

Content: This dataset includes 34660 rows and 21 columns. Each row corresponds to a customer review. Exploratory Data Analysis Text Pre-Processing Model Selection 3 Labels Conclusion

Conclusion: From the models evaluated we can say that the three label sentiment analysis provieds good enough results. However, it can be improved by balancing the dataset. Either increasing the number of negative and neutral labels or by decreasing the positive labels. The f1, precision and recall overall score of the latest Random Forest model has good results.

## Women's Clothing (E-Commerce): Customer-Recommendation and Review-Rating Prediction
Context: This is a Women’s Clothing E-Commerce dataset revolving around the reviews written by customers. Its nine supportive features offer a great environment to parse out the text through its multiple dimensions. Because this is real commercial data, it has been anonymized, and references to the company in the review text and body have been replaced with “retailer”.

Content: This dataset includes 23486 rows and 10 feature variables. Each row corresponds to a customer review, and includes the variables:

Clothing ID: Integer Categorical variable that refers to the specific piece being reviewed. Age: Positive Integer variable of the reviewers age. Title: String variable for the title of the review. Review Text: String variable for the review body. Rating: Positive Ordinal Integer variable for the product score granted by the customer from 1 Worst, to 5 Best. Recommended IND: Binary variable stating where the customer recommends the product where 1 is recommended, 0 is not recommended. Positive Feedback Count: Positive Integer documenting the number of other customers who found this review positive. Division Name: Categorical name of the product high level division. Department Name: Categorical name of the product department name. Class Name: Categorical name of the product class name.

Conclusion: In this project we have used sentiment analysis to determine whether the product is recommended or not. We have built models with different machine learning and Deep learning algorithms and compare their performance. Thus, we have determined the algorithm that makes the most accurate emotion estimation by using the information obtained from the Review Text variable. When the scores are examined in the Compare section, it is seen that the scores are generally close to each other, but the Random Forest model stands out. When a new customer without any previous purchase history visits the e-commerce website for the first time, he/she is recommended the most popular products sold on the company's website. Once, he/she makes a purchase, the recommendation system updates and recommends other products based on the purchase history and ratings provided by other users on the website. The latter part is done using collaborative filtering techniques. Further, we have created Review Rating Prediction Model by using Logistic Regression with accuracy of 75%. With this model e-commerce will be able predict product ratings for future cutomers and will be able to recommend most recommended and rated products. To conclude this project, these models will facilitate in cost saving and better product offerings to the e-commerce customers, which will eventually upscale the business and revenue for the e-commerce
