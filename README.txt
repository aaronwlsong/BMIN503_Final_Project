{\rtf1\ansi\ansicpg1252\cocoartf2580
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;}
{\*\expandedcolortbl;;\cssrgb\c0\c0\c0;}
\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx560\tx1121\tx1681\tx2242\tx2803\tx3363\tx3924\tx4485\tx5045\tx5606\tx6166\tx6727\tx7288\tx7848\tx8409\tx8970\tx9530\tx10091\tx10651\tx11212\tx11773\tx12333\tx12894\tx13455\tx14015\tx14576\tx15136\tx15697\tx16258\tx16818\tx17379\tx17940\tx18500\tx19061\tx19621\tx20182\tx20743\tx21303\tx21864\tx22425\tx22985\tx23546\tx24106\tx24667\tx25228\tx25788\tx26349\tx26910\tx27470\tx28031\tx28591\tx29152\tx29713\tx30273\tx30834\tx31395\tx31955\tx32516\tx33076\tx33637\tx34198\tx34758\tx35319\tx35880\tx36440\tx37001\tx37561\tx38122\tx38683\tx39243\tx39804\tx40365\tx40925\tx41486\tx42046\tx42607\tx43168\tx43728\tx44289\tx44850\tx45410\tx45971\tx46531\tx47092\tx47653\tx48213\tx48774\tx49335\tx49895\tx50456\tx51016\tx51577\tx52138\tx52698\tx53259\tx53820\tx54380\tx54941\tx55501\tx56062\slleading20\pardirnatural\partightenfactor0

\f0\fs24 \cf2 \
This is BMIN503/EPID600 Final Project made by Weilu Song.\
\
Title: Exploration of significant predictors for decision of taking PrEP among high risk population based on machine learning algorithm\
\
Introduction: \
\
Pre-Exposure Prophylaxis (PrEP) has been proven an effective way to prevent HIV infection.However, the PrEP coverage among high risk population is still low. The reason behind it is complex, because making a decision of taking PrEP is determined by multiple factors. When conduct and collect the dataset, the researchers always try to capture as much participant's characteristic as possible. Therefore, it leads a results that a typical epidemiological dataset contains hundreds of variables. Therefore, it is needed to integrate the machine learning method to identify the significant variables and further optimize the model based on the selected variables. \
\
Hypothesis: \
	Primary aim: Exploring significant predictors for outcome: Decision of taking PrEP. \
	The secondary aim: Compare different machine learning model's  given an imbalanced dataset. \
\
Significance: \
           We expect that the research can provide practical references for HIV prevention by using PrEP in Kenya. In addition, present a plausible way to optimize model based on machine learning model. \
\
Method: \
     A Curated, completed dataset is used in this project. To achieve our aim, there are mainly 6 steps for analysis: \
     Step 1: Outcome variable inspection;\
     Step 2: Demographic variable inspection;\
     Step 3: Variable selection;\
     Step 4: Model evaluation;\
     Step 5: Create original GLM model; \
     Step 6: Optimize GLM model. \
     \
Result: \
    1) Main result: 4 variables out of 6 have statistical significant association with outcome. They could be considered as predictors for decision of taking PrEP. \
    2) Variable selection: Toal 18 significant associated variables/predictors are selected by GLM model given the a=0.05 level. The outcome inspection result shows that the dependent variable has 	    extreme unbalanced outcomes (24 v.s 1108) which severely affects the model's performance. \
    3)Model selection and evaluation: GLM has the best performance for this extreme unbalanced number outcome compared to SVM and Random forest tree. \
\
Limitation: \
     1) Imbalanced outcome affect the performance and accuracy when run different ML models.\
     2) Using completed dataset will introduce the bias since the missing value is not completely random. }