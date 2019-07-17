# AutoAuto Learning Platform Analysis

AutoAuto builds hand-held self-driving cars to engages students in programming. Students work together in pair programming exercises on a learning platform designed by AutoAuto. There is data on interactions from 150 students from February 2019 - April 2019 in an Austin middle school classroom. The goal of this project is to find patterns in the teacher's and student's behavior with the learning platform to make necessary adjustments to curriculum design and lesson activities. 


There are many articles that describe the benefits of teaching computer science, and the such, in public schools. One such article is written here:
https://medium.com/edmodoblog/more-than-coding-what-students-really-learn-from-computer-science-3d6870387fbc

 Other companies who are trying to teach programming in K-12 schools are... 
 
 The approach for AutoAuto is different because...


With my results, I can inform AutoAuto of trends and solutions such as: lessons that students often fail, different tracks for students who fail multiple lessons, the variance of time to complete assessments earlier in the program versus later, and/or design a lesson flow that changes as student complete activities. This will lead to a better understanding for students which can increase teachers and schools using AutoAuto and their Learning Platform.

My work will be formatted in a document or article that can be used in an academic setting. I can supplement the article with a more visual presentation as well. The results of this project will hopefully be shared at the Association for the Advancement of Artificial Intelligence Fall Symposium. 

The data has been collected by AutoAuto and is stored on GitHub. There is over 65 csv files with inforamtion on logins, assessment results, history of lesson changes, points earned by lesson, etc. 

Problems that might occur with the project is having missing or misleading data. Some of the checks for understanding were graded by the teacher. Therefore, students may have completed an activity but did not mark it on the learning platform, and on the other hand they may have marked it as complete on the learning platform but it may not be done correctly. To address this problem I will focus on finding more trends in time spent on activities and number of attempts versus solely focusing on whether the activity was completed. 
Another gap in the data is that sometimes students would only use one person's account since they worked in pairs. To mitigate this problem, I will consider looking at group trends instead of individual trends since there may be gaps between individual student activity. 

My next steps are to meet with Ryan the CTO of AutoAuto to have him explain how the data is represented. Once I am able to understand how he organized and collected the data I will begin the EDA process, and then conduct statistical tests. I also hope to do some unsupervised learning with the data to find underlying clusters or patterns with the content. 

