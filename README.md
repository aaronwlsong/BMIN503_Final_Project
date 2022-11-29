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

------------Below is the information about this project----------------------------------

This is BMIN503/EPID600 Final Project made by Weilu Song.

The folder contains 5 files, they are:
1) Final project_song. Rmd. This file contains all original codes that are used to generate the project.
2) Final_project_Song.html. This file contains the whole contents of project including introduction, method, result and discussion. 
3) method pic. This .png file is used to show the method flow, it is kept as a separated picture in the same path/folder with .Rmd file and used in .Rmd file. 
4) Jilide_coh_2022aug.csv. This is original dataset that was used in this project.
5) README.md. This is a readme file which contains the list of files and their brief information as well as a gist of research. 

--------------------Below is the gist of this research--------------------------------------------- 

Title: Exploration of significant predictors for decision of taking PrEP among high risk population based on machine learning algorithm

Introduction: 

Pre-Exposure Prophylaxis (PrEP) has been proven an effective way to prevent HIV infection.However, the PrEP coverage among high risk population is still low. The reason behind it is complex, because making a decision of taking PrEP is determined by multiple factors. When conduct and collect the dataset, the researchers always try to capture as much participant's characteristic as possible. Therefore, it leads a results that a typical epidemiological dataset contains hundreds of variables. Therefore, it is needed to integrate the machine learning method to identify the significant variables and further optimize the model based on the selected variables. 

Hypothesis: 
	Primary aim: Exploring significant predictors for outcome: Decision of taking PrEP. 
	The secondary aim: Compare different machine learning model's  given an imbalanced dataset. 

Significance: 
           We expect that the research can provide practical references for HIV prevention by using PrEP in Kenya. In addition, present a plausible way to optimize model based on machine learning model. 

Method: 
     A Curated, completed dataset is used in this project. To achieve our aim, there are mainly 6 steps for analysis: 
     Step 1: Outcome variable inspection;
     Step 2: Demographic variable inspection;
     Step 3: Variable selection;
     Step 4: Model evaluation;
     Step 5: Create original GLM model; 
     Step 6: Optimize GLM model. 
     
Result: 
    1) Main result: 4 variables out of 6 have statistical significant association with outcome. They could be considered as predictors for decision of taking PrEP. 
    2) Variable selection: Toal 18 significant associated variables/predictors are selected by GLM model given the a=0.05 level. The outcome inspection result shows that the dependent variable has 	    extreme unbalanced outcomes (24 v.s 1108) which severely affects the model's performance. 
    3)Model selection and evaluation: GLM has the best performance for this extreme unbalanced number outcome compared to SVM and Random forest tree. 

Limitation: 
     1) Imbalanced outcome affect the performance and accuracy when run different ML models.
     2) Using completed dataset will introduce the bias since the missing value is not completely random. 
                  
                  