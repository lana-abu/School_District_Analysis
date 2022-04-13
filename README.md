# School_District_Analysis

## Overview

### Purpose

#### The purpose of this assignment is two-fold. The first is the most obvious: to practice using pandas to clean and analyze data. As we all know, all data is not going to be complete and accurate. It's important to be able to know how to take in the data, determine if the data is not complete, and use your tools to "clean up" the data. The second purpose is directly related to the challenge itself. PyCity schools wanted to determine its budget for the school year. In order to do so, it wants to look into the passing percentage for different schools and grades within the school district. Unfortunately, data for 9th graders at Thomas High School seemed to be manipulated. Therefore, to get a more accurate analysis, we had to get rid of the 9th graders at Thomas High School. After completing the analysis on the new, more accurate data, then we could give recommendations to the PyCity school board on what to do with their budget. 

## Results
<img width="419" alt="Screen Shot 2022-03-12 at 4 06 37 PM" src="https://user-images.githubusercontent.com/96541632/158035013-461cd289-ff80-4534-8623-57be39c8113b.png">

### How is the district summary affected? 

#### The first image below shows the district summary prior to changing all 9th graders at THS to NAN. The second shows after the scores were switched to NAN. As shown, there is not a difference in the scores. 

<img width="1015" alt="Screen Shot 2022-03-09 at 12 14 55 PM" src="https://user-images.githubusercontent.com/96541632/157495002-b6ea3590-1ff7-41d9-918f-503ee4f8edea.png">


<img width="1015" alt="Screen Shot 2022-03-08 at 9 50 50 AM" src="https://user-images.githubusercontent.com/96541632/157262501-1de7d96f-8dce-44d5-b10a-100837a56bea.png">

### How is the school summry affected? 

#### The first image is the school summary prior to hanging all 9th graders at THS to NAN. The second shows after the scores were switched to NAN. For Thomas Highschool, all the scores changed either slightly or a lot. The average math score and reading score stayed relatively the same with minor changes. However, the percentage of students at Thomas who passed reading, math, or both, decreased dramatically with the change. The percent of students who passed math went from around 93.27 to 69.66. The percent of students who passed reading went from around 97.30 to 69.66. The overall passing percentage went from 90.94 to 65.07. 

<img width="1015" alt="Screen Shot 2022-03-09 at 12 53 54 PM" src="https://user-images.githubusercontent.com/96541632/157501700-29884d7c-6d2c-485d-8a37-46e4f10582b7.png">

<img width="805" alt="Screen Shot 2022-03-09 at 2 34 52 PM" src="https://user-images.githubusercontent.com/96541632/157518399-5adb2eb9-5c36-4252-bf41-a39b3c2d1e56.png">


### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

#### Thomas's overall passing performance decreased dramatically if accounting for the 9th graders. However, if just looking at tenth to twelfth graders, it still remained in the top 5 schools in terms of performance. 

<img width="1026" alt="Screen Shot 2022-03-09 at 3 33 05 PM" src="https://user-images.githubusercontent.com/96541632/157530986-250b989d-af2a-4ad4-8545-dcac8a92e382.png">

### How does replacing the ninth-grade scores affect the following:

#### Math and reading scores by grade
  
#### Math Scores pre and post change

##### The first image is prior to the change and the second is after. There is no difference despite changing the 9th grade scores. 

<img width="419" alt="Screen Shot 2022-03-12 at 3 50 08 PM" src="https://user-images.githubusercontent.com/96541632/158034565-af83ba32-ce47-4276-90bd-288fca8f6003.png">


<img width="409" alt="Screen Shot 2022-03-12 at 3 42 14 PM" src="https://user-images.githubusercontent.com/96541632/158034316-f4703146-e3b7-46c6-9227-56b9ec41689e.png">


#### Reading scores pre and post change

##### The first image is prior to the change and the second is after. There is no difference despite changing the 9th grade scores.

<img width="297" alt="Screen Shot 2022-03-12 at 4 07 48 PM" src="https://user-images.githubusercontent.com/96541632/158035046-4e6593ca-2c1f-4402-9041-c0060805afaa.png">

<img width="297" alt="Screen Shot 2022-03-12 at 4 08 14 PM" src="https://user-images.githubusercontent.com/96541632/158035057-2acde846-1788-4b8d-a8cf-306a2ae7fcbe.png">

#### Scores by school spending? 

##### The first image is prior to the change and the second is after. There is no change despite replacing the scores. 

<img width="808" alt="Screen Shot 2022-03-28 at 2 40 42 PM" src="https://user-images.githubusercontent.com/96541632/160464942-aedb3d24-1fb1-49cc-ac24-463cd23a8358.png">

<img width="808" alt="Screen Shot 2022-03-28 at 2 40 58 PM" src="https://user-images.githubusercontent.com/96541632/160464983-21f06930-6d89-45af-9c7a-b5fe9c638f59.png">


#### Scores by school size? 

##### The first image is prior to the change and the second is after. There is no change despite replacing the scores. 

<img width="808" alt="Screen Shot 2022-03-28 at 2 41 17 PM" src="https://user-images.githubusercontent.com/96541632/160465032-7b501561-b374-4298-bfa3-01ca92cf8f52.png">

<img width="808" alt="Screen Shot 2022-03-28 at 2 41 41 PM" src="https://user-images.githubusercontent.com/96541632/160465081-3afd4952-5407-421e-93af-6d91613fc41b.png">

#### Scores by school type

##### The first image is prior to the change and the second is after. There is no change despite replacing the scores.

<img width="808" alt="Screen Shot 2022-04-13 at 1 08 55 PM" src="https://user-images.githubusercontent.com/96541632/163233697-2b0a58c6-1126-4f34-9b62-526bcf6fed93.png">

<img width="808" alt="Screen Shot 2022-04-13 at 1 09 41 PM" src="https://user-images.githubusercontent.com/96541632/163233832-e33e03b9-253a-4f11-8f1f-249739108482.png">

### Summary

#### In summary, a few changes took place when math and reading scores for 9th graders at Thomas High School with NaNs. The most noticeable change was the percent of students passing math and reading at THS. The percent of students passing math went from 93.3% to 66.9%. The percent of students who passed reading went from 97.3% to 69.7%. The average math score decreased just a bit as well as the average reading score. Looking at the average scores for spending ranges: the spending range from $630 to 644 saw a slight decrease in average scores and percent of students passing scores. This is due to Thomas Highschool being apart of it. 



