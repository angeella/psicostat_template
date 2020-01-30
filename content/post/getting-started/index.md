---
authors:
- admin
categories:
- Demo
date: "2016-04-20T00:00:00Z"
draft: false
featured: false
image:
  caption: ''
  focal_point: ""
  placement: 2
  preview_only: false
lastmod: "2019-04-17T00:00:00Z"
projects: []
subtitle: 'Short list Python information'
summary: Short list Python information
tags:
- Python
title: 'Start with Python '
---

# **Introduction to Python**
## **To start**

- There are two popular versions of Python (**2.7** and **3.5**);

- Ide $\rightarrow$ Pycharm, Netbeans, Eclipse etc, I suggest **Spyder** (similar to Rstudio);

- **Jupyter Notebook** $\rightarrow$ web application to create and share documents (code, formulas, text, etc);

- **Anaconda** $\rightarrow$ contains R, Python, various IDE, Anaconda navigator (GUI), Anaconda Prompt and Jupyter Notebook.

## **Some tutorials**

- <https://docs.python.org/3/tutorial/> $\rightarrow$ official python tutorial;
- <https://courses.edx.org/courses/course-v1:UCSanDiegoX+DSE200x+1T2018/course/> $\rightarrow$ Videos, exercises, etc;
- <http://www.pymvpa.org/tutorial.html> $\rightarrow$ Multivariate Pattern Analysis.

##  **Some basic information**

- Python uses **white space** to identify code blocks (Avoid using tabs and prefer whitespaces) $\rightarrow$ $4$ spaces per indentation level;
- No $;$ at the end of each line;
- No variable declaration as R;
- assignment operator $=$, i.e not <-.

```python
# One line comment

"""
Two lines comment
"""
```

## **Some useful packages**

- **Numpy** $\rightarrow$ array

- **Scipy** $\rightarrow$ math (<https://docs.scipy.org/doc/scipy-0.18.1/reference/index.html>)

- **Pandas** $\rightarrow$ dataframes (<https://pandas.pydata.org/pandas-docs/stable/>)

- **Matplotlib** $\rightarrow$ plot (<https://matplotlib.org/>)

- **Seaborn** $\rightarrow$ plot (<https://seaborn.pydata.org/>)

- **scikit learn** $\rightarrow$ Classification, Regression, Clustering etc (<https://scikit-learn.org/stable/tutorial/index.html>)

- **statmodels** $\rightarrow$ Models (<http://www.statsmodels.org/devel/index.html>)

## **Install packages**

- **Anaconda Prompt** $\rightarrow$ <https://anaconda.org/anaconda/repo>
  Example: 
```{bash, eval=FALSE}
conda install -c conda-forge numpy
```
  
- **Anaconda Navigator** $\rightarrow$ enviroments $\rightarrow$ search package

In both cases, it is useful to create an **enviroments**:

```{bash, eval=FALSE}
conda create -n yourenvname python=x.x anaconda
activate yourenvname
```

and then install packages into yourenvname.
