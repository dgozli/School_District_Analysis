# School District Analysis

## Overview

We had initially made a DataFrame that combined student data and school data. We conducted analyses on the average scores (math and reading) as well as the average number of students passing, based on a number of independent variables: school, grade, school budget (spending per student), school size, and school type (charter vs. district). We then repeated and modified our analyses after we were asked to remove the scores of the 9th-grade students at Thomas High School, due to possible cheating. The modified analyses appear in the Jupyter Notebook file beginning at cell 54. 

## Results

### District Summary Results

After removing math and reading scores of 9th grade students from Thomas High School, there was a negligble drop in the average math and reading scores (less than 0.1%), though the percentage of students passing math, reading, and both dropped by around 1% as the tables below show.

Before cleaning the data

![District Summary_Before](https://user-images.githubusercontent.com/105169537/183466964-3dad1594-caec-439e-ac6c-a1577fee9977.png)

After cleaning the data

![District Summary_After](https://user-images.githubusercontent.com/105169537/183467157-fe363339-2941-4e37-9b3e-942df328fb28.png)

### School Summary Results

After removing math and reading scores of 9th grade students from Thomas High School, the school's overall percentage of passing students dropped very slightly from 90.9% to 90.6%. However, Thomas High School still remained 2nd highest ranking school in terms of the percentage of overall passing students (for both math and reading), as shown in the tables below.

Before cleaning the data

![School_Summaries_Before](https://user-images.githubusercontent.com/105169537/183478074-ca8dc8ea-8dea-448d-a5fe-954935ebef0b.png)

After cleaning the data

![School_Summaries_After](https://user-images.githubusercontent.com/105169537/183478056-48c2dcf1-a0df-4b03-9265-b33b71ec76d4.png)

### Scores by grade

When we group the data based on schools and grades, we see the effect of removing the scores of the 9th grade students from Thomas High School, because the removals are contained in the two cells. With this arrangement, everything else remains unaffected by the removal.

Reading scores by school, by grade level after cleaning the data
![Screen Shot 2022-08-08 at 1 38 46 PM (2)](https://user-images.githubusercontent.com/105169537/183480141-a888abb9-6827-43c0-a9b2-812e2592b1c2.png)

Math scores by school, by grade after cleaning the data
![Screen Shot 2022-08-08 at 1 38 52 PM (2)](https://user-images.githubusercontent.com/105169537/183480225-4c1f6fa5-a813-4d23-b26c-841beb41ced2.png)

### Scores by school spending
After cleaning the data, we did not see any change in the average scores and percentage of overall passing, even though we do see a drop in the number of students passing math and reading in the $631-645 spending category, to which Thomas High School belongs.

Before cleaning the data

![Spending_Before](https://user-images.githubusercontent.com/105169537/183483060-b1d1d1c5-519e-4301-bd90-14bde28a448f.png)

After cleaning the data

![Spending_After](https://user-images.githubusercontent.com/105169537/183483083-e05d2f9f-2b4b-4fc2-b4a6-a6ef51a509ce.png)


### Scores by school size



### Scores by school type
