# Titanic-EDA
Exploratory Data analysis of the Titanic disaster dataset

### Prerequisite:
* [NumPy](http://www.numpy.org/)
* [IPython](http://ipython.org/)
* [Pandas](http://pandas.pydata.org/)
* [SciKit-Learn](http://scikit-learn.org/stable/)
* [SciPy](http://www.scipy.org/)
* [StatsModels](http://statsmodels.sourceforge.net/)
* [Patsy](http://patsy.readthedocs.org/en/latest/)
* [Matplotlib](http://matplotlib.org/)

### Goal for this Notebook:
Show a simple example of an analysis of the Titanic disaster in Python using a full complement of PyData utilities. 

### This Notebook will show basic examples of:
#### Data Handling
*   Importing Data with Pandas
*   Cleaning Data
*   Exploring Data through Visualizations with Matplotlib

#### Data Analysis
*    Supervised Machine learning Techniques:
    +   Logit Regression Model
    +   Plotting results
    +   Support Vector Machine (SVM) using 3 kernels
    +   Basic Random Forest
    +   Plotting results

#### Valuation of the Analysis
*   K-folds cross validation to valuate results locally
*   Output the results from the IPython Notebook to Kaggle


### Major insights extracted:
1. Females were given higher priority in the rescue operation than male\
2. The first class people were given higher priority than the second class than the third class
3. The features such as Age, Siblings Onboard and Parents onboard didn't have major influence on the survival probability
4. A better way for filling the missing values for Age column is explained by extracting info from Name column

### References:
1.https://github.com/agconti/kaggle-titanic
2.https://github.com/VinayBN8997/Titanic-EDA
