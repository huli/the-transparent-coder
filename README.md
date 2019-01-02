# Analysis of StackOverflow data from 2011 to 2018

### The motivation
I started coding with C# more than 10 years ago. With my data science projects my focus was shifting more to Python programming. When I got my hands on the extensive survey from stack overflow I decided to check some of my assumptions about the distribution of Python and C# among the developers. Though the two languages are not direct competitors the examination of their trends can be of interest. I also took the opportunity to analyze some behavior differences between the two groups. \
\
The project is also an assignment from the Data Science Nanodegree Program @[Udacity](http://www.udacity.com). 

### The project
This project does analyze the distribution of Python and C# on StackOverflow. It also does examine behavioral differences between the two groups by analyzing the different groups and their workout behavior in 2018 (This is done with two different approaches: Bootrapping and the Chi-Square Test of Independence).

#### Main files
* *time_series.ipynb* - Analysis of the trends for C# and Python
* *in_depth.ipynb* - Comparison of C# and Python developers in 2018
#### Supporting files
* *overview.ipynb* - Initial data preparation and exploration
* *build_combined_data.ipynb* - Building composite data set from the individual years

### The results
There were 3 key findings in the project:
* The percentage of C# developers did decrease in the last years significantly 
* The proportion of Python developers did gain a lot of momentum after 2017
* On average, the Python programmers are working out more often than the C# coders


### Data & Instructions:
* The data for this repository can be found directly on stackoverflow: \
https://insights.stackoverflow.com/survey/
* The code does make use of common data science and statistic libraries like pandas, numpy, scipy and matplotlib
