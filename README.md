# Kickstarter-analysis

## Overview of Project
Louise wants to know how different campaigns fared in relation to their launch dates and their funding goals. In order to do so we need to use the Kickstarter data to analyze and visualize campaign outcomes based on their launch dates and their funding goals.

### Purpose
The purpose of the Kickstarter project is to analyze and visualize the number of successful, failed, and canceled projects by month and the percentage of successful, failed, and canceled plays based on the funding goal amount.

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
The first analysis that's done is for the Theater category. The outcome is analyzed based on launch date and month wise. The data and the chart below shows the number of successful, canceled and failed outcomes for theater category. For this analysis I used Pivot table and Pivot chart to filter data for Theater and years. I then put the outcome in the columns and values to get the count of sucessful, failed and cancelled campaigns. I then added Date created conversion date to the Rows so that I could get the data years and month wise.

<img width="326" alt="Screen Shot 2021-06-23 at 6 21 25 PM" src="https://user-images.githubusercontent.com/85711507/123179874-dec6af80-d44f-11eb-9b22-b87f2f024e8f.png">

<img width="800" alt="Screen Shot 2021-06-23 at 2 45 39 PM" src="https://user-images.githubusercontent.com/85711507/123158660-b3cd6300-d431-11eb-8887-c808aada7096.png">



### Analysis of Outcomes Based on Goals
The other dataset and chart is created to show the percentage of successful, failed, and canceled plays based on the funding goal amount. To perform the analysis goals column is created based on range shown in the Goal column in the screenshot below. Then using coutifs function count of successful, failed, and canceled plays is calculated. Then we added and got the total projects for each goal range. This step was necessary in order to get to the percentage of successful, failed, and canceled plays.The Outcome based on goal graph helps in visualizing the percentage of successful, failed, and canceled plays.

<img width="500" alt="Screen Shot 2021-06-23 at 6 26 35 PM" src="https://user-images.githubusercontent.com/85711507/123180281-98be1b80-d450-11eb-8b80-e6416a99c8e2.png">


<img width="800" alt="Screen Shot 2021-06-23 at 2 48 05 PM" src="https://user-images.githubusercontent.com/85711507/123158961-09a20b00-d432-11eb-9506-8f98925e2b81.png">


### Challenges and Difficulties Encountered

One of the challenge that I encountered while delivering the data was the complexity of countifs function when trying to calculate the number of successful, failed and canceled projects. The range criteria needed to be very carefully placed as there were multiple ranges.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. May month has the most successful outcomes for Theater category based on launch date but also the highest number of failed outcomes.
2. It is difficult to analyze data based on only outcomes by launch date. There are other criteria which needs to be considered as well like average donation and percentage funded.

- What can you conclude about the Outcomes based on Goals?
  
  Plays that had goal between $1000 to $4999 were most successful.There were no plays canceled  for plays subcategory.

- What are some limitations of this dataset?

  One of the limitation of Kickstarter dataset is that the goal amount has a wide range. Most of the campaigns(961) have goals ranging from $1000 to $14999. There are only 86 campaigns that have a goal amount ranging from $15000 to greater than $50000. 


- What are some other possible tables and/or graphs that we could create?

  1.Table and chart showing Outcome based on end date.

  2.Table and chart showing outcome based on country.

