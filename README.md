# AutoAuto Learning Platform Analysis

The goal of this project is to find patterns in the teacher's and student's behavior with the AutoAuto learning platform to make necessary adjustments to curriculum design and lesson activities. AutoAuto builds hand-held self-driving cars to engage students in programming. Students work together in pair programming exercises on a platform designed by AutoAuto. There is data on interactions from 150 students from February 2019 - April 2019 in an Austin middle school classroom. 


There are many articles that describe the benefits of teaching computer science, and the such, in public schools. One such article is written here:

https://medium.com/edmodoblog/more-than-coding-what-students-really-learn-from-computer-science-3d6870387fbc

 Other companies who are teaching computer science and programming in K-12 schools are CollegeBoard<sup>1</sup>, MIT<sup>2</sup>, and Project Lead The Way (PLTW)<sup>3</sup>. 
 
 The approach for AutoAuto is different because unlike CollegeBoard, they are aimed at reaching all demographics who might not otherwise have access to college level coursework or topics. The curriculum and approach is also designed so that students have immediate success and interaction with a real-world problem. With MIT's App Inventor, students aren't using any Python or coding languages to interact with the program. 

With my results, I can inform AutoAuto of trends and solutions such as: lessons that students often fail, different tracks for students who fail multiple lessons, the variance of time to complete assessments earlier in the program versus later, and/or design a lesson flow that changes as student complete activities. This will lead to a better understanding for students which can increase teachers and schools using AutoAuto and their Learning Platform.

My work will be formatted in a document or article that can be used in an academic setting. I can supplement the article with a more visual presentation as well. The results of this project will hopefully be shared at the Association for the Advancement of Artificial Intelligence Fall Symposium in November 2019. 

The data has been collected by AutoAuto and is stored on GitHub. There is over 65 csv files with inforamtion on logins, assessment results, history of lesson changes, points earned by lesson, etc. 

Problems that might occur with the project is having missing or misleading data. Some of the checks for understanding were graded by the teacher. Therefore, students may have completed an activity but did not mark it on the learning platform, and on the other hand they may have marked it as complete on the learning platform but it may not be done correctly. To address this problem I will focus on finding more trends in time spent on activities and number of attempts versus solely focusing on whether the activity was completed. 
Another gap in the data is that sometimes students would only use one person's account since they worked in pairs. To mitigate this problem, I will consider looking at group trends instead of individual trends since there may be gaps between individual student activity. 

My next steps are to meet with the CTO of AutoAuto to continue understanding how the data is represented. Once I am able to get a grasp on the organization of the data, I will begin the EDA process, and then conduct statistical tests. I also hope to do some unsupervised learning with the data to find underlying clusters or patterns with the content. 


# Reference
1. https://apcentral.collegeboard.org/courses/ap-computer-science-principles/course
2. http://appinventor.mit.edu/explore/about-us.html
3. https://www.pltw.org/our-programs/pltw-computer-science-curriculum

