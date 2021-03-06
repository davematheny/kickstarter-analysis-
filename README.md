# Kickstarting with Excel
UNC Boot Camp assignment

## Overview of Project
1. Take excel data KickStarter worksheet provided and perform analysis.   
2. Filter, format and add new columns\calculated columns to the tabular data.   
3. Create two new tabs Outcomes Based on Goals and Theater Outcomes by Launch Date.
4. Create pivot tables based off the data.  
5. Create visualizations.  
5. Perform analysis with visualizations.  
 
## Purpose
Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals.

## Analysis and Challenges
I created two line charts of the outcomes.  First chart based on Launch Date and the second based on the goal.

### Analysis of Outcomes Based on Launch Date
Live outcomes were filtered from the data set.  Below is a linechart of successful, failed and canceled outcomes by month.
![Graph 1. Theater Outcomes based on Launch Dates](resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
Live outcomes were filtered from the data set.  Below is a linechart of the goals in bins of 5k where each outcome was grouped by successful, failed and canceled in the corresponding bin.
![Graph 2. Theater Outcomes Based on Goal Ranges](resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
The only challenges I encountered where remembering the excel functions.  Also it was difficult for me to get use to scrubbing data in excel, typically I clean data in a database with SQL.  Remebering all the excel tricks to clean the data proved a challenge(example splitting the column into two columns).  Also Im use to pivot tables off OLAP cubes so using raw data was fun to get use to again.  The biggest challenge beyond programming which I think gets seriously overlooked is just understanding the data, aka the columns\features.  Like what exactly does this column\feature represent, where did we get this data, does it change etc.
## Results

-What are two conclusions you can draw about the Outcomes based on Launch Date?
1. Few projects were canceled
2. Most successful projects were in May and June

-What can you conclude about the Outcomes based on Goals?
The most successful outcomes are projects with goals that are less than $5000 goals or between $35000 and $45000. 

-What are some limitations of this dataset?
More data could possibly provide more\different insights(lack of more data). Also there wasnt much data on canceled plays which would have been nice.  I would also say that
the quality of the data could have been better, for example some of the subcategories seemed redundent and ambiguous.  I would also say that bias is another factor that could
have effected this data, people typically see movies in their own language did these movies have subtitles etc.

-What are some other possible tables and/or graphs that we could create?
I could create scatter plots or bar charts.  Possibly a staked bar chart show launch date to goal, or percent to goal.
