# Data Science Process Project
## Overview of the project
In this project, we apply the CRoss Industry Standard Process for Data Mining (CRISP-DM) to answer the following questions:
1. What are the parameters impacting the personal insurance cost?
2. What is the most important parameter in deciding your insurance cost?
3. Is the insurance cost biased based on the gender?

## Project phases 
In this project we followed the standard CRISP-DM steps as follows:

1. Business understanding – What does the business need?
2. Data understanding – What data do we have / need? Is it clean?
3. Data preparation – How do we organize the data for modeling?
4. Modeling – What modeling techniques should we apply?
5. Evaluation – Which model best meets the business objectives?
6. Deployment – How do stakeholders access the results?

For this project we will stop at step 5 and leave the deployment to a later phase.

## Project resource
For this project we used the dataset available [Medical Cost Personal Dataset](https://www.kaggle.com/mirichoi0218/insurance). The dataset is referenced at "Machine Learning with R" by Brett Lantz. The dataset can also be downloaded from the github link [here](https://github.com/stedy/Machine-Learning-with-R-datasets).

## Project outcome
### Factors deciding your insurance cost
We thought the columns of the dataset are a good representative of the parameters impacting the insurance cost for individuals. They are as follows:
- Sex
- BMI (Body Mass Index)
- Smoking
- Age
- Number of children
- Region where the person lives in

### The most important factor for your insurance
After fitting our model to the data (and being able to predict with %70 accuracy), we investigated the weights of the coefficients in the model. The highest weight, by far, was smoking.

### Gender biad
Through our analysis, we realized the coefficient for gender (i.e., sex) was the lowest weight, indicating there is no strong correlation between gender and insurance cost, at least from this dataset.

## Project structure
All the codes are put in the Jupyter notebook. The dataset is also located at the root folder. Just run through the notebook to see each section or download it as a Python file and run it.