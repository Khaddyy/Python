# Python
![image](https://github.com/Khaddyy/Python/assets/117234410/529c53d3-8769-4194-b02c-1695478c0201)

An exploratory data analysis on a dataset of USA mass killings from 1982-2023.

CONTEXT: The US has witnessed 398 mass shootings in last 41 years, with a report of 144 cases from this particular database. 
Geography: United States of America
Unit of analysis: Mass Shooting Attack

Dataset: The dataset contains detailed information of 144 mass shootings in the United States of America.

Variables: The dataset contains Serial No, Title, Location, Date, Summary, Fatalities, Injured, Total Victims, Mental Health Issue, Race, Gender, Year etc...

Data cleaning included but not limited to; 
Finding the different missing values aliases in each column with df.case.unique()
then removing unwanted blank spaces;
df.case = df.case.str.strip()
Checking for NaN value;
df.loc[df.isnull()]
Putting column values in standardized format; 
df.location = df.location.str.strip().str.capitalize()

To categorize gender;
We'll replace male and female with M and F respectively.
M/F, replaces both male and female genders.

INSIGHTS
Finding out max fatalities recorded;
For this, I have counted the total number of fatalities, grouped them using ‘year’ and sorted them by ‘fatalities’ columns 
Year was divided into month, date and year to find out about deadly days, months or year in particular.
Frequency of attacks per month indictated the highest to be in February, Years 2018 and 2022 with equal frequency of attacks.
The visualizations mark 2017, 2018, 2019, 2016 and 2022 as the most unfortunate with high death rates while 2017, 2019 and 2022 recorded high innjury rates respectively. 
Year 2017 recorded the most fatalities and injuries.
Perpertrators are suggested to be largely white males, more prevalent compared to females or cross genders. Also commonly indicating high rates of prior mental health issues.
2723 total sum of victims were recorded. 1606 injuries and 1117 fatalities.
