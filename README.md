# presidential-speech-analysis
Using NLP to understand speech patterns among Republican and Democratic Presidential speeches


Purpose

This project investigates whether linguistic patterns in U.S. presidential speeches can be used to accurately classify these speeches into their respective political parties. Utilizing techniques such as TF-IDF vectorization and logistic regression, this analysis aims to identify distinct linguistic signatures associated with Democratic and Republican speeches and assess the predictive power of machine learning in political science.

Data Source

The dataset comprises official U.S. presidential speeches sourced from Kaggle, containing transcripts up to September 2019. After initial cleaning, speeches from only Democratic and Republican presidents were considered, dating from post-1920 to align with the historical consolidation of political party platforms.

Dataset Link: Kaggle Dataset

Code Overview

The code in finalcode.ipynb encompasses several stages of data processing and analysis:

Data Cleaning: Trimming the dataset to include relevant entries and preprocessing text data.
TF-IDF Vectorization: Transforming the cleaned text data into a numerical format suitable for machine learning.
Model Training: Implementing and evaluating a logistic regression model to classify speeches based on political party affiliation.
Semantic Similarity Analysis: Examining the thematic consistency within and across the political speeches using spaCy for natural language processing.
Key Findings

The logistic regression model demonstrated a moderate success rate in classifying speeches by political party, with distinct differences in language usage patterns between the two major parties.
Semantic analysis revealed substantial intra-party coherence, suggesting a strong alignment in the thematic and stylistic elements of speeches within the same party.
Future Work

Further research could explore the impact of historical contexts on presidential rhetoric, aiming to understand how pivotal events and societal shifts influence the linguistic strategies of presidents from different eras.
