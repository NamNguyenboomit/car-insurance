# CAR INSURANCE CLAIM PREDICTION IN NEXT 6 MONTHS
## Car Insurance Market
With the gradual increase in the number of cars, companies will pay more and more attention to precision marketing.

Car insurance companies are increasingly focusing on data mining to __identify customer profiles__, thereby forming specific strategies for each customer group with the goal of optimizing business profits. The use of machine learning models will help companies predict the future trend of insurance usage for each customer based on certain personal characteristics and the history of that individual. This project consists of __three main parts__ with the goal of identifying customer profiles through certain factors and building a machine learning model for predicting claims in the next 6 months using some basic algorithms. The parts include:

-	Data cleaning (handling missing data, handling outliers) <br>
-	Exploratory data analysis <br>
-	Machine learning <br>

## Exploratory Data Analysis
The objective of this section is to identify the customer profile and help the business have a better understanding of customer groups with a tendency to confirm using car insurance in the next 6 months (which means the customer is likely to have a car accident).

The factors analyzed in this project include:

-	Kids Driving (KIDSDRIV): Analyzing the relationship between whether __customers allow teenagers to use their cars and whether it increases the likelihood of using car insurance in the future__. <br>
-	Age (AGE): Determine the relationship between age groups and confirmation of usage insurance, as well as identify the distribution of age groups in the project.<br>
-	Income and Home Value (INCOME, HOME_VAL): Identify the relationship between income and house value, as well as their impact on the intention to use insurance. Additionally, evaluate the differences in insurance usage between customers who do not own a house (house value = 0) and those who do own a house. <br>
=>	In addition, additional factors such as Occupation, Car Age, Car Type, Previous Claim and Revoked are assessed.

=>	Evaluating different factors helps companies to __develop appropriate strategies for different customer groups__.

## Machine Learning
Balancing the imbalanced data using __SMOTE__ to tackle the issue of the imbalanced confirmation of insurance usage. Afterward, __Extra Tree Classifier__ is employed, this is a Model-based approach for selecting the features using the tree-based supervised models to make decisions on the importance of the features. The Extra Tree Classifier or the Extremely Random Tree Classifier is an ensemble algorithm that seeds multiple tree models constructed randomly from the training dataset and sorts out the features that have been most voted for. 
Algorithms were used:

-	Logistic Regression<br>
-	XGBoost<br>
-	Ada Boost<br>
-	Random Forest<br>
-	Gradient Boosting Classifier<br>


