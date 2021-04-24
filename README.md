# BT5153-Group-Project
Applied Machine Learning Group Project
#Group 9 Members: He Dongying, Kwok Shi Ann Sheranne, Lee Kok Mun, Mittal Sidharth and Poh Huizhen Isabella

##Codes
Here I will write what's there in the different code files:
1. The data-preprocessing and feature engineering file has all the pre-preocessing steps that we did to get the clean data; it also has codes for generating additional features which were used for making the predictions
2. Our team did extensive EDA to understand the data - hence, have segregated the EDA codes into 2 files (EDA-Part 1 and EDA-Part 2)
3. We also extracted sentiment scores from loan description - this is in sentiment and emotion score code
4. There are 3 different files for the prediction model as we tried various models; predictions (DT, RF, and XGB) has codes for decision tree, random forest and XGBoost; prediction (LR,NB and KNN) has codes for logistic regression, naive bayes, and k-nearest neighbours; prediction neural network has codes for deep neural network model
5. There are 2 files for recommendation models – 6 (a) contains the code for our content-based recommendation model, and 6 (b) contains the code for generating the similarity between user profiles to address the cold start problem.
6. Text summarization has codes for the extractive text summarization appraoch.

##Datafiles and other outputs
We have uploaded 5 datafiles that we used for modelling:
1. Kiva_loan_lenders_sample_2000 contains sample information for different loans and their corresponding lenders.
2. Kiva_loan_sample_data contains the sample information for different loans and their corresponding features, such as loan description and borrower information.
3. Kiva_loans_lenders acts as a joining table.
4. Web_Scrap_Interest_Group contains the information for the different user interest groups - this was scraped from the Kiva Website.
5. Web_Scrap_Partner_Info contains the field partner information scraped from the Kiva Website.

Output files: We have also uploaded 2 output .png files - these are the sample newsletters and modified sampled kiva landing page which contains the result of text summarization model.

Happy Coding! 
