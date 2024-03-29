# ML-based-IDS
Implementation of an IDS based on the public dataset UNSW-NB15. The analysis takes in consideration the differences between classification task when we leave the training set unbalanced, w.r.t the case in which the training set is rebalanced (with RandomUnderSampler and SMOTE)

## Problem addressed
_Binary classification:_<br>
The task is to predict for a given datapoint if it belongs to the attack or non-attack category.

_Multiclass classification:_<br>
The dataset contains "attack_cat" with 9 values that represent different types of malicious traffic and 1 that represents benign traffic. The task is to predict for a given datapoint to which category it belongs.

## Machine Learning techniques
Techniques employed for the analysis:
- Naive Bayes
- Decision Tree
- Random Forest

A Stratified K-fold cross validation strategy is applied.
Further details in the notebook and associated presentation.

## References
- Moustafa, Nour, and Jill Slay. "UNSW-NB15: a comprehensive data set for network intrusion detection systems (UNSW-NB15 network data set)." Military Communications and Information Systems Conference (MilCIS), 2015. IEEE, 2015.
- Moustafa, Nour, and Jill Slay. "The evaluation of Network Anomaly Detection Systems: Statistical analysis of the UNSW-NB15 dataset and the comparison with the KDD99 dataset." Information Security Journal: A Global Perspective (2016): 1-14.
- Moustafa, Nour, et al. "Novel geometric area analysis technique for anomaly detection using trapezoidal area estimation on large-scale networks." IEEE Transactions on Big Data (2017).
- Moustafa, Nour, et al. "Big data analytics for intrusion detection system: statistical decision-making using finite dirichlet mixture models." Data Analytics and Decision Support for Cybersecurity. Springer, Cham, 2017. 127-156.
- Sarhan, Mohanad, Siamak Layeghy, Nour Moustafa, and Marius Portmann. NetFlow Datasets for Machine Learning-Based Network Intrusion Detection Systems. In Big Data Technologies and Applications: 10th EAI International Conference, BDTA 2020, and 13th EAI International Conference on Wireless Internet, WiCON 2020, Virtual Event, December 11, 2020, Proceedings (p. 117). Springer Nature.