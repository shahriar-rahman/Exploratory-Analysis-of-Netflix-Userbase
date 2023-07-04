===========================================================================
# Exploratory Analysis of Netflix Userbase Data

By leveraging the power of data analysis and engineering tools such as Matplotlib, Pandas, MisingNo, and Seaborn, an in-depth 
and visual exploration is conducted in order to discover key insights about age demographics, age, and gender distribution, subscription types, and so forth
This notebook might serve as a hands-on experience  for beginners in the field of data science.

![alt text](https://github.com/shahriar-rahman/Prediction-of-Compressive-Strength-using-Multi-Layered-Perceptron/blob/main/img/git_img%20(1).jpg)

### Introduction:
Several types of research have indicated that concrete strength development is mostly determined by the water-cement ratio 
(w/c ratio) with the amalgamation of other ingredients. Despite displaying a pattern of practical acceptability of this theory, 
there have been some deviations from the norm. Codes consist of various empirical equations that can be applied to achieve 
a proper prediction of compressive strengths, which are usually based on experiments without using supplementary 
cementitious materials such as fly ash, blast furnace slag, and so forth. Therefore, it is crucial to investigate the validity of 
the relationships with the aforementioned materials in order to get better interpretability in circumventing this particular problem. 

### Objective:
The primary incentive of this research is to:
* Initiate an exploratory analysis of data to find the patterns of the feature that makes up the data.
* Conduct a comparative analysis of feature transformation algorithms to find the most suitable for utilization.
* Experiment with different Hyper-parameters to obtain a well-organized tuning for the MLP model.
* Locate a viable approach to solve this problem to develop an efficient model capable of correctly predicting 
the strength of the concrete, given certain parameter exists.

![alt text](https://github.com/shahriar-rahman/Prediction-of-Compressive-Strength-using-Multi-Layered-Perceptron/blob/main/img/git_img%20(2).jpg)

### Approach:
This research is classified into 5 steps:
1.	Identifying the problem and its data sources.
2.	Constructing raw data into clean processed data and analyzing it using both Jupyter Notebooks and IDE.
3.	Scaling the data with 3 different transformation algorithms for comparisons and us the best-suited one for this problem.
4.	Experiment and Diagnose in order to achieve the best Hyper-parameters for building an efficient model.
5.	Result Analysis for both training and test data.

Project Organization:
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

### Study Flowchart:
![alt text](https://github.com/shahriar-rahman/Prediction-of-Compressive-Strength-using-Multi-Layered-Perceptron/blob/main/img/flow_chart.JPG)

### Results:
| Data Type | Mean Squared Error | R-Squared Error |
|----------- | --------------------- | ------------------ |
| Training | 0.077 | 0.86 |
| Test     | 0.077 | 0.85 |

* Training Loss Curve:
![alt text](https://github.com/shahriar-rahman/Prediction-of-Compressive-Strength-using-Multi-Layered-Perceptron/blob/main/figures/ide_graphs/training_loss_curve.png)

* Training set Ground truth vs Estimated values:
![alt text](https://github.com/shahriar-rahman/Prediction-of-Compressive-Strength-using-Multi-Layered-Perceptron/blob/main/figures/ide_graphs/training_fit_data.png)

* Training Error Density Plot:
![alt text](https://github.com/shahriar-rahman/Prediction-of-Compressive-Strength-using-Multi-Layered-Perceptron/blob/main/figures/ide_graphs/training_error_distribution.png)

* Test Loss Curve:
![alt text](https://github.com/shahriar-rahman/Prediction-of-Compressive-Strength-using-Multi-Layered-Perceptron/blob/main/figures/ide_graphs/test_loss_curve.png)

* Test set Ground truth vs Estimated values:
![alt text](https://github.com/shahriar-rahman/Prediction-of-Compressive-Strength-using-Multi-Layered-Perceptron/blob/main/figures/ide_graphs/test_fit_data.png)

* Test Error Density Plot:
![alt text](https://github.com/shahriar-rahman/Prediction-of-Compressive-Strength-using-Multi-Layered-Perceptron/blob/main/figures/ide_graphs/test_error_distribution.png)


### Packages and Modules used:
* os
* sys
* math
* pickle
* random
* pandas
* sklearn
* seaborn
* matplotlib
* missingno

===========================================================================

