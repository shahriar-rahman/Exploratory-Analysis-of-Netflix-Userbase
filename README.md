===========================================================================
# Exploratory Analysis of Netflix User Base Data

By leveraging the power of data analysis and engineering tools such as Matplotlib, Pandas, MisingNo, and Seaborn, an in-depth 
and visual exploration is conducted in order to discover key insights about age demographics, age, and gender distribution, 
subscription types, and so forth. This notebook might serve as a hands-on experience for beginners in the field of data science.

<div align="center">
    <img width="100%" src="img/netflix (3).gif" alt="Netflix1.gif" >
</div>

<br/><br/>

### ◘ Introduction
The acquired dataset provides a sample Netflix user base, showcasing a plethora of monthly revenue, user subscriptions, 
activity, and account details. Each sample represents a unique user, identified by their identification as a user ID, and includes
information such as the subscription type which is categorized as Basic, Standard, or Premium. The revenue generated monthly 
from their subscription is also included along with the date of joining Netflix labeled as “Join Date”, the date of their last payment
as “Last Payment Date”, and the country in which they resided.

Additional columns have been included to provide insights into user behavior and preferences, which include the type of devices, 
case in point, Smart TV, Mobile phone, Desktop, and Tablet. Moreover, the total watch time (in minutes), and account status 
including whether the account is active or not is also provided. It can be used to analyze and model user trends, preferences, 
and revenue generation within a hypothetical Netflix user base.

<br/><br/>

### ◘ Objective
The primary incentive of this research is to:
* Process dataset by analyzing its integrity, missing values, duplicated values, and so forth.
* Perform various clean-ups, if required, and improve accessibility for more convenient exploratory analysis.
* Conduct exploratory analysis using a myriad of graphing tools to reach a conclusion.
* To reach a proper decision on which model to apply to the processed dataset in a future project to achieve the ideal optimization 
tuning and hopefully, a better outcome in the model's generalization.

<br/><br/>

![alt text](https://github.com/shahriar-rahman/Exploratory-Analysis-of-Netflix-Userbase/blob/main/img/netflix%20(3_Cropped).jpg)

<br/><br/>

### ◘ Approach
This research is classified into 2 steps:
1.	Data Wrangling: Where the dataset is extracted, tested, cleaned, processed, and stored in memory.
2.	Feature Analysis: Where the processed data is then explored thoroughly to acquire a viable insight.

<br/><br/>

### ◘ Methodologies & Technologies applied
* Diagnose and fix structural errors
* Check and Clean data
* Address duplicates & outliers
* Logical feature amalgamation to construct a unique variable
* Univariate inspection
* Bivariate inspection
* Feature correlations
* Seaborn & Matplotplib visualizations

<br/><br/>

[alt text](https://github.com/shahriar-rahman/Exploratory-Analysis-of-Netflix-Userbase/blob/main/img/edaFlowchart.png)

<br/><br/>

### ◘ Project Organization
------------
    ├── LICENSE
    │
    ├── README.md          <- The top-level README for developers using this project.
    │
    ├── data
    │   └── processed      <- The final, canonical data sets for modeling.
    │   └── raw               <- The original, immutable data dump.
    │
    │
    ├── notebooks          <- Jupyter notebooks for EDA
    │                         		
    │
    ├── figures               <- Generated graphics and figures to be used in reporting using Jupyter Notebooks
	|
    │
    ├── img            <- Project related files
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable, so that src can be imported
    │
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io

--------

<br/><br/>

### ◘  Modules required
* Jupyter
* pandas
* missingNo
* matplotlib
* seaborn

<br/><br/>

===========================================================================

