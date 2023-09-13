# ca4022_yahoo_topic_classification

This is the shared repository of Diarmuid Brady and Joseph Oluwasanya. It contains all the code and details of our Big Data Yahoo Topic Classification team project as part of the CA4022 Data at Speed and Scale Final Assignment.

# Key Insights
- We compared the performance of Linear Support Vector Machines and Random Forest at classifying the Yahoo Answer topics using a TF-IDF document embedding.
- The Support Vector Machine outperformed the Random Forest producing an accuracy of 64% when predicting across all 10 topics.
- These results are comparable to results obtained from an LSTM of 68%
- Therefore, we believe that the use of simple linear classifiers is still merited as they are still very powerful and much less computationally expensive than more complex deep learning architectures.

# File Structure
There are a number of directories each of which has a specific purpose.

## Data
- This contains all the data required for the assignment. This folder is included in the .gitignore and therefore is not present on Github. To find the data visit [Yahoo Topic Classification on Kaggle](https://www.kaggle.com/datasets/bhavikardeshna/yahoo-email-classification?select=train.csv)
- The data contains 2 million samples (1.4 million training and 60,000 test).
- There are 10 topics and the data samples are split evenly between each topics (140,000 for each topic)
- The ten topics include 
	- Society & Culture
	- Science & Mathematics
	- Health
	- Education & Reference
	- Computers & Internet
	- Sports
	- Business & Finance
	- Entertainment & Music
	- Family & Relationships
	- Politics & Government

## Deliverables
The deliverables contain the following:
- Midway Report (500 words) describing the dataset, technology, analytics and the plan for team roles
- Final Report (3 pages) describing the project analysis and findings
- ScreenCast (5 minutes) demonstrating each of the components of our analysis running

## Environments
Environments contain the environment file we used to set up our Anaconda environment call yahoo.

## Notebooks
Notebooks consists of several jupyter notebooks that contain all the code including cleaning, processing, feature engineering, modelling and visualization.

## Specification
Specification contains the original specification and requirement details for our assignment.
