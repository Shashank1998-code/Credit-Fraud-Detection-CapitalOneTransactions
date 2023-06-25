# Credit-Fraud-Detection-CapitalOneTransactions

Credit card fraud detection (CCFD) is like looking for needles in a haystack. It requires finding, out of millions of daily transactions, which ones are fraudulent. Due to the ever-increasing amount of data, it is now almost impossible for a human specialist to detect meaningful patterns from transaction data. For this reason, the use of machine learning techniques is now widespread in the field of fraud detection

# Base Line ML Architecture

![baseline_ML_workflow](baseline_ML_workflow.png)

# Challenges

ML for CCFD is a notoriously difficult problem. I summarise below the commonly faced challenged. 

Class imbalance: Transaction data contain much more legitimate than fraudulent transactions: The percentage of fraudulent transactions in a real-world dataset is typically well under 1%. Learning from imbalanced data is a difficult task since most learning algorithms do not handle well large differences between classes. Dealing with class imbalance requires the use of additional learning strategies like sampling or loss weighting, a topic known as imbalanced learning.

Categorical features: Transactional data typically contain numerous categorical features, such as the ID of a customer, a terminal, the card type, and so on. Categorical features are not well handled by machine learning algorithms and must be transformed into numerical features. Common strategies for transforming categorical features include feature aggregation, graph-based transformation, or deep-learning approaches such as feature embeddings.

Performance measures: Standard measures for classification systems, such as the mean misclassification error or the AUC ROC, are not well suited for detection problems due to the class imbalance issue, and the complex cost structure of fraud detection. A fraud detection system should be able to maximize the detection of fraudulent transactions while minimizing the number of incorrectly predicted frauds (false positives). It is often necessary to consider multiple measures to assess the overall performance of a fraud detection system. Despite its central role in the design of a fraud detection system, there is currently no consensus on which set of performance measures should be used.

# PROPOSED SOLUTION

1_Load_Dataset
------------------

In this Notebook I download, unzip and load the Datset from the URL provided.
Question 1 of the Challenge is answered here.

2_EDA_Vizualization
---------------------

This notebook includes basic Data Cleaning, Exploratory Data Analysis and the various plots.
Question 2 of the Challenge is answered here.

3_Preprocessing_Wrangling
--------------------------

This notebook contains the various preprocessing operations performed before fitting the model.
I have also answered the Question 3 - Data Wrangling here.

4_Modelling
------------

Question 4 of the Challenge is answered here.

This Notebook contains various Machine Learning Algorithms that have been fit to the data. I present
the results of the various models and the conclusions drawn. I also present here the Future Scope 
and References.
