# School District Analysis

## Overview

We had initially made a DataFrame that combined student data and school data. We conducted analyses on the average scores (math and reading) as well as the average number of students passing, based on a number of independent variables: school, grade, school budget (spending per student), school size, and school type (charter vs. district). We then repeated and modified our analyses after we were asked to remove the scores of the 9th-grade students at Thomas High School, due to probable cheating.

## Results

### District Summary Results

After removing math and reading scores of 9th grade students from Thomas High School, we observed the following changes in the overall findings. Since the portion of the data removed was relatively small in the overall data set these changes are relatively small. 

- A negligble decrease in average math score (about 0.1%), from 79.0% to 78.9%
- No visible change in the average reading score, remaining at 81.9%
- 1% drop in the percentage of students passing math (from 75% to 74%)
- 1% drop in the percentage of students passing reading (from 86% to 85%)
- Slightly over 1% decrease in the percentage of students passing both courses (from 65.17% to  64.09%)

Before cleaning the data

![District_Before](https://user-images.githubusercontent.com/105169537/183493205-6aa1ffd2-c2ad-457d-9f1e-6c1f6b4ffbe1.png)

After cleaning the data

![District_After](https://user-images.githubusercontent.com/105169537/183493227-c29cae73-4810-48a3-846c-681cbff52439.png)

### School Summary Results

After removing math and reading scores of 9th grade students from Thomas High School, the school's overall percentage of passing students changed from 90.9% to 65%. As a consequence, Thomas High School's ranking dropped from 2nd highest to 8th (as shown in tables below).

Before cleaning the data:

![School Ranking_Before](https://user-images.githubusercontent.com/105169537/183497052-9af71765-00d4-4729-81f0-87cfe71476bd.png)

After cleaning the data:

![School Ranking_After](https://user-images.githubusercontent.com/105169537/183497068-33a2340f-9ba4-4329-b695-0c11b412c35e.png)

### Scores by grade

When we group the data based on schools and grades, we see the effect of removing the scores of the 9th grade students from Thomas High School, because the removals are contained in the one cell (in each table). With this arrangement, everything else remains unaffected by the removal.

Math scores by school, by grade level after cleaning the data:

![Screen Shot 2022-08-08 at 3 34 25 PM](https://user-images.githubusercontent.com/105169537/183500395-cd03cb0c-c3ab-4dd7-b837-fccf94ab16c1.png)

Reading scores by school, by grade after cleaning the data:

![Screen Shot 2022-08-08 at 3 37 31 PM](https://user-images.githubusercontent.com/105169537/183500419-5791f8db-f41f-462b-a909-513dfa366e6e.png)

### Scores by school spending

After cleaning the data, we did not find a noticable change in the average scores, though the percentage of overall passing dropped, in the $631-645 spending category, to which Thomas High School belongs. The drop was from 63% to 56%.

Before cleaning the data:

![Screen Shot 2022-08-08 at 3 40 10 PM](https://user-images.githubusercontent.com/105169537/183500855-d4510f77-42ce-431e-a392-5b2fa8a44c94.png)

After cleaning the data:

![Screen Shot 2022-08-08 at 3 40 20 PM](https://user-images.githubusercontent.com/105169537/183500862-b4164dfc-ad49-45d3-8e2c-6ec03327bdb3.png)

### Analysis by school size

Cleaning the data impacted our analysis of grades based on school size, in the category to which Thomas High School belonged (Medium (1000-1999), where the % Overall Passing dropped from 91% to 85%.

Before cleaning the data:

![Screen Shot 2022-08-08 at 3 44 07 PM](https://user-images.githubusercontent.com/105169537/183503565-599d070a-c7e9-44de-b985-de8d4e967f0f.png)

After cleaning the data: 

![Screen Shot 2022-08-08 at 3 43 54 PM](https://user-images.githubusercontent.com/105169537/183503583-57324002-2821-4911-a786-52fea804eafa.png)

### Scores by school type

Since Thomas High School belonged to the category of charter schools, cleaning the data reduced the overall passing percentage for Charter schools by 3% (from 90% to 87%), while leaving the district schools category unaffected.

Before cleaning the data:

![Screen Shot 2022-08-08 at 4 00 00 PM](https://user-images.githubusercontent.com/105169537/183511093-066ed79f-f590-46f7-955e-c40e65337053.png)

After cleaning the data:

![Screen Shot 2022-08-08 at 4 00 33 PM](https://user-images.githubusercontent.com/105169537/183511120-89363bfc-8bdc-46af-ac8f-dac715b304d1.png)

### Summary 

First, with respect to the overall findings, such as the average scores in the entire district, removing the data of the 9th-grade students from Thomas High School did not make a big impact. Even when we look only at 9th grade students' average scores, cleaning the data reduced the average overall scores only by a negligble .1% (from 82.5% to 82.4%). However, when we look more closely at the data and sub-categories, we find noticeable impact of the removal. 
- In the $631-645 spending category, there was a drop in the overall passing percentage from 63% to 56%. 
- In the school-size category of Medium (1000-1999), overall passing percentage dropped from 91% to 85%. 
- Finally, the percentage of passes dropped for Charter schools from 90% to 87%, while leaving the district schools category unaffected. 
