<!-- PROJECT LOGO -->
<br />
<div align="center">
<p align="center">
  <img width="460" height="auto" src="https://github.com/vivekgriri/Datascience_projects/blob/main/images/fr.jpg">
</p>


  <h1 align="center">Fraud Detection Optimization in Card Transactions</h1>
  <p align="center">
    
Credit Card Fraud Detection: A Precision-Recall Approach
  </p>
</div>

<!-- ABOUT THE PROJECT -->
## About The Project

This project addresses the critical challenge of detecting fraudulent credit card transactions in a highly imbalanced environment. Using a dataset of over 284,000 transactions, where only 0.17% are fraudulent, the analysis moves beyond traditional accuracy to implement a cost-sensitive machine learning pipeline.

The goal is to minimize False Negatives (missed fraud) while maintaining a sustainable False Positive rate to ensure a seamless customer experience.

### Built With
* Python Programming using Jupiter Notebook
* pandas
* seaborn module
* matplotlib

### Key Features
* __Temporal Feature Engineering__: Decomposition of transaction timestamps into cyclical hourly and minute-based features.
* __Logarithmic Scaling__: Normalization of skewed transaction amounts to improve model convergence.
* __Synthetic Balancing (SMOTE)__: Implementation of Synthetic Minority Over-sampling Technique to bridge the 0.17% class imbalance.
* __Ensemble Modeling__: Utilization of a tuned Random Forest Classifier to capture non-linear fraud "fingerprints."
* __Explainable AI__: Feature importance analysis to identify the top statistical drivers ($V_{17}, V_{14}, V_{12}, V_{10}$) of fraudulent behavior.



### Conclusion
* __High Signal Detection__: Identified that 75% of the model's decision-making weight is derived from just four latent features.

* __Business Alignment__: By adjusting the classification threshold, the model effectively caught significantly more fraud than the baseline Logistic Regression while keeping customer friction within acceptable limits.



<!-- CONTACT -->
## Contact

Your Name - [Vivek Giri linkedin](https://www.linkedin.com/in/vivekgiri01/) - girivivek01@gmail.com

Profile Link: [Vivek Giri_ProjectProfile](https://vivekgriri.github.io/VivekGiri_portfolio/)

