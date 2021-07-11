This case study is provided in the Capstone project of the Google Data Analytics Certification course for an imaginary company called, Bellabeat using a dataset from Fitabase. 

**## What is the case study about?**

Bellabeat is a high-tech company that manufacture health-focused products for women. This analysis will focus on one of Bellabeat’s products and analyze smart devices to gain insight into how consumers are using their devices and also help the marketing strategy team.

**DATA SOURCE: ** [FitBit Fitness Tracker Data]https://www.kaggle.com/arashnic/fitbit) (Open source made available by [Mobius](https://www.kaggle.com/arashnic/) on Kaggle). The data is collected from 30 users of the Fitabase products.

**Columns Highlighted in the dataset:** User_Id, AcitivityDates, Total Distance, TotalSteps, Very Active Distance, SleepDay, Calories and some others. 

## TASKS/Questions to be solved
•	Trends in FitBit Smart device usage
•	How the trends can be applied to Bellabeat customers
•	How it will help marketing strategy for any Bellabeat product

## PROBLEMS/LIMITATIONS OF THE DATA
- **Sampling Bias:** The collector of the dataset made it clear it was from 30 participants but I found datasets for 33 users. The numbers of participants in the research do not cut across all the population, the age group of the participants and occupation were not made known.
- **Missing information: **When the datasets were sorted and filtered, some of the data do not contain all the users. Some columns are filled with zero values and some datasets do not contain all the participants.
Regardless of these, the analysis was done and some amazing trends and patterns were found.

## HOW THE DATA WAS PROCESSED
The dataset is one that can be analyzed by **MS Excel or Google Sheet**. So, MS Excel was used in the processing, analysis and visualization of the data.
1.	The relevant columns were combined in the activity sheet and excluded columns that are irrelevant and uncompleted sheets. 
2.	In the completed sheets, there was no duplicate found.
3.	The pivot table of the new sheet/excel was done. [See the new Excel Book here](https://drive.google.com/drive/folders/1po2mGVa81ZYX-6tLLi6ign2KKpZ6KsgH?usp=sharing) (consists of the data sheet and visualizations for questions and answer sheet).

## HOW THE DATA WAS ANALYZED
At this phase, I included three more columns(Avg_totalDistance, Avg_totalSteps, Avg_SumCalorie, and Avg_ActiveDistance) and then asked and gave answers to some questions that will help in determining trends and patterns in the data so better decisions can be made using the visualizations.
1.	Average total distance, Average TotalSteps, Average ActiveDistance, and Average Calorie columns were include and it cuts across all the 33 participants. 
2.	Reduced the result of values in some columns with decimals to 2 decimal places
3.	Cleaned the hourCalories sheet. A new column included (time was extracted from the date).
4.	Then set and answer some questions.
**How the average values were calculated:** The values in the columns were divided by the count of activity days for each user.

**SOME QUESTIONS WITH ANSWERS**
1). What is the Maximum and Minimum values for TotalDistnace, TotalSteps and Calories?
ANS: MAX (TotalDistance): 409.60 MIN(TotlaDistance): 11.45
	MAX(TotlaSteps): 497241 MIN(TotlaSteps): 15352
	MAX(Calorie): 106534 MIN(Calorie): 7895

2). How many users perform the activity for 31days? 
ANS: 21 participants (63.64% of the participants)

3). How many users perform the activity for 30days? 
ANS: 3 participants (9.09% of the participants)

4). How many users perform the activity for less than 30days? 
ANS: 9 participants (27.27% of the participants)
Out of these users, 1 performed the activity for 4 days. This might probably be an error.


[SEE THE PIE CHART OF THE USERS HERE =>](https://drive.google.com/file/d/1MeWVtxojjnF_d6b_zwhwhXqb_0HIVOb3/view?usp=sharing)

5). What is the relationship between the Avg_TotalDistance and Avg_TotalSteps covered by participants?
[SEE THE CHART OF THE USERS HERE =>](https://drive.google.com/file/d/1MaRJVCy0ECltV_NuwyrR_eO2cq4B9YTB/view?usp=sharing)
ANS: There is a positive correlation between the distance covered and the steps taken.

6). What is the relationship between the distance covered and the calories, using the Avg_TotalDistance and Avg_Sum_Calorie columns?
[SEE THE CHART OF THE USERS HERE =>](https://drive.google.com/file/d/1M_meWzs2CfGBpnwmH0WRFD_KSd1P8NbX/view?usp=sharing)
ANS: There is no strong relationship between the distance covered and the number of calories recorded. Few participants with the most average distance recorded more calories. Bulks of the Calories recorded are by participants who maintained the average distance between 1 and 8.5.

7). What is the relationship between the ACTIVE DISTANCE covered and the CALORIE?

[SEE THE CHART OF THE USERS HERE =>](https://drive.google.com/file/d/1MY71MxSFSAqgveI7hqvNTMOawZE6ybdS/view?usp=sharing)

ANS: The more active the distance is, the larger the number of calories consumed. But a larger percentage of the participants maintained the range of 1,500 – 3,000 calories.

8). Relationship between hours of the day and the number of calories (This was done after Time was extracted from the ActivityHour column in the hourCalorieMerge sheet and named the column hourCalorie. 

[SEE THE CHART OF THE USERS HERE =>](https://drive.google.com/file/d/1UbK8_eDnfq8Uvf3vdaefzvhhkMItfT1I/view?usp=sharing)

ANS: The chart above shows that participants recorded the largest amount of calories between 5 PM and 7 PM every day. Also, the bulk of the recorded calories lies within the hour of 5 AM and 10 PM.

**RECOMMENDATION**
I have seen that in this analysis, the participants took part in the activities to maintain their weight and we can get that from the calorie values.
I did not include columns like Weightloss, sleepDay, heartRate and some others because the columns do not include all the participants.

## What Bellabeat product can the result from this analysis be used for?
This analysis can be used in making decisions for all Bellabeat’s products but it fits in more for the Bellabeat app. The app provides users with health data that can help them make healthy decisions and being at the normal weight range is one of the better health decisions.
Bellabeat is a company that focuses on women. Women are interested in keeping their weight in check and this can be done via monitoring their daily calorie intake.

According to [Healthline](https://www.healthline.com/nutrition/how-many-calories-per-day#average-calorie-needs), a moderately active woman between the age of 26-50 needs to eat about 2000 calories per day to maintain her weight and 1,500 calories per day to lose 1 pound of weight per week.
