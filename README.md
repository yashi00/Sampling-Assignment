# Sampling-Assignment
In this python code, we have used sampling techniques on a credit card fraud detection dataset and then applied various ML models on the dataset to find out which Model,sampling technique combination gives us the best accuracy.

Following 5 sampling Techniques were used:

Random Under Sampler (Sampling1)
Random Over Sampler (Sampling2)
SMOTE (Sampling3)
TOMEK links (Sampling4)
Near Miss (Sampling5)

The Sample size was calculates using the following formula: n = Z^2(p(1 – p)/m^2) where: n = sample size Z = z-value (for 99% confidence interval, Z = 2.576) p = proportion of the minority class (taken as 0.5 for a balanced dataset) m = margin of error (taken as 0.05 for a sample size of 1000)

Following 5 models were applied on the sampled dataset:

Logistic Regression (M1)
Decision Tree Classifier (M2)
Random Forest Classifier (M3)
Support Vector Classifier (SVC) (M4)
Extra Tree Classifier (M5)
