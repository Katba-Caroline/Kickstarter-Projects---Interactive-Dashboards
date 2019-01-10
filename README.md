
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The libraries/packages used are:
- numpy
- pandas
- datetime
- pycountry
- [Plotly](https://plot.ly/#/)
- seaborn
- matplotlib

You might need to install pycountry and plotly, but otherwise, there should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*



## Project Motivation<a name="motivation"></a>

For this project, I was interested in using kickstarter dataset from Kaggle to answer the following questions:

1. What percentage of campaign succeed or fail?
2. How many campaigns per year have there been on Kickstarter since 2009?
3. How many campaigns in each category have there been on Kickstarter since 2009 per year? and how many were successful?
4. How many total backers per category since 2009? (credence to the crowd-sourcing claim)
5. What is the average run time per campaign? How quickly do you know if your campaign will succeed or fail?
6. How global is the Kickstarter community? How much has each country contributed?
7. Which campaign categories are more popular during which months? and which campaign categories raise more money during which months?

Using interactive visualizations.

## File Descriptions <a name="files"></a>

The notebook 'Kickstarter_project.ipynb' strives to answer the questions above using simple exploratory data analysis using interactive visualizations. This notebook follows the approach of Cross-Industry Standard Process for Data Mining (CRISP-DM). I strongly recommend viewing it in nbviewer for the full experience. 

The data file:

- ks-projects-201801.csv (2).zip : This is the data downloaded from the Kaggle website. It contains information about kickstarter since 2009 untill 2018. All the cleaning code, can be found in the notebook. 

The data has been taken from Kaggle's website [here](https://www.kaggle.com/kemical/kickstarter-projects).


## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://katba-caroline.com/analyzing-kickstarter-campaigns-with-interactive-visualizations/).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Kaggle for the data.  You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/c/titanic/data).  

Also credits to https://github.com/jjrunner/stackoverflow/blob/master/README.md for the readme template.
Otherwise, feel free to use the code here as you would like! 
