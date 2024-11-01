# Esophageal-Cancer-Detection
The Machine Learning project on Esophageal Cancer Detection 


Esophageal cancer is a growth of cells that starts in the esophagus. The esophagus is a long, hollow tube that runs from the throat to the stomach. The esophagus helps move swallowed food from the back of the throat to the stomach to be digested.
Esophageal cancer usually begins in the cells that line the inside of the esophagus. Esophageal cancer can happen anywhere along the esophagus.

Symptoms:-
Esophageal cancer may not cause symptoms early on. Symptoms of esophageal cancer usually happen when the disease is advanced.
Signs and symptoms of esophageal cancer include:
•	Difficulty swallowing.
•	Chest pain, pressure or burning.
•	Coughing or hoarseness.
•	Weight loss without trying.
•	Worsening indigestion or heartburn.

Causes: -
Esophageal cancer happens when cells lining the esophagus develop changes in their DNA. A cell's DNA holds the instructions that tell the cell what to do. In healthy cells, the DNA gives instructions to grow and multiply at a set rate. The instructions tell the cells to die at a set time. In cancer cells, the DNA changes give different instructions. The changes tell the cancer cells to make many more cells quickly. Cancer cells can keep living when healthy cells would die. This causes too many cells. The cancer cells might form a mass called a tumor. The tumor can grow to invade and destroy healthy body tissue. In time, cancer cells can break away and spread to other parts of the body. When cancer spreads, it's called metastatic cancer.
Types of esophageal cancer
Esophageal cancer is classified depending on the type of cells that are involved. The type of esophageal cancer you have helps determine your treatment options.

Types of esophageal cancer include:
•	Adenocarcinoma: Adenocarcinoma begins in the cells of the glands in the esophagus. These glands produce mucus. Adenocarcinoma happens most often in the lower part of the esophagus. Adenocarcinoma is the most common form of esophageal cancer in the United States. It affects mostly white men.
•	Squamous cell carcinoma: Squamous cell carcinoma begins in the flat, thin cells that line the surface of the esophagus. Squamous cell carcinoma happens most often in the upper and middle parts of the esophagus. Squamous cell carcinoma is the most common esophageal cancer worldwide.
•	Other rare type: Some rare forms of esophageal cancer include small cell carcinoma, sarcoma, lymphoma, melanoma and choriocarcinoma.

Project:
The Machine Learning project on Esophageal Cancer Detection Using a dataset of 3985 records with 85 features, I applied thorough Data Cleaning, Feature Engineering, Exploratory Data Analysis and Model testing to predict cancer risks effectively.

Data Cleaning & Preparation: -.
•	Filtered out features with over 50% missing values and dropped unnecessary columns to refine our dataset.
•	Handled remaining missing values with targeted imputations using mode for categorical features and mean for continuous.
Feature Engineering & Classification: -.
•	Classified features as categorial, continuous or discrete for structural handling
•	Applied Chi-Square tests to identify high impact categorial features, giving us a clearer view of predictors.
Exploratory Data Analysis (EDA): -
•	Leveraged Histograms, Box Plots and Count Plots to explore distributions and identity patterns in cancer progression.
•	Created pivot tables for demographics and disease status to uncover trends across gender, race and age in Esophageal Cancer outcomes.

Data Visualization for Deeper Insights: -
•	Built Correlation Heatmaps to study relationships among continuous features, highlighting predictors and feature interactions.
•	Used distribution plots to analyze differences in patient habits, cancer stages and survival metrics.

Model Testing & Results: -
After data preparation, I tested several algorithms to identify the best-performing model for cancer detection –

•	Logistic Regression: -
Accuracy = 64.87%
Confusion Matrix = [[60, 4, 3], [84, 292, 71], [46, 72, 165]]
Classification Report: Precision = 32% (Class 0); 79% (Class 1); 69% (Class 2); 
Recall: 90% (Class 0); 65% (Class 1); 58% (Class 2); 

•	Decision Tree Classifier: -
Accuracy = 99.75%
Confusion Matrix =  [[66, 1, 0], [0, 446, 1], [0, 0, 283]]

•	Classification Report: -
Perfect precision, Recall and F1-Scores across all classes.

Conclusion: -
This project has been a fantastic journey in applying data science, statistical analysis and machine learning techniques to support early cancer detection, potentially improving outcomes for those at risk of Esophageal Cancer.
