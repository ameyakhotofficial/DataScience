# Hiring Department  User Recommender.

Using High School mathematics to find a person with a certain set of characteristics that compare to the most desired candidate. 

##Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

1. Python 3 - Jupyter Notebook 

2. Python Libraries:
    
    a. Pandas
    b. NumPy
    c. Math
    d. Seaborn
    e. Seaborn

### Installing

Use Pip or Conda for installing any missing python libraries. You can install these libraries from Command Prompt or Jupyter Notebook itself.
Example:
        
         1. Pip:
            pip install seaborn
            
         2. JupyterNotebook:
            !pip install seaborn

## Intention

In the HR Domain, there are a lot of candidates that apply for a job position. An HR associate in no way can understand all the resumes and judge them correctly. This leads to human error and sometimes, a wrong candidate might be passed on to the interview and not the candidate who is needed the most to get the job done. 

This small piece of code was created to minimize the hiring process of a candidate from day 1 when an aptitute test is conducted to judge the students to when the students are called for final interviews. 

Here, we've tried to find the candidate who has highly similar skills to solve the problem which is needed to, in comparison with the persona of the candidate that the company has while hiring. 

This was a freelance project for a colleage. 

## Understanding the Dataset

The dataset uNew.data has user_id, rating (In the range 1-5), Question_id, and timestamp.
There are 6 users that have taken the test. Out of these 6, 5 users are candidates and 1 user is the legend, with whom the other 5 are compared with. 

The dataset 'ques_asked' has the questions assigned to certain question_id's.

When these 2 datasets are merged, a combined dataset is created that gives a complete understanding of the dataset.

## Authors

Ameya Khot and Aniket Sanap
