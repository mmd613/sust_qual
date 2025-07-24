# Qualitative Analysis of TRAILS Sustainment Pilot Study
The following code was used to analyze qualitative data collected by a program sustainment pilot survey. 

## Background
As of 2025, TRAILS had launched impact studies and product satisfaction studies. However, there were no studies on the sustainability of TRAILS mental health programs, meaning there was no data on how long and why providers continue to deliver TRAILS after their initial training. Studying sustainability must be a priority for mental health programs because it allows organizations to study the success and failures of their program over time and gather input for improvements. From a QA standpoint, the study of sustainability gives organizations the opportunity to study curriculum and material engagement and produce product improvements that can mend a decline in client satisfaction. 

## Problem
Senior Data Analyst Chiagoziem Jacob created a program sustainment pilot survey for all three TRAILS programs. This survey was offered to all providers who had been trained by TRAILS (2012-2022). In this survey, providers could offer information about their training, program delivery, perceived impact on students, and motivations for program sustainment. Jacob produced a report for internal review, which I had the opportunity to revise and analyze. This survey collected a good amount of qualitative data, which had not been empirically studied. In my team, I was the only member with hands-on experience coding and analyzing qualitative data.

##Solution
I utilized my skills in R and qualitative methods to analyze the data collected by the pilot survey. I was particularly interested in understanding the core motivations for providers to engage with TRAILS motivation. Any findings may have proved useful for TRAILS QA/QI, identifying churn risks, and increasing client engagement. 

## Method
I used the tidytext package in R to clean qualitative data. Specifically, this meant formatting data into meaningful tokens/data points and creating distribution tabulations, bigrams, and a sentiment analysis. I focused on questions that asked providers for their motivations to continue delivering or implementing our programs.

## Product
My analysis yielded a sentiment analysis of our Tier 1 program broken down by school. After I cleaned the data, I created wordclouds and tabulations that allowed me to see which words were most common. I ran a preliminary sentiment analysis on descriptions of our programming, which I then refined by program and school name. Each school received a sentiment score for how positively or negatively their SMHPs regarded TRAILS Tier 1 program. 

I struggled with missing data in this process. Many SMHPs did not fully complete their survey. I had the intention of deepening my analysis using network analysis and bigrams to identify relationships between sentiment, school, and provider.; however, I was only able to run a sentiment analysis. 

## Result
Most SMHPs showed a passion for improving student mental health, which motivated them to continue delivering. Other SMHPs regarded the program as too complicated or impractical for their context. Overall, SMHPs showed great concern for their student mental health, the key driver or motivator. Quality improvement for TRAILS products could look like making programming more adaptable to specific cultural and institutional context. Likewise, programs should be able to be deployed quickly and seamlessly in a classroom. My report and analysis were reviewed by executive leadership and the clinical program team. 
 
 Additionally, I used this code to lead a qualitative analysis and coding training for the Research and Evaluation team.
