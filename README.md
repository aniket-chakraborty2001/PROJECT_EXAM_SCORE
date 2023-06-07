# Project Name : PROJECT_EXAM_SCORE
This project gives us the understanding of the exam scores of different students in different subjects. We perform data understanding, data manipulation and data visualization in this project.
### Introduction:
Here in this project I use R programming language to undertsnad, work and analysis a data set called **Exam_Score** data set, which is created by me. This data set contains different scores of different subjects of different students.
### Into the project Explanation:

#### 1. Installing and loading Packages:
Here I use the main data handling package in R known as tidyverse package. Under this packages I Use some libraries:
* tidyverse library
* dplyr library
* ggplot2 library

#### 2. Reading the file:
In step two I read the contains on the **.csv** file by using **read.csv()** function which comes under the readr library of tidyverse package.

#### 3. Data Understanding:
This is the third step of thi process. This includes,differnet works that I do to understand the data . They include:
* Previewing the data set
* Getting structure of the data set
* Getting summary statistics of the data
* Getting first few rows of the data
* Getting number of rows and columns of the data set.

#### 4. Data manipulation:
This step is alos known as the data preparation step. In this step we address missing values, correct errors of the data set, transfor the data into a useable format so that the data frame can be analysed further. This includes different functions such as:
* select()- to select variables
* mutate()- to create new variables based on values
* filter()- to filter rows using a specific condition
* group_by()- to organize all types of objects
* summarize()- to calculate Mathematical values
* There are other functions too

#### 5. Data analysis by Visualization:
In this step I use the ggplot() function which comes under the ggplot2 library that comes under the tidyverse package. This library help to make publixcation level graphical input. Some plotting objects are:
* Dot plot or scatter plot
* Bar chart
* Line chart
* Histogram
* Pie chart
* Density Chart
* Boxplot
* There are other plot objects too.

#### Conclusion part:
* Average Marks Score in Maths is 82.12
* Minimum munber scored in Maths is 45
* Maximum Number Scored in Maths is 99.
* There is only a person who get a Remark 'Good' after getting 90+ in maths
* Male have higher variability in Maths and Science Scores
* Male have higher variability in English and Bengali Scores
* Male have higher variability in Science and Geography Scores.
* Our study shows that male are grater than female,there can be some reasons behind this.
* Number of females are considerably less than the number of males
* There may be a bias in the data
* Age of students shows a great interpretation of our result.
* For 21 years old persons, there are more variability in the Marks Scored in exam
