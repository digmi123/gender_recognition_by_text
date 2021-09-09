# Gender Recognition by Text

## Description
In this project we were tasked to recognize the gender of the author of a given text using various algorithms which were taught as a part of the course.

## Dependencies
The project was written with Python 3.9.
**Packages used:**
- pandas
- sklearn

## Process
- We got database of paragraphs that have been written by students and we had to recognize by the text if the author is a male or a female
- Used stopwords.txt file which includes words that can decrease the accuracy of the model.
- Used the Inverse Document Frequency Vectorizer to determine how many times a particular word occurs in each paragraph.
- We used a KNN model because our project relates to clustering. We also used GridSearchCV to determine the ideal parameters for the KNN model.
- As a final step, we evaluated the accuracy of the model using the F1 score and Avg score for each gender.

## HIT Machine Learning course 2021 Final Project 

