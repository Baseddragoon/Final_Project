# Final_Project

This is the final project I did at TripleTen. This Project has us working with data from Interconnect, where we are given 4 dataframes, phone, personal, internet, and contract. The first portion of this project is a work plan that covers a breifing on the steps that I will be working on during the project. The steps are as followed

1. Import the Libraries and Load the Dataframes in the notebook
2. Preproccessing Stage of EDA: Fix missing data, fix column names, column data types, duplicated data, and Merge all the DFs together using the customer_id column
3. Perform EDA: Focus on graphs and trying to see if we can corelations about customers that are stil with the company or trends of those who left.
4. Split the Data into Training and Testing sets of Data.Perform Model Training on several Models to find the best one and use the best one the testing sets of data
5. Come to a general conclusion to the Interconnect Work Plan indicating how well of an AuC ROC score the model acheives for predicting churning customers, and talking about any coorelations we found in the  EDA process that looks like it contributed to causing customers to churn.

The goal of this project is to make a model that is capable of determining if customers are going to churn at Interconnect. The project uses a ROC-AUC to judge how well the model performs. There are some things such as inbalalnce, feature encoding and data scaling we must do in order to create a well trained model that does not overfit the data skewing the results as well. The grading for the AUC-ROC is below:
AUC-ROC < 0.75 — 0 SP
0.75 ≤ AUC-ROC < 0.81 — 4 SP
0.81 ≤ AUC-ROC < 0.85 — 4.5 SP
0.85 ≤ AUC-ROC < 0.87 — 5 SP
0.87 ≤ AUC-ROC < 0.88 — 5.5 SP
AUC-ROC ≥ 0.88 — 6 SP
