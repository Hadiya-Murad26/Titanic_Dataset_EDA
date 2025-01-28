# Titanic Dataset EDA

## <u>**Author:**</u>
- Hadiya Murad Hadi
## <u> **Contact:**</u>
hadiyamurad96@gmail.com

## **ABOUT THE DATASET**
---
- `DESCRIPTION: ` This dataset provides information about the passengers aboard the RMS Titanic, which sank in the North Atlantic Ocean in 1912 after colliding with an iceberg.
- `CONTENT: ` Each passenger (row) has values for various attributes, including survival status, class, name, gender, age, number of siblings/spouses aboard, number of parents/children aboard, ticket number, fare, cabin, and port of embarkation.
- `ACKNOWLEDGEMENTS:` This information is derived from the original passenger lists of the Titanic. The dataset has been made available for educational and analytical purposes, allowing data scientists to explore and model real-world data.
- `INSPIRATION: ` The Titanic dataset has been widely used in the data science community for learning and competitions. It provides a compelling real-world scenario for developing predictive models and understanding the factors that contributed to survival during the disaster.
- `TASK: ` We intend to create an Exploratory Data Analysis (EDA) on this dataset. The EDA will serve as a foundation for Data Wrangling techniques aimed at cleaning and normalizing the data. We will meticulously document each step, ultimately drawing meaningful conclusions from the dataset.
---

# <u>**Importing the Libraries**</u>


1.   <u>Pandas</u> : Data manipulation and Analysis Library.
2.   <u>Numpy</u> : Numerical computing library
3.   <u>Seaborn</u> : Statistical data visualization library.
4.   <u>Matplotlib</u> : Data Visualization Library

## **Insight #1**
---
- We'll see how many of the survived passengers were the passengers of class 1, 2 and 3.
- For that we will use the columns `Survived` and `Pclass`.
- Also we will use the data visualization technique.
- Using data visualization to visualize the data for the abpve insight.
- Using bar graph to see how many survived and did not survive based on the passenger class `Pclass` column.
- Reason for using bar graph?
-  Bar graphs offer a versatile and effective means of data representation.
Whether it's comparing categories, visualizing frequency data, or emphasizing magnitude differences.

## **INSIGHT #2**
---
- For this insight we are looking at the distribution of ages.
- This shows how passengers were distributed among different ages.

## **INSIGHT #3**
---
- It shows the stats of fare of `Pclass 1`.
- The describe() function is applied to the fare_1st_class Series to compute descriptive statistics, such as count, mean, standard deviation, minimum, 25th percentile, median, 75th percentile, and maximum values.
- Overall, this code filters the DataFrame to isolate data related to first-class passengers, computes descriptive statistics for their fares, and generates a histogram to visualize the distribution of fares among first-class passengers.

## **INSIGHT #4**
---
- This code snippet calculates the correlation between the 'Age' and 'Fare' variables and then creates a scatter plot to visualize the relationship between passenger age and fare. The scatter plot allows us to observe any potential patterns or trends in the data and assess the strength and direction of the correlation.

## **INSIGHT #5**
---
- This shows the survival rate of different people embarked at different ports.
- df.groupby('Embarked') groups the DataFrame df by the 'Embarked' column, which represents the port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

## **INSIGHT #6**
---
- Survival count based on siblings and spouses aboard.
- This count plot allows for visual comparison of the survival count for different categories of the ` SibSp ` variable, showing how the number of siblings/spouses aboard may have influenced survival rates. The hue differentiation helps to distinguish between survivors and non-survivors within each category.

## **INSIGHT #7**
---
- This histogram allows for visual comparison of the age distribution between male and female passengers. By using different colors for each gender, it's easier to observe any differences or patterns in the age distributions.

## **INSIGHT #8**
---
- This bar chart visualizes the ages of individuals in our dataset.
- Each bar represents the age of an individual at a specific record number. The height of the bar indicates the age of that individual

That concludes the EDA on Titanic Dataset. 
