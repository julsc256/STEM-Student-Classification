# Overview
___

The objective is to determine if a student should be interviewed for a spot into the prestigious STEM Academy.

___

## The Process

Supervised learning - Classification - allows us to tell if something belongs to one class, or the other. In this particular project, we're doing a multiclass classification problem because we're determining if a student will get accepted or not into the STEM Academy.

## Dataset

- Used selenium to scrape the school district information of each student from their middle school years.
    1. Grades
    2. Attendance
    3. State test scores
    4. Teacher comments

## The Notebooks

1. Collecting Data 1 
    - Selenium gathering from the STEM High School
2. Collecting Data 2 
    - Selenium gathering from the High School
4. Processing Data 1 (Creating Dataframe)
    - Combining the dataframes from the selenium web scrapping together and cleaning the data.
5. Processing Data 2 (Feature Engineering)
    - Cleaning the text data and creating new features from existing dataset.
6. Processing Data 3 (NLP)
    - NLP techniques
7. Processing Data 4 (Clustering)
    - An expoloration into clustering.  Taking out the 'target' column and seeing what happens as an unsupervised learning problems.
8. Exploring Data
    - Using the data to find relationships between the dataset.
        - Looking into the target, gender, and comments.
9. Modeling
    - All the prediction models using pipelines, PCA, and GridSearchCV

## Model Comparions

- KNN
- Decision Tree
- Random Forest
- Gradient Boost
- AdaBoost
- XGBoost
- Isolation Forest

## Steps

1. Scrape the data and clean the data.
    - Cleaning the text data to perform NLP techniques
1. Use a pipeline to go through each model and find the best accuracy score for the model.
2. Use accuracy score to determine best model.
3. Use a sample size to check accuracy of the best model.
4. Review results.
___

# Results

The best model with a 91% accuracy was XGBoost, when testing the models on the sample size, it resulted in 15 out of 18 correct results.  

___

# Future Work

1. Continue to work on improving the model.
    - Especially with teacher comments because they can be anything the teacher writes, need to implement a better NLP process in which will be better interpreted.
2. Develop interactive application for use of all schools to be able to use to determine if students should be interviewed for a spot into their school or not.
