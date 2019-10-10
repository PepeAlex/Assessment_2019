# TIPS Dataset – Project
## Project 2019/2
### Institution: Galway-Mayo Institute of Technology - GMIT
### Course: Higher Diploma in Data Analytics
### Module: Fundamentals of Data Analysis – 2º sem/2019
### Author: Alexander Pepe

> This assessment is research about TIPS Dataset to Fundamentals of Data Analysis by Dr. Ian McLoughlin as lecturer. I have written some Python codes to describe this dataset and I used some Python’s libraries and Jupyter as part of current project.
This Project is avaiable at https://github.com/PepeAlex/Assessment_2019 .

# INTRODUCTION

The dataset describe what one waiter recorded information about each tip he received over a period of a few months working in one restaurant. He collected several variables. A data frame with 244 obsevations on the lollowing 8 variables:
- TipPercentage - a numeric vector, the tip written as a percentage (0-100) of the total bill.
- Bill - a numeric vector, the bill amount (dollars).
- Tip - a numeric vector, the tip amount (dollars).
- Gender - a factor with levels Female Male, gender of the payer of the bill.
- Smoker - a factor with levels No Yes, whether the party included smokers.
- Weekday - a factor with levels Friday, Saturday, Sunday, Thurday, day of the week.
- Time – a fator with levels Day Night, rough time of day.
- PartySize – a numeric vector, numbers of people in party.
https://rdrr.io/cran/regclass/man/TIPS.html

# DATA SET

This data can be easily viewed on the internet, but for this project I used the link recommended by the lecturer, such as following the link https://github.com/mwaskom/seaborn-data/blob/master/tips.csv

# DESCRIPTION

To complete this Project, I have used some programmes and their libraries; below is a short description of each:

### PYTHON
- Python is an interpreted, object-oriented, high-level programming language with dynamic semantics. Its high-level, built-in data structures, combined with dynamic typing and dynamic binding, make it very attractive for rapid application development, as well as for use as a scripting or glue language to connect existing components together. https://www.python.org/doc/essays/blurb/
   - Python Libraries:
      - Matplotlib: is a Python 2D plotting library which produces publication-quality figures in a variety of hardcopy formats and interactive environments across platforms. Matplotlib can be used in Python scripts, Python and IPython shells, Jupyter notebook, web application servers, and four graphical user interface toolkits. https://matplotlib.org/
      - Pandas: is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language. Pandas is a NumFOCUS sponsored project. This will help ensure the success of development of pandas as a world-class open-source project, and makes it possible to donate to the project. https://pandas.pydata.org/
      - Seaborn: is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics. https://seaborn.pydata.org/
### CMDER
CMDER is a software package created out of the absence of suitable console emulators in Windows. It is based on quality software, with a Monokai color scheme and a custom prompt layout.
https://cmder.net/
### GITHUB
GitHub is a Git repository hosting service, but it adds many of its own features; while Git is a command line tool, GitHub provides a Web-based graphical interface. It also provides access control and several collaboration features, such as a wikis and basic task management tools for every project. https://techcrunch.com/2012/07/14/what-exactly-is-github-anyway/?guccounter=1&guce_referrer_us=aHR0cHM6Ly93d3cuZ29vZ2xlLmNvbS8&guce_referrer_cs=QdRUp8Vpgm9JNIVT4qpoSA.
### JUPYTER NOTEBOOK
Project Jupyter is a non-profit, open-source project, born out of the IPython Project in 2014 as it evolved to support interactive data science and scientific computing across all programming languages. Jupyter will always be 100% open-source software, free for all to use and released under the liberal terms of the modified BSD license. https://jupyter.org/about

# Analysing

I opened Jupyter Notebook and I imported the data set with "pandas" library. After that I wrote some codes to show how to manipulate the data and describe a little about it.
My codes printed informations such as:
- names and numbers of variables, numbers of samples, datatype used in each column and memory usage.
![Alt text](https://github.com/PepeAlex/Assessment_2019/blob/master/info.png)

- Total numbers of columns and rows in this dataset.
- column names of the data.
![Alt text](https://github.com/PepeAlex/Assessment_2019/blob/master/row%26columns.png)

- There are statistical summary as count variables, mean, standard deviation, 25%th, 50%th and 75%th on each column.
- List randow 5 rows of the data.
![Alt text](https://github.com/PepeAlex/Assessment_2019/blob/master/summary.png)

# Statistic

In this part of the project I manipulated the data also using "pandas" library. I found a "mean", a "max", a "min" and a "median" for each variable per "gender".
![Alt text](https://github.com/PepeAlex/Assessment_2019/blob/master/value_variable.png)

# Graphic

Finally, I used libraries as matplotlib.pyplot, seaborn and pandas to easily describe TIPs data set by graphics.

- Relation betwween TIP and variable
![Alt text](https://github.com/PepeAlex/Assessment_2019/blob/master/boxplot.png)
![Alt text](https://github.com/PepeAlex/Assessment_2019/blob/master/boxplot1.png)

- I also used the HISTOGRAM graphic type to illustrate my data
![Alt text](https://github.com/PepeAlex/Assessment_2019/blob/master/histogram.png)

- I manipulated my data and used SCATTER PLOT to show it per "total_bill" versus "tip".
![Alt text](https://github.com/PepeAlex/Assessment_2019/blob/master/scatterplot.png)

# Conclusion

The TIPs Data set is a data really interesting to work because there are differents variable. I tried to use my knowledge imparted during my time studying at GMIT.

I used Pynton through the Jupyter Notebook and I liked it. The Jupyter Notebook has a interfece mondern and easy to visualize your print. I widely used pandas to import the data and used matplotlib and seaborn to create graphics to make my project more easily to see.

This project is a first step of theproject of the semester end and I am very excited to next step.

# Reference

1. Python - https://www.python.org/doc/essays/blurb/
2. Matplotlib - https://matplotlib.org/
3. Pandas - https://pandas.pydata.org/
4. Seaborn -  https://seaborn.pydata.org/
5. CMDER -  https://cmder.net/
6. GITHUB - https://techcrunch.com/2012/07/14/what-exactly-is-github-anyway/?guccounter=1&guce_referrer_us=aHR0cHM6Ly93d3cuZ29vZ2xlLmNvbS8&guce_referrer_cs=QdRUp8Vpgm9JNIVT4qpoSA
7. Jupyter Notebook - https://jupyter.org/about
8. Data Set - https://github.com/mwaskom/seaborn-data/blob/master/tips.csv
