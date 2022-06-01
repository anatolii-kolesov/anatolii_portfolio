# Anatolii Kolesov - Data Science / Analytics Projects

# [Project 1: Churn Prediction with Logistic Regression (R)](https://github.com/anatolii-kolesov/ds_code/blob/main/classification_r/churn_prediction_with_logistic_regression.html)
### Overview
In this project I developed a logistic regression model to predict customer churn in a bank and estimated the time to churn with survival function.
The goal of the project was to identify the most important factors influencing customer churn and the average tenure of a customer before they churn.

### Results
- A Logistic Regression model was able to predict customer churn correctly with 78% accuracy.
- The most important factors for predicting churn are client’s place of residence, number of products they have and being an active member. Tenure, age and gender might also influence churn.
- On average, bank has ~ 10 months before the customer becomes very likely to churn. Keep in mind that this shows that the bank has been operating for a short period so far and it might change.

### Logistic regression model
![](https://github.com/anatolii-kolesov/anatolii_portfolio/blob/main/images/logistic_regression_model_output.PNG)

### Survival Analysis

![](https://github.com/anatolii-kolesov/anatolii_portfolio/blob/main/images/Survival_function_plot.PNG)

# [Project 2: Customer Satisfaction Prediction with Naive Bayes, Decision Trees, Logistic Regression (Python)](https://github.com/anatolii-kolesov/ds_code/tree/main/classification_python)
### Overview 
This project describes the development of a machine learning solution that would allow to predict the satisfaction of customers of an airline compnay based on individual satisfaction scores, features of customers, such as age, gender, and conditions of flights, such as distance traveled and arrival/departure delay.

The models were trained and tested on a dataset from [Kaggle](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction).

### Executive summary
Three machine learning models were developed using Naive Bayes (NB), Decision Trees (DT), and Logistic Regression (LR) algorithms.

With model tuning, the highest testing accuracy levels achieved with each algorithm were the following:

- Naive Bayes - 86.7%
- Decision Tree - 95%
- Logistic Regression - 87.3%

Decision Tree algorithm yeilded the highest accuracy and given its easy interpretability is deemed to be the best solution for this problem.

Confusion matrices for each of the models:

### Naive Bayes Classifier Confusion Matrix

![](https://github.com/anatolii-kolesov/anatolii_portfolio/blob/main/images/NB_cm.png)

### Decision Tree Classifier Confusion Matrix

![](https://github.com/anatolii-kolesov/anatolii_portfolio/blob/main/images/DT_cm.png)

### Logistic Regression Classifier Confusion Matrix

![](https://github.com/anatolii-kolesov/anatolii_portfolio/blob/main/images/LR_cm.png)

# [Project 3: Powerlifting Dashboard (Power BI)](https://github.com/anatolii-kolesov/ds_code/tree/main/powerlifting_dashboard)

### Overview

This project explores powerlifting – a sport in which athletes attempt to lift maximum weight for one repetition in squat, bench press and deadlift within their sex, weight and age categories. In this project I developed a dashboard that describes the composition of current powerlifting athletes, their results and powerlifting events as well as the relationships between certain parameters of the athletes (age, bodyweight, gender, equipment used) and the performance in each discipline. Two visuals in the last pages show the most influential factors that determine if an athlete is going to win a competition.

### Executive summary

- Body weight of an athlete was found to be positively related with the total weight lifted – heavier athletes on average are able to lift more total weight compared to lighter weight athletes. The average total weight lifted is lower for female athletes of the same body weight as male athletes. This trend is observed for all three exercises, the only difference is that the gap between how much more a male athlete is able to squat widens with the increase in body weight.
- The older the athlete, the less weight they are able to lift overall. This is true for male and female athletes, but on average male athletes are able to lift more weight that female athletes at any age, although this gap decreases with age.
- Older male athletes will be able to lift more weight in squat than in two other exercises compared to female athletes.
- The only influential predictors of being a winner of a competition are being at the end of the age or body weight distribution – either under 23 or over 40 and older when it comes to age, either under 60 kg or over 120 kg. This is simply because most athletes compete within “Open” age division (23 to 39 y.o.) and are of a medium weight (more than 60 kg, but less than 120kg), so athletes that compete outside of these categories simply have higher chances to win because there is less competition.
- The most important predictor of lifting the highest weight is different for male and female athletes. For males the most important factor of lifting the highest possible weight is the equipment used – the highest possible weight among males is lifted in wraps. For females the most important factor is the test status. On average, females that were not tested for performance-enhancing drugs (and hence had the opportunity to use them) lift higher total weight than those that were tested. Other than that, males on average lift higher weight than females, heavier weight athletes (over 80 kg) lift higher weight than lighter athletes, and athletes younger than 28 years old on average lift more weight than athletes that are older.
- For the all-time maximum weight lifted in each exercise the equipment used was different, for average values the lowest weight is lifted without equipment and the highest weight is lifted in the “Unlimited” category with the most supportive equipment.
- The highest possible lifts in every exercise for both male and female athletes were achieved in non-tested competitions. The same is true for averages, although for females the averages for non-tested versus tested are only 10 to 20 kg higher, while in all other categories the difference between tested versus non-tested is much higher - 30 kilograms and more.

The dataset used was obtained from [OpenPowerlifting](https://www.openpowerlifting.org/) website.

### Key findings page

![](https://github.com/anatolii-kolesov/anatolii_portfolio/blob/main/images/powerlifting_dashboard.PNG)

# [Project 4: University Rankings Cluster Analysis (R)](https://github.com/anatolii-kolesov/ds_code/blob/main/cluster_analysis_r/A.Kolesov_CA.Rmd)

In this project I explored possible clustering solution for the Times Higher Education World University Rankings 2020.

I ended up with 4 cluster solutions showing different groups of universities.

### K-means clustering solution

![](https://github.com/anatolii-kolesov/anatolii_portfolio/blob/main/images/k-means_clustering.png)

### Agglomerative clustering solution

![](https://github.com/anatolii-kolesov/anatolii_portfolio/blob/main/images/agglomerative_clustering.png)

# [Project 5: University Rankings Principal Component Analysis (R)](https://github.com/anatolii-kolesov/ds_code/blob/main/PCA_r/PCA.Rmd)

### PCA decomposition

![](https://github.com/anatolii-kolesov/anatolii_portfolio/blob/main/images/PCA.png)

### PCA with countries

![](https://github.com/anatolii-kolesov/anatolii_portfolio/blob/main/images/PCA_country.png)

# [Project 6: Sales Dashboard (Power BI)](https://github.com/anatolii-kolesov/ds_code/tree/main/sales_dashboard)

### Overview

This is a sales dashboard I made using the in-built dataset in Power BI

![](https://github.com/anatolii-kolesov/anatolii_portfolio/blob/main/images/sales_dashboard.PNG)

