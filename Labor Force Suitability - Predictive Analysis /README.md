<!-- PROJECT LOGO -->
<br />
<div align="center">
<p align="center">
  <img width="460" height="auto" src="https://github.com/vivekgriri/Datascience_projects/blob/main/images/PA.jpg">
</p>


  <h1 align="center">Predictive Analysis of Labor Force Suitability</h1>
  <p align="center">
    
To identify underserved populations and help recruiters find viable candidates for labor opportunities by scoring "non-skill behaviors" derived from real-time survey responses.

  </p>
</div>

<!-- ABOUT THE PROJECT -->
## About The Project



The Data: This project utilizes the 2019 American Time Use Survey (ATUS) Respondent Data from the Bureau of Labor Statistics (BLS). The dataset provides a comprehensive look at how individuals spend their time, their employment status, income levels, and demographic details like family status and spousal employment.



### Built With
* Python Programming using Jupiter Notebook
* pandas
* seaborn module for data manipulation/visualization
* matplotlib
* kmodes for categorical clustering
* scikit-learn and scipy for clustering and scaling

### Steps

__Method of Analysis:__ Applied a Predictive Modeling approach using the CRISP-DM (Cross-Industry Standard Process for Data Mining) methodology. The analysis involved:

__Data Preprocessing:__ Cleaning the data by handling missing values (using median imputation and forward/backward filling) and label encoding categorical variables.

__Clustering:__ Utilizing K-Modes clustering (specifically designed for categorical data) to group survey respondents into distinct segments based on their behavioral and demographic profiles.

__Correlation Analysis:__ Evaluating how non-technical time use (e.g., time spent with family) impacts a candidate's likelihood of seeking employment.


### Summary 

__Data Cleaning Logic:__ * Handling Nulls: You defined a threshold to drop columns with >50% missing data.

__Imputation:__ You used ffill, bfill, and a custom function rep_data to replace specific survey error codes (-1, -2, -3, -4) with the median of the column.

__Feature Engineering:__ Used Label Encoding to transform categorical survey responses into numerical values suitable for machine learning models.

__Clustering Approach:__ Implemented AgglomerativeClustering and KModes. K-Modes is particularly effective for this dataset because survey data is often categorical rather than continuous.


<!-- CONTACT -->
## Contact

Your Name - [Vivek Giri linkedin](https://www.linkedin.com/in/vivekgiri01/) - girivivek01@gmail.com

Profile Link: [Vivek Giri_ProjectProfile](https://vivekgriri.github.io/VivekGiri_portfolio/)

