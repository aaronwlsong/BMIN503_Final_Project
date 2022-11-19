# BMIN503/EPID600 Final Project

This repository contains templates for your final written report and GitHub repository. Follow the instructions below to clone this repository, and then turn in your final project's code via a pull request to this repository.


1. To start, **fork** this BMIN503_Final_Project repository.
1. **Clone** the forked repository to your computer.
1. Modify the files provided, add your own, and **commit** changes to complete your final project.
1. **Push**/sync the changes up to your GitHub account.
1. Create a **pull request** on this, the original BMIN503_Final_Project, repository to turn in your final project.


Follow the instructions [here][forking] if you are unsure what the above steps mean.

DUE DATE FOR FINAL VERSION: 12/09/22 11:59PM. This is a hard deadline. Turn in whatever you have by this date.


<!-- Links -->
[forking]: https://guides.github.com/activities/forking/

------------------------------------------------------------------------------------Below is the information about this research--------------------------------------------------------------------------------------------
NOTE: This project is in process, most of work is still undergoing.....

Title for the research: Exploration of significant predictor for decision of taking PrEP among high risk population based on machine learning and casual inference method

Introduction: 

To better control HIV infection among high risk population, it urgently needs to explore the relationship between related determinants that may affect Pre-Exposure Prophylaxis (PrEP) usage. Jilinde PrEP cohort study was conducted in Kenya, it contains over 1000 participants and over 300 variables that related to PrEP usage among high risk population. In this project, curated dataset is used to analyze the potential PrEP predictors that may impact the PrEP usage among targeted population.  

Aim and significance: We expect to through this research, it can provide practical references for HIV prevention through PrEP in local area, moreover, present a plausible way to optimize model by integrating causal inferential theory to machine learning model.   
	Primary aim: Exploring significant predictors for outcome: Decision of taking PrEP. 
	The secondary aim: Compare different machine learning models' effective given the unbalanced outcome. 

Method: Cleaned the dataset by using baseline and completed case to carry on analysis. The barplot is used to check outcome variable, the GLM, random forest tree and SVM are used as predicted models. ROC curve is used to evaluate the model's performance. The Gini score and p-value are used to create most significant predictors list for further GLM model comparison. Then, the two GLM models: One is that contain top 6 significant predictors from the GLM result meanwhile overlapped with RF result, another GLM model contains the adjusted predictors which applied casual inferential theory on it.  

Result: The GLM model with variables that are adjusted based on causal inferential theory shows the better performance to predict the outcome. The result shows that the people who have had sex shows the most intention to take PrEP, which imply the intervention and advertising direction among the high risk population when it comes to the uptake PrEP.

Limitation: Unbalanced outcome affect the performance and accuracy when run different ML models.
                  Using completed dataset will introduce the bias since the missing value is not completed random. 