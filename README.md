# Python_DataScinece
Python_DataScinece _Assignment _L1
Below mandatory Assignments need to be submitted.

Date Preparation and Exploration:

1. Reading a Titanic dataset from a CSV file

2. Detecting missing values
Missing values reduce the representativeness of the sample, and furthermore, might distort inferences about the population.
How many missing values are there in  age  Attribute of Titanic dataset

3.Imputing missing values

After detecting the number of missing values within each attribute, we have to impute the missing values since they might have a significant effect on the conclusions that can be drawn from the data.

Assign the missing value to the most likely port, which is Southampton

4. Exploring and visualizing data

After imputing the missing values, one should perform an exploratory analysis, which involves using a visualization plot and an aggregation method to summarize the data characteristics. The result helps the user gain a better understanding of the data in use.

a) Bar Plot which shows how many passengers survived and how many perished
b) Bar Plot which shows how many passesngers travelled by first class, second class and thrid class
c) Barplot which shows how many are male passengers and how many are female passengers
d) plot histogram of different ages
e) Stacked barplot's  to find out
 -which gender is more likely to perish during shipwrecks
 -Passenger survival by class
f) Box Plot which shows passenger survival by age


Visualization:

5. Read from sample superstore xl file  into pandas dataframe and perform below operations

a) Display Subcategory wise sum of profit
b) Exclude Office Furniture SubCategory
c) Sort SubCategory in Desc order
d) Categorywise sum of profit in pie chart
e) Line Chart yearwise sum of profit
f) Display Top 10 most profitable customers
g) scatter plot between profit and sales


6. Create dept dataframe and emp dataframe  with suitable data and perform inner , leftouter,RightOuter and FullOuter Joins based on common column Deptno.

Dept Data Frame will have
Deptno
Dname
Loc

Emp DataFrame will have below columns
Deptno
Eno
Sal



Descriptive and Inferential Statistics:
7. Suppose the height of men in the United Kingdom is known to be normally distributed with a mean of 177 centimeters and a standard deviation of 10 centimeters. If you were to select a man from the United Kingdom population at random, what is the probability that he would be more than 200 centimeters tall?

8.Let's take the mileage and horsepower of various cars and see if there is a relation between the two.

mpg = [21.0, 21.0, 22.8, 21.4, 18.7, 18.1, 14.3, 24.4, 22.8, 19.2, 17.8, 16.4, 17.3, 15.2, 10.4, 10.4, 14.7, 32.4, 30.4,
       33.9, 21.5, 15.5, 15.2, 13.3, 19.2, 27.3, 26.0, 30.4, 15.8, 19.7, 15.0, 21.4]
hp = [110, 110, 93, 110, 175, 105, 245, 62, 95, 123, 123, 180, 180, 180, 205, 215, 230, 66, 52, 65, 97, 150, 150, 245, 175, 66, 91, 113, 264, 175, 335, 109]


9.  Perform T-test on two classes that are given a mathematics test and have 10 students in each class. Determine if 2 distributions are identical or not.

class1_score = np.array([45.0, 40.0, 49.0, 52.0, 54.0, 64.0, 36.0, 41.0, 42.0, 34.0])

class2_score = np.array([75.0, 85.0, 53.0, 70.0, 72.0, 93.0, 61.0, 65.0, 65.0, 72.0])

10. The mean score of the mathematics exam at a national level is 60 marks and the standard deviation is 3 marks. The mean marks of a class are 53. The null hypothesis is that the mean marks of the class are similar to the national average.  Test this Hypothesis using Z – Test.

11. Calculate Pearson correlation coefficient between Girth and Volume in trees dataset( trees csv file) Pl mention what you draw from correlation coefficient

12.Suppose that you want to perform a hypothesis test to help determine whether the correlation between tree girth and tree volume is statistically significant.

Perform a two-sided test of the Pearson's product moment correlation between tree girth and volume at the 5% significance level,




Machine Learning Algorithms

12. Use Automobile price data Raw csv file :
⦁     Split data 80% to train 20% for test
⦁     predict price for 20% test data
⦁     Determine R-Squared value

13. The Pima Indians Diabetes Binary Classification dataset  csv file contains all of the data of female   patients of the same age belonging to Pima Indian heritage. The data includes medical data, such as glucose and insulin levels, as well as lifestyle factors of the patients. The columns in the dataset are as follows:
⦁     Number of times pregnant
⦁     Plasma glucose concentration of 2 hours in an oral glucose tolerance test
⦁     Diastolic blood pressure (mm Hg)
⦁     Triceps skin fold thickness (mm)
⦁     2-hour serum insulin (mu U/ml)
⦁     Body mass index (weight in kg/(height in m)^2)
⦁     Diabetes pedigree function
⦁     Age (years)
⦁     Class variable (0 or 1)
⦁     The last column is the target variable or class variable that takes the value 0 or 1, where 1 is positive or affected by diabetes and 0 means that the patient is not affected.
⦁     You have to build models that could predict whether a patient has diabetes or tests positive or not using logistic regression

14.  Use hotel.csv file and Show how to cluster hotel location data with K-means Clustering. That is perform K-means clustering on hotel location data to identify whether the hotels are located in the same district.
 Using k-means cluster location data for 3 clusters.

