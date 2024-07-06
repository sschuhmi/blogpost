## Project "Write a Data Science blog post"

This project is included within Udacity´s Data Scientist Nanodegree Program.

### Table of Contents
 
1. [Project Motivation](#motivation)
2. [Survey Data](#surveydata)
3. [Provided Files](#files)
4. [Installation](#installation)
5. [Results](#results)
6. [Licensing, Authors, and Acknowledgements](#licensing)

## Project Motivation <a name="motivation"></a>

To write a Data Science blog post represents a part of the Udacity Data Scientists Nanodegree Program.</br> 
Therefore, I analyzed Stack Overflow’s Annual Developer Survey data from the year 2017. 

## Survey Data <a name="surveydata"></a>

The Stack Overflow survey includes around 64k of reviews from more than 200 countries and territories all around the world. The focus of the survey is to understand significant aspects of jobs in software development and data analytics.</br>
The survey contains of the following two CSV files:
<ul>
  <li>The schema of the survey data, containing information about the more than 150 columns (i.e., questions) used within the set
  <li>The survey results themselves, containing thousands of individual answers to the survey questions 
</ul>
Further information about the original dataset can be found at StackOverflow (https://survey.stackoverflow.co/2017)

## Provided Files <a name="files"></a>

The following files are provided within this project:
<ul>
  <li><b>BlogPost.ipynb:</b> Jupyter Notebook containing the Python code for the analysis</li>
  <li><b>BlogPost.hmtl:</b> HTML-Export of the Jupyter Notebook</li>
  <li><b>README.md:</b> This file</li>
</ul>

## Installation & Libraries <a name="installation"></a>

To analyze the data, I used Python (version 3.9.19) in combination with Jupyter Notebooks (version 6.4.5). The code is provided within the ipynb-File and should run on any Python 3 version (3.0.* or higher) without any issues. It was tested using the Anaconda distribution of Python.</br>

Here are the additional Python libraries used within this project:
<ol>
  <li>Numpy (v1.26.4)</li>
  <li>Pandas (v1.3.4)</li>
  <li>Matplotlib.PyPlot (v3.9.0)</li>
  <li>Seaborn (v0.13.2)</li>
  <li>SciKit Learn (v1.4.2) – LinearRegression model, train_test_split, R2 Score metric</li>
</ol>

You will need to download Stackoverflow’s 2017 Annual Developer Survey and put it in your specific folder.</br> 
You can find the data to download [here](https://insights.stackoverflow.com/survey). </br>

## Results <a name="results"></a>

The analysis focused on questions concerning the preferred work starts of developers.</br>
The main findings of the code can be found in my blog post available [here](https://sschuhmi.github.io/2024/07/05/BlogPost.html) at GitHub pages.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Thanks to Stack Overflow for providing the data. The Licensing for the data and other descriptive information can be found at this [Kaggle](https://www.kaggle.com/stackoverflow/so-survey-2017/data) link.
