# Enron-POI-Classifier

This project focuses on building a classification algorithm to identify individuals from Enron who may have committed fraud. The dataset includes features such as salary, bonuses, number of emails sent to known persons of interest, exercised stock options, and the occurrence of chosen stem words over email conversations. The primary goal is to develop a model that can effectively distinguish between Enron employees who were involved in fraud (Person of Interest - POI) and those who were not.

### Additional Notes

- The script removes outliers from the dataset, handles missing values, and creates two new features related to the proportion of messages sent to and received from persons of interest.
- Feature selection is performed using the SelectKBest method, and the script explores different classifiers to find the most suitable one for the task.
- The final classifiers are tuned using GridSearchCV to optimize performance metrics such as recall.
