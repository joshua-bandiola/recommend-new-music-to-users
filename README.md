# Music Recommendation System

## Description 
This project aimed at developing a music recommendation system that predicts and suggests new music based on user preferences.
Built using Python and Apache Spark, this project applies core data mining principles such as data cleaning,
exploratory data analysis, and feature engineering. By applying the FP-Growth algorithm, the system identifies patterns in 
user listening habits and recommends new music based on frequent itemsets. 

To optimize accuracy, the model was trained by setting different values for support and confidence.
Using a for-loop, various combinations of these values were tested to generate association rules, and the results were 
visualized to determine the optimal thresholds. The hypertuned model was then used to predict music recommendations tailored
to each user.

By utilizing frequent pattern mining and data analysis techniques, this project provides users with more relevant music
recommendations based on their historical listening habits. 

The techniques used in this project can be applied to a wide range of recommendation engines beyond music. For instance, 
they can be adapted to build product recommendation systems in e-commerce, where purchasing patterns help suggest relevant
products to users. These methods can also be used for customer segmentation in marketing, helping identify user groups 
based on behaviour and preferences. The scalability of using Apache Spark ensures that it can handle large datasets
efficiently. 

## Tech Stack
- **Programming Language**: Python
- **Framework**: Apache Spark
- **Libraries**:
  - PySpark
  - Pandas
  - Scikit-Learn
  - Matplotlin/seaborn
- **Algorithms**:
  - FP-Growth
