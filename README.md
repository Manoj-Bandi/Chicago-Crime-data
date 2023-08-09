# Chicago-Crime-data
Exploratory Data Analysis (EDA):
EDA of the dataset includes initial analysis of the underlying raw data to identify any patterns,
anomalies and duplicates which may have an influence on the next stage of our visualization
project.
We start by formatting the column headers so as to standardize and make the handling easier.
This was achieved using the following code to remove any leading or lagging blank spaces,
replace commas and blanks and convert all headers into lowercase letters.


Dataset characteristics: This gives us a brief summary of the dataset which was extracted from
Chicago PD webpage.
● Shape: 1413406 rows and 22 columns
● Size: 31094932 (which is a product of rows & columns)


Data set after EDA:
● Shape: 1413406 rows and 10 columns
● Size: 14134060 (which is a product of rows & columns)
We see a significant reduction in the data size from 31094932 to 14124060, which is a 54%
reduction (16960872).


Analysis of the current year 2022:

In the first part of the analysis, we look at the 2022 dataset to identify any trends and major observations
which will help the citizens. For this, we created a data frame with data limited only to the year
2022 from the entire dataset.

As stated in the introduction, we have performed analysis in 3 parts:
1) What: what are the types of crimes in Chicago
2) Where: where are the crimes taking place, are there any particular districts, locations
which are riskier compared to others
3) When: Is there any specific time or season when crimes are more prevalent than
others
1) What: Types of Crimes commonly occur across Chicago, and what proportion of the total
they are. This helps us to educate the readers on what type of crimes citizens should be
vigilant of and accordingly they can prepare themselves.

Initially, we looked at all the types of crimes and we see that crimes are broadly classified into 31
types. But this resulted in a poor visualization as only 12 crime types have percentages > 1%
while the rest of the 19 represent an insignificant proportion of the total crime data for 2022.


Year on Year Analysis across 6 years:

For the second part of the analysis, we have considered data for 6 years instead of the usual 5
years as we wanted to cover 3 periods which are:
● Pre Covid: 2017 to 2019 (3 years)
● Covid : 2020 and 2021 (2 years)
● Post Covid: 2022 (current year)

This will help us to identify if there are any trends in terms of total crimes reported across years,
any change in terms of increase or decrease in any particular crime type and if seasonal
variations are similar or any changes took place across these 3 periods.

By looking at all the visualizations and analysis of the data, we can derive the following conclusions
For the most recent data i.e., for the year 2022,

1. Out of all the crimes that are happening in Chicago in the year 2022, only Theft and Battery
makeup 40% of total crimes. So, the citizens should be careful and not walk alone at any
time of the day.

2. Out of all the districts in Chicago, District 6 & 8 has the highest crime rates, followed by
Districts 4 & 12. Unfortunately, Our UIC campus and Little Italy where most of the students live
falls under District 12. So, Students must be very cautious all the time.

3. Crime rate in the months of June to September, which is summer, has the crime rate. So, we
can assume that during the winters, due to the extreme cold and snow, there won’t be many
people roaming outside which further decreases the chances of crimes.

4. Ironically, the probability of crimes happening at mid-noon i.e., 12 noon is high. After the midnoon,
crime rates remain high from 3 pm to 8 pm. Surprisingly, the crime rate is comparatively low at night
and is lowest in early mornings.

For the data across years from 2017 – 2022.

1. Before covid, the crime is a significant crime rate. But during covid, there is a drop-in crime
rate same as every other field. But after covid not only the people and businesses got
back to the pre covid times but also the crime rate which slowly rising to pre covid levels.

2. After analyzing different crimes across the years from 2017-2022, we can conclude that crime-type theft has an upward trajectory.
3. Police should investigate that and implement the required protocols to control the rising theft levels.

4. Across the years, the crime rate for crime type ‘Battery’ has a downward trend. We can
assume that the police are successful in controlling the battery.

5. Most surprising trend is motor vehicle theft. It is at its peak in the year 2022 compared to
the previous years. People should be aware of that and should make use of antitheft
precautions in their vehicles
