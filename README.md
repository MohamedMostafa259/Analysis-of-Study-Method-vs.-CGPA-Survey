# Analysis-of-Study-Method-vs.-CGPA-Survey
**A Descriptive Analysis of the “Study Method vs. CGPA” Survey conducted among second-year Computer and Information Sciences (CIS) students at My University, EUI, in 2024**

## Table of Contents
- [Introduction](#introduction)
- [Research Questions](#research-questions)
- [Hypothesis](#hypothesis)
- [Population of Interest](#population-of-interest)
- [Sampling Method](#sampling-method)
- [Bias Identification](#bias-identification)
- [Survey Questions](#survey-questions)
- [Analysis](#analysis)
- [Statistical Analysis](#statistical-analysis)
- [Conclusion](#conclusion)
- [Potential Issues](#potential-issues)

## Introduction
Effective study methods play a crucial role in academic success. This project investigates the correlation between various study methods and student performance, as measured by Cumulative Grade Point Average (CGPA). The survey was conducted among second-year Computer and Information Sciences (CIS) students at the Egypt University of Informatics (EUI), aiming to uncover which study methods they primarily employ when preparing for final exams. The analysis primarily utilizes descriptive statistics to provide insights into the learning habits and academic performance of the surveyed students.

## Research Questions
1. Which study method is the most frequently used by high-achieving second-year CIS students at EUI?
2. What is the most common study method used by second-year CIS students at EUI?

## Hypothesis
It is hypothesized that high-achieving students prefer active study methods, particularly written & summarized notes with highlights, as these methods may reflect deeper engagement and understanding of the material compared to passive methods like online revisions, which may be the most common study method.

## Population of Interest
The population of interest for this study comprises second-year CIS students at EUI.

## Sampling Method
Convenience sampling was utilized through the second-year EUI CIS students' WhatsApp group.

## Bias Identification
#### Identified Biases:
- If certain groups of participants are more likely to respond to the survey than others, the results may be skewed and biased toward these groups. For example, if high-achieving students are more motivated to participate, the data may overrepresent their study methods compared to lower-achieving students.
- Students might misrepresent their preferred learning styles or habits.
#### To minimize bias:
- The survey will be anonymous to encourage honest responses. 
- The wording of questions will be neutral and avoid leading answers like the “hands-on practice” study method.

## Survey Questions
1. What is your current Cumulative GPA (CGPA)?
2. Which study method do you primarily use when preparing for final exams? (If your method varies depending on the subject, please choose your most beneficial and preferred one.)<br>
Written & summarized notes with highlights<br>
Session with a teacher<br>
Online resources (e.g., revisions on YouTube)<br>
Group studies with your friends<br>

## Analysis
The analysis of the collected responses yielded the following insights:

### The most Common Study Method:
![Distribution of Study Methods Among Students](https://github.com/MohamedMostafa259/Analysis-of-Study-Method-vs.-CGPA-Survey/blob/main/Distribution%20of%20Study%20Methods%20Among%20Students.png)

The pie chart above suggests that “online resources” are the most prevalent study method used by the 2nd year CIS students at EUI in preparation for exams. Conversely, “group studies” appears to be the least common method, potentially representing close to 0% of students based on the chart!

### High-Achieving Students & CGPA Distribution: 
![CGPA Distribution for each Study Method](https://github.com/MohamedMostafa259/Analysis-of-Study-Method-vs.-CGPA-Survey/blob/main/CGPA%20Distribution%20for%20each%20Study%20Method.png)
Among students with a CGPA above 3.5, “Written & summarized notes with highlights” seem more prevalent than the “online resources” study method.
The "Online resources" histogram might have a wider spread, meaning that students with a wider range of academic performance use this method.

## Statistical Analysis
![Boxplot of CGPA Across Study Methods](https://github.com/MohamedMostafa259/Analysis-of-Study-Method-vs.-CGPA-Survey/blob/main/Boxplot%20of%20CGPA%20Across%20Study%20Methods.png)
A Kruskal-Wallis test was conducted to examine whether study methods influence CGPAs. The obtained p-value (0.12) exceeds the significance level of 0.05, indicating failure to reject the null hypothesis. This suggests no significant differences in CGPA medians across study methods.

#### NOTEs on the above Boxplots’ result: 
-	In Kruskal-Wallis, the null hypothesis typically states that there are no significant differences in the medians of CGPA across the study method categories (written notes, sessions with teachers, online resources, and group studies). 
- The Kruskal-Wallis test is used as it doesn’t assume that the data (CGPA in this case) is normally distributed within each study method group. Also, it’s used when the sample size is small like in this case. If the data was normally distributed, using a test like ANOVA would be a better choice.

## Conclusion
The goal of this survey was to investigate the study methods preferred by high-achieving second-year CIS students with a CGPA > 3.5 at EUI, as well as the most common study method among all second-year CIS students. The results revealed that "Written & summarized notes with highlights" is the preferred study method among the top-achieving 2nd-year CIS students at EUI, while the most prevalent study method among all 2nd-year CIS students is "online resources". However, it's important to note that the small sample size, 21 students, might limit the generalization of these findings.

## Potential Issues
- The survey focuses on study methods for final exams, which might not capture the full range of learning activities students use throughout the semester.
- The survey may not account for other factors that could influence study habits and academic performance, such as socioeconomic status, prior knowledge, or extracurricular activities.
