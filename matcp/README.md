# Reproducing locally
```shell
pip install -r requirements.txt
jupyter notebook
```
Only run notebook "sprint_2.ipynb" - the others are kept as history/testing only.

###### 3.2.2 KPIs and Statistical Analysis
Managing public green spaces efficiently implies considering some KPI (key performance indicator) like: water or energy consumption, most used pieces
of equipment, and park users’ profile by age, for instance. The best practices concerning Statistical Analysis should be considered in the elaboration of
US09 to US11.

• US09 - As a GSM, I want to know the exact costs referring to water
consumption of specific green space so that I may manage these expenses efficiently. Therefore, within this US, the aim is to carry out a
statistical analysis concerning the water consumption costs in all parks.
The ”WaterUsed.csv” file provide the necessary data to carry out the study. 
This file records daily water consumption (in m3) since the day each park opened. The amount paid for water is 0.7 AC/m3 , up to a consumption of 50 m3, with a fee of 15% added for higher consumption
levels.

The data file contains records of the following information: ”Park Identification”, ”Year”, ”Month”, ”Day”, ”Consumption”. 
Consider this data in order to obtain the following outcomes:

– Barplot representing monthly water consumption, as a result of
the following specifications given by the user: time period (StartMonth, EndMonth) and park identification.

– Average of monthly costs related to water consumption as a result
of the following specifications given by the user: number of parks
to be analyzed, and park identification.

– Consider the water consumption of every day that is recorded.The aim is to analyze and compare statistical indicators between
the park with the highest and lowest water consumption. For these two parks, perform the following tasks and compare results:
∗ Calculate the mean, median, standard deviation, and the coefficient of skewness;
∗ Build relative and absolute frequency tables (classified data), considering 5 classes;
∗ Check if the data has outliers, using the outlier definition as values that deviate from the median by more than 1.5 times
the interquartile range;
∗ Graphically represent data through histograms with 10 classes.

• US10 - As a GSM, I want to know which piece(s) of equipment is/are used in each day so that I can understand the users’ preferences. Consider that the park has the following equipment: walking paths, children’s playground, picnic area, and exercise machines (gymnastics equipment). At the park exit there is an electronic device with a list of all
the equipment, in which the user(s) must indicate the equipment they used that day.
In the file ”EquipmentUsed.csv” the choices of 1000 users are recorded. Make a pie chart representing, in percentage, the use of each piece of
equipment.

• US11 - As a GSM, I want to be able to collect data from the user portal
about the use of the park, so that I may understand the use of the park
by different age groups. To analyse the use of the park by age groups,
a three-question survey was inserted in the user portal:
Question 											Answer type
Age range											1 - Child (up to 15 years old)
													2 - Adult (between 16 and 65 years old)
													3 - Senior (over 65 years old)
Would you recommendthe park to others? 				Y/N
How many times do you visit the park per month? 	Numeric

The obtained responses are recorded in the ”Inquiry.csv” file.
– Indicate the type of each of the three variables.
– Indicate the proportion of users from each age group who would recommend the park to others.
– Create a boxplot for each age group, regarding the monthly frequency of use of the park, and draw the main conclusions obtained
from this type of graph.

Critérios
In the elaboration of the US09 to US11 the following acceptance criteria will be considered:
• Programming Language: Python
• Development environment: Jupyter Notebook
• Work delivery format: A single Jupyter Notebook file, which contains all the work carried out.
• Each US must be composed of: (1) introduction (succinct and objective); (2) code and results, and (3) analysis and interpretation of the
results.
• Formulas must be written in LaTeX.
• At the end of the file, you must indicate the contribution (in %) of each member of the group to the development of the work 
(the sum of all percentages must be 100%).
