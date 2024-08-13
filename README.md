# Predicting Employee Satisfaction on Glassdoor: Machine Learning Analysis

#### Description
This project aims to predict employee satisfaction based on features such as job level, work-life balance, and company culture through data analysis and different machine learning models, including Ridge Regression, Logistic Regression, Random Forest, and LightGBM.

This project is still being iterated upon,
Feedback and suggestions are welcome as I continue to refine this project

#### Purpose:
Employee satisfaction is crucial for company success. Understanding the factors that influence satisfaction can help in making data-driven decisions to improve the workplace environment.

Few of the goals and question I had in mind:
- Understand the relation/correlation among employee satisfaction and industries (is it same all throughout?)
- Understand the key drivers for employee satisfactin, worklife balance, management, key words in reviews, etc.
    - Any opportunities to improve overall satisfaction to attract to new talent?
    - Which areas of employee environemnt to put emphasis on for different industries?

#### Data Overview
The dataset contains 800,000 employee reviews with features such as job title, level, satisfaction ratings, and more, but after extensive cleaning I narrowed it down to 240000 reviews with minimimal selection bias.

Due to github's limitation on size of dataset (220MB), you will need to download the glassdoor dataset from the following link:
https://www.kaggle.com/datasets/davidgauthier/glassdoor-job-reviews/data


#### Installation Instructions: Provide a step-by-step guide on how to run the project, including setting up the environment, installing dependencies, and running the models.
Clone the repository
Install dependencies: pip install -r requirements.txt

Also download SpaCy Model by pasting this 
`python -m spacy download en_core_web_sm`


