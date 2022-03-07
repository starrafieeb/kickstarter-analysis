# Kickstarter Challenge Analysis


## Overview of Project

This project was for Louis, who is playwrighter and wants to start a crowdfunding campaign to help fund her play, Fever. As an Excel power user, I had to sort, organize and filter the data for her, so she can compare the most successful campaigns in her own field and see if there is any specific factors that they got successful. 

## Analysis and Challenges

### Analysis Process 

One the first steps that I took to analyze the crowdfunding data, was to make the data readable. As the dates were not readable. I tried to go to details as much as possible so I separated “Category & Subcategory “ into two separate columns. Also I found the “Average Donation” by using the data that I have from pledged amount and backers count. I used conditional formatting tool to make my “outcomes” column visible. Meanwhile I applied some filters to analyze raw data that I had so I can make my conclusion accurately. After all, I filtered my data to find the factors that they were possible to be useful for same field that Louis wanted. I filtered my data by “Theatre” or “Plays” and by creating Pivot Charts and change the filters, I made my conclusion which I explain in Results paragraph. 

### Analysis result by charts 
In general, the good news for Louis is, theatre is the most successful campaign compare to other campaigns. Refer to“Parent Category Outcomes” chart, you can see that the first successful campaign is theatre. 

![category_statistics](/resources/category_statistics.png)


Also, if you go in details, between all the subcategories, “plays” has the most successful statistic. Please refer to “Subcategory Outcomes” chart.

![subcategory_outcomes](/resources/subcategory_outcomes.png)

	

### Challenges

As I said, to sort, analyze and organize the data, the data should be readable. The very first thing that I did, was using the formula “=(((J2/60)/60)/24)+DATE(1970,1,1)” for both “Deadline” and “Launched_at” columns to make them readable and I created two other columns, “Date Created Conversion” and “Date Ended Conversion”. Also, I couldn’t filter and find “Plays” in the “Category and Subcategory” column, that’s why I had to use “Text to Columns” tool to separate them into two different columns. Besides I extract the year by using “Year()” formula from “Date Created Conversion” column, so I would be able to create a Pivot Chart based on the “Years” and analyze the data from there. 



## Results

### Theater Outcomes Based on Launch Date
Refer to “Theater_Outcomes _vs _Launch” chart, the most cancelation that we got was in January and I’m assuming that maybe it’s because of people mostly spend a lot during the holiday season, they have to work more or going back to school so they don’t want to spend that much. The most successful month was “May” and no cancellation on “October”. Also, “December” had the least successful one. 
![Theater_Outcomes_vs_Launch.](/resources/Theater_Outcomes_vs_Launch..png)




### Outcomes Based on Goals

Refer to “Outcomes Based on Goals” chart, it’s obvious that we have only two factors “ Successful” and “Failed”, as there was no cancelation. The other thing that is obvious is mostly people they’re willing to pay more in range of 1000 to 49999, and then 50000 or more. Which means people that we are dealing with either they’re reach or middle-class. 

![Outcomes_based_on_Goals](/resources/Outcomes_based_on_Goals.png)



