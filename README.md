# Quiz-Data-Analytics

1. Code to remove duplicate records from a dataset named df
A. df.drop_duplicates()

2. Code to slice list to get the first 3 values
holidays= ['Thanksgiving', 'Christmas', 'Halloween', 'Easter', 'Hanunukah', 'Cinco De Mayo', 'Kwanzaa']
A. holidays[0:4]

3. code to give number of rows and columns of data
A. df.shape

4. Write the code to import the travelDestinations.csv dataset into a data frame.

Your Answer:
import pandas as pd
import numpy as np


location = "travelDestinations.csv"
df = pd.read_csv(location)
df

5. Code to list column names along with number of records with missing values in those columns
A. df.isnull().sum()

6. What does the melt function do?

Your Answer:
reshapes data from wide to long

7.What does the y-intercept tell you?

Your Answer:
The dependent variable, also where the line intersects the y-axis

8. What can violin plots tell us?

Your Answer:
The range of the dependent variable on the y-axis plotted as points and also the range of the independent variable along the x-axis plotted as points

9. We can have columns with string values when building a linear regression model.
A. False

10. What can a correlation table tell you?

Your Answer:
whether 2 variables have a positive correlation (when both variables near +1 and both variables near -1) or negative correlation (when one increases and the other decreases). Correlation coeffcient's >0.5 are good to look at. 

11. Which library is this line of code from?
lm.fit(X, df.price)

A. sklearn

12. Which library in Python is the seaborn library built on top of?

A. matplotlib

13. Which library do we need to create a boxplot as such:
sns.boxplot(data=df)

A. seaborn

14. What library do we need in order to use decision trees?

A. sklearn 

15. Which library do we need to import a spreadsheet?

A. pandas

16. df.head(50)

A. Your Answer:
print out the first 50 rows of the table

17. What does this code do?

df.fillna('awesome')

Your Answer:
Fills the word "awesome" in the space with missing values

18. What does this code do?

df.groupby(['gender'])['age'].mean()
Your Answer:
It groups by average for gender and age 

19. What does this line of code output?

df.corr()
Your Answer:
correlation coefficient

20. How big is our training data set here?

X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.25, random_state=90)

A. 75%

