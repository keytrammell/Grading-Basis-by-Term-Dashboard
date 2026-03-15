# Grading Basis Changes Amongst Students

## Project Objective:
Identifying the subjects that have historically been changed to the Satisfactory/Unsatisfactory (pass/fail) grading basis. Identify trends among classes/subjects that have a higher grading basis rate and see if there's a correlation amongst semesters and the year of students. I'll also be identifying the increase of S/U changes that have made from Spring of 2024 to Fall of 2025.  
                                                                                
## Data Used:
- <a href="https://github.com/keytrammell/Grading-Basis-by-Term-Dashboard/blob/main/Fall%202024.xlsx">Dataset</a>
- <a href="https://github.com/keytrammell/Grading-Basis-by-Term-Dashboard/blob/main/New%20Spring%202025%20Grading%20Basis.xlsx">Dataset</a>
- <a href="https://github.com/keytrammell/Grading-Basis-by-Term-Dashboard/blob/main/New%20Fall%202025%20SU%20Data.xlsx">Dataset</a>

## Challenges: 
These insights have previously been tracked, but not ordered/simplified in a way to show a concise measure of courses and students by class year. 

## Solution:
Create a simplified dashboard that will display the top courses that students have a tendency of making S/U and showing which class of students are taking the courses as pass/fail.

## Target Audience: 
Primary - Associate Dean of Student Success. Secondary - Student success department, primarily the ones that will be implementing the new procedures that come from our findings. 

## Tools Used: 
Primarily Excel and Tableau for visuals. 

## Information Needed: 

- The Dean needs the top courses that are taken on a pass/fail basis. 
- Class year of students most likely to take the courses as pass/fail. 
- Identify if any of the courses currently have student success initiatives. Ex. Tutoring or SI 
Programs to promote study skills 

## Data Quality Checks: 

I have performed a series of data checks, clean ups, and validations to make sure that the data is as accurate and concise as possible. Row count checks, column count checks, data type check, and duplicates checking. 

## Acceptance Criteria: 

The solution should - 
	
  • Recommend future insights on courses with a high rate of grading basis changes based on quantified data. 
	
  • Clearly explain and showcase recommendations with data proven justification. 
	
  • Take into consideration any outliers that may arise. Some classes will appear that do not indicate any trends. 

## Success Criteria: 

After viewing this dashboard, the Dean of Student Success should be able to actively identify the top courses that students typically take for S/U. It will give the Dean and her team insights to make informed decisions for the future of student outcomes and the launch of new events/campaigns as well as intervention tactics. It will also help with identifying departments across the university system that they can collaborate with to help with furthering student success. 

## Actions taken: 

The first thing I did was clean up my excel data. I deleted all values that weren't needed within columns. I also added in a row so that I could categorize each column. I used CONCAT to allow data to be pulled in from two separate columns, combining them into one. This combined the class name and catalog name into one column making for cleaner data. 
	
  - After cleaning up all of the S/U data from Spring of 2024 to Fall of 2025, I then formed a few pivot tables in excel to get a count of each class name/number to show exactly how many courses had been changed to S/U. In doing so, it also highlighted which courses had the highest number of changes.

  - I then focused on creating some visuals to demonstrate my findings using Excel and Tableau. 

    ## Creating Visuals: 

Using Excel I first filtered through my data to make sure that it was only showing the most important classes that are usually changed to S/U. This excluded any courses such as internships and research based courses that are graded as satisfactory/unsatisfactory. I then paired this data with Tableau to create a more cohesive dashboard for visual storytelling. 

- Although Fall 2025 had a total of 55 S/U changes, I tried to highlight the courses that have shown a pattern in the past within my visualizations.

## Dashboard

![image alt](https://github.com/keytrammell/Grading-Basis-by-Term-Dashboard/blob/main/Screenshot%202026-03-14%20224729.png?raw=true)

## Conclusion: 

  - Spring 2024, only 1 S/U change was made.
	
  - In Spring of 2025, a total of 19 S/U grading base changes were made. 
	
  - In the Fall of 2024, All of the S/U changes were made by freshman. As a whole, 15 students changed their grading basis to S/U. 
	
  - In contrast, Fall of 2025 had a total of 55 grading basis changes.  That is an increase of 40 students, a percentage growth of 266.67%.

	- A strategic plan with events and intervention focused primarily on Freshman students should be created. Freshman students made up the majority of the grading basis changes. There should be a increased focus on creating events that partner with individuals within the math department, as majority of the students struggles came from Math 111, Math 108, and Math 112. Currently there's no SI for Math 108, but it should be something to consider for the future success of students who take that class. Programming centered around Math department resources should be created at the onset of student orientation, so that students are made aware quite early of what they have available to them on campus. Marketing for these courses should be on a concrete rotational basis as to have hightened awareness for students who may struggle in the future. 
