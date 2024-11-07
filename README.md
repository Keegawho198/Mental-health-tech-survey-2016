#Mental-Health-tech-survey-2016 Project

Link to dataset:
https://www.kaggle.com/datasets/osmi/mental-health-in-tech-2016/data

    ReadMe edit
  https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#images



#Project – Mental Health in Tech Companies 2016

To save you time, here is the summary of this project. For a more detailed explanation of how our data was extracted, cleaned and visualized feel free to read past the TLDR.

Summary  TLDR:
Mental health in the tech workplace is marked by stigma, gender disparities in seeking help, and significant challenges despite available support. Many employees feel their productivity is impacted, highlighting the need for comprehensive mental health initiatives. A multifaceted approach is essential, focusing on awareness, stigma reduction, and accessible resources to foster a healthier workplace culture that benefits both employees and productivity.


--------------------------------------------------------------------------------------------------------
Project Analysis
Mental Health in Tech: People working in tech are often at their desks for extended amounts of time. In this project, we explored how this trend correlates with mental health within the tech industry.

Background:
Since 2009, every second Thursday of September is  R U OK Day, a day to increase awareness and encourage conversations around mental health. We wanted to see if mental health was being addressed years later using a 2016 survey of individuals who work in the tech industry.

Project Aim:
This project aims to uncover potential influences and trends on mental health and treatment-seeking behavior in the tech industry.


The main questions we used to guide our analysis were:
1.	Does mental health interfere with work?
2.	Do males seek mental health treatments less often than females in tech companies?
3.	Is mental health more prevalent in different regions? Does the USA have a bigger issue with mental health compared to other countries?
4.	How do employees perceive their workplace culture regarding mental health?


About Our Data
Our data was found from a Kaggle dataset called OSMI Metal Health in Tech Survey 2016. 
Link: https://www.kaggle.com/datasets/osmi/mental-health-in-tech-2016/data
This data was gathered from a survey of individuals who volunteered and worked within the tech industry. 
Questions ranged from whether they had a mental illness and were diagnosed by a medical professional or Does your workplace have any well-being programs. 

Potential Limitations
Upon cleaning the data, it was found that many individuals who did the survey were not from the same location. The vast majority of people who did the survey were from the USA and many of the other people who did the survey were from the outside. From this, we decided to use this as one of our questions and compare the USA to the rest of the world if mental health was more of a problem.
It should also be noted that 840 of the responses were from the USA and 593 were from outside the USA. From this, it was decided that we would use percentages to fairly display the results found from the data as if we were to use the whole numbers it may unfairly represent the USA compared to the rest of the world.
Cleaning the data
From going through the data, many of the questions were very long and although very useful, we did not need all the questions to answer our questions. 
Our first step when cleaning the data was to rename relevant questions that would help guide our analysis. 
For example:
'Have you been diagnosed with a mental health condition by a medical professional?’
To 
‘Diagnosed by professional?’

We checked for NaN values and removed those responses based on the question that we needed to answer. While keeping the original Dataframe intact in case we needed to go back and if we did not need to remove them based on what questions were being answered.





Analysis Question 1: Does mental health interfere with work?
First, we broke down our main question into 3 sub-questions to find a clearer answer to our main question.
Our sub-questions were:
•	Do you think you have a mental disorder?
•	Do you think your productivity is ever affected by mental health issues?
•	What percentage of your work time is affected by mental health issues?

We first looked at the question: Do you think you have a mental disorder?
From what was found, 40.1% of respondents reported 'yes' which indicates that mental health is a critical issue that may need to be addressed in this industry. 
The 22.8% who responded 'maybe' reflects a level of uncertainty or lack of awareness regarding mental health disorders. This could point to the need for more education and resources about mental health in the workplace.
The 37.1% who said 'no' indicates that individuals do not identify with having a mental health disorder. However, this figure is still lower than the percentage of those who believe they do, which may suggest that mental health issues are more common than perceived.
Given the high percentage of individuals acknowledging mental health disorders, it may be beneficial for tech companies to implement mental health initiatives, such as wellness programs, mental health days, and access to counseling services. This could help create a more supportive environment for employees.

 ![alt text](https://github.com/Keegawho198/Project-1_Mental-Health/blob/main/output/Lishi_f1_Responses%20to%20Mental%20Health%20Disorder%20Inquiry.png)



Our next question was: Do you think your productivity is ever affected by mental health issues?
From our findings when looking at this question, the majority (88.7%) of individuals with a mental disorder believe that their productivity is affected. Meanwhile, 7.3% are uncertain, and only 4.0% reported that it does not impact their productivity.
The fact that 88.7% of individuals believe their productivity is affected by their mental disorder indicates a strong awareness of the relationship between mental health and work performance. This suggests that mental health issues are a significant concern for a large portion of the workforce.
With only 4% reporting that their productivity is not impacted, it highlights that very few individuals feel unaffected by their mental health challenges. This could imply that mental health disorders are commonly perceived as disruptive to work.
The 7% of respondents who are uncertain about the impact on their productivity may reflect a lack of awareness or understanding of how their mental health affects their work. This uncertainty could be an opportunity for organizations to provide education and resources to help individuals better understand their situations.
The overwhelming majority indicating that their productivity is affected suggests a strong need for workplaces to address mental health issues proactively. This could include implementing mental health programs, providing access to counseling services, and creating a supportive work environment.

 
![alt text](https://github.com/Keegawho198/Project-1_Mental-Health/blob/main/output/Lishi_f2_believe%20your%20productivity%20is%20ever%20affected%20by%20a%20mental%20health%20issue.png) 



Our final sub-question was: What percentage of your work time is affected by a mental health issue?

When it comes to the extent to which mental health disorders interfere with work, the responses were as follows: 
•	39.1% indicated minimal influence (1-25%)
•	31.8% reported moderate influence (26-50%)
•	18.2% noted moderate to severe influence(51-75%)
•	10% believed that mental health disorders could have a substantial impact on their work (76-100%).
The fact that 39.1% of respondents reported minimal influence (1-25%) indicates that a significant portion of individuals may be managing their mental health challenges effectively.
With 31.8% reporting moderate influence, it indicates that a substantial number of individuals experience some level of disruption in their work due to mental health issues.
The 18.2% who noted moderate to severe influence, along with the 10% who believe in a severe impact (76-100%), highlights a critical area of concern. This indicates that almost 1/3 of the workforce is significantly affected, which could lead to decreased productivity, increased absenteeism, and higher turnover rates.
This raises the need for awareness and resources related to mental health in the workplace. Organizations might consider implementing mental health programs, providing training for managers, and fostering a supportive environment to help those who are affected.




![alt text](https://github.com/Keegawho198/Project-1_Mental-Health/blob/main/output/Lishi_f3_Work%20time%20%25%20affected%20by%20a%20mental%20health%20issue.png)



 

From our findings, to answer the main question: Does mental health interfere with work? 
The answer is yes; about 90% of people with mental health disorders suggested that their work is affected to varying degrees, with about one-third reporting moderate to severe impacts.





Analysis Question 2: Do males seek mental health treatment less often than females in the tech industry?
Moving on to the next question, we wanted to see differences in males compared to females in regards to who was more likely to seek treatment

From our findings, we found that males are more inclined to seek treatment compared to females. This may suggest that males tend to be more proactive in seeking mental health support, while females are more likely to avoid or delay treatment.
However, it should be kept in mind that while more males are likely to seek treatment, they tend to have a greater rate of suicide compared to women. 
This bar graph shows the overall count of males and females who have sought mental health treatment, regardless of their country. The data is grouped by gender to identify how frequently males and females seek help from mental health professionals in the tech industry



![alt text](https://github.com/Keegawho198/Project-1_Mental-Health/blob/main/output/GenderSeekHelpBar.png)
 

Comparing the USA to rest of the world
The data is broken down by gender when comparing mental health treatment-seeking behavior between the United States and other countries. The grouped bars (one set for the US and one for non-US countries) show how males and females behave in terms of seeking mental health treatment in different regions. 

We consistently see that males are more likely to seek mental health treatment than females in the tech industry, both in the United States and globally. These insights may highlight the need for gender-sensitive approaches to mental health support in the tech industry, especially encouraging females to seek the care they need.

 ![alt text](https://github.com/Keegawho198/Project-1_Mental-Health/blob/main/output/GenderCountriesSeekHelp.png)




Analysis Question 3: Is mental health more prevalent in different regions? Does the USA have a bigger issue with mental health compared to the rest of the world?

While asking this question to guide our analysis, we also focused on individuals who sought treatment and were diagnosed by a medical professional and if their workplace offered any well-being support.

From that, our data indicates that individuals in the USA are significantly more likely to seek mental health treatment, with the number of responses seeking help being doubled compared to countries outside the USA.
In contrast, there is a slight increase in the number of individuals outside the USA who report not seeking treatment. 
This disparity may suggest that mental health is prioritized more highly in the USA compared to other countries, highlighting potential cultural differences in the perception and importance of mental health care 

Numbers below

![alt text](https://github.com/Keegawho198/Project-1_Mental-Health/blob/main/output/mental_health_treatment_responses.png)
 
USA - YES: 550 (65.48%)- NO: 289 (34.52%)
Outside USA - Yes: 290 (48.74%) - NO: 304 (51.26%)


Individuals in the USA are significantly more likely to seek mental health treatment, with 65.48% of responses indicating they have sought help compared to only 48.74% of individuals outside the USA. Specifically, in the USA, 550 individuals reported seeking treatment (Yes), while 289 did not (No). In contrast, 290 individuals outside the USA sought treatment, while 304 reported not seeking help.
This Visible difference suggests that mental health is prioritized more highly in the USA compared to other countries, highlighting cultural differences in the perception and importance of mental health care.
The higher percentage of treatment-seeking behavior in the USA may be influenced by factors such as greater public awareness, access to mental health resources, and reduced stigma surrounding mental health issues.
Also, the slight increase in the number of individuals outside the USA who report not seeking treatment (51.26%) compared to those who do (48.74%) raises questions about the barriers to mental health care in those regions. This trend indicates a need for improved mental health awareness and resources in countries outside the USA.
















Workplaces that offer help for Mental Health (USA vs Outside) 
Our data indicates that 33% of respondents in the USA reported that their workplace offers mental health support, compared to only 18% of respondents from countries outside the USA.
In the USA, 40% responded "No" and 27% answered, "I don't know." Compared to outside the USA, 63% responded "No" and 19% said "I don't know."
These findings suggest that while both regions have significant portions of individuals who are uncertain or do not receive mental health support, the USA demonstrates a greater emphasis on mental health initiatives in the workplace.
This reinforces the notion that mental health may be prioritized more highly in the USA compared to other countries.


![alt text](https://github.com/Keegawho198/Project-1_Mental-Health/blob/main/output/HelpOfferedInWorkplaces.png)


 
Data percentages USA yes: 33%, NO: 40%, IDK: 27% 
Outside USA: YES: 18%, no: 63%, IDK: 19%

In our findings of workplace mental health support, we found notable differences between responses in the USA and those from other countries.
In the USA, 33% reported that their workplace offers mental health support, while only 18% of respondents from outside the USA indicated the same.
It is important to note that 40% of respondents in the USA answered "No" to the question of whether their workplace provides mental health support, and 27% responded "I don't know." In contrast, among respondents from other regions, 63% answered "No," and 19% said "I don't know."
These findings suggest that while a significant portion of individuals in both regions are uncertain about or do not receive mental health support, the USA appears to place a greater emphasis on mental health initiatives in the workplace. This further reinforces a higher prioritization of mental health in the USA compared to other countries.
However, the data also highlights a concerning trend: despite having more workplace treatment options for mental health, the USA faces a larger issue with mental health challenges among its workforce.






Analysis Question 4: How do employees perceive their workplace culture regarding mental health?
With our final main question, we looked into people’s willingness to discuss physical health issues compared to mental health issues.
We found that 44% of people are somewhat willing to discuss physical health issues ("Maybe Yes"). While 25% are willing to discuss physical health openly ("Yes"). 
However 62% of people are unwilling to discuss mental health issues ("No"). 
Only 8% are willing to discuss mental health openly ("Yes"). 
So we could see that although organizations are focusing on raising awareness through initiatives like Are You Okay Day, people are still far more comfortable discussing physical health than mental health.



![alt text](https://github.com/Keegawho198/Project-1_Mental-Health/blob/main/output/WillingToDiscussHealth.png)
 



We then looked at the individuals who believed that mental health did have an impact on their career.
A survey question about the impact of being identified with a mental health issue on one's career is designed to uncover the reasons why people may be reluctant to discuss mental health. 
51% of respondents firmly believe mental health issues could impact careers and 32% believe the health issue may impact careers. However, Only 10 % report actual negative career impacts.
So a significant majority of people perceive mental health issues as a potential threat to career progression, which may lead to hesitation in disclosing mental health concerns. However, there is a clear discrepancy between perception and reality. While many people have concerns about career progression, the actual number of those affected is much lower.
Understanding the stigma surrounding mental health is crucial, as it remains a significant barrier to open discussions and support. Many individuals still hold the belief that mental health challenges can negatively impact their careers, which reflects the ongoing stigma that persists in professional environments.
By fostering supportive environments in the workplace, organizations can help employees feel more comfortable seeking help, ultimately promoting a healthier, more inclusive, and productive work culture.

![alt text](https://github.com/Keegawho198/Project-1_Mental-Health/blob/main/output/ImpactWithMentalHealthCareer.png)
 

Conclusion
The analyses of mental health in the workplace, particularly within the tech industry, reveal a complex landscape characterized by significant disparities, prevalent stigma, and the urgent need for comprehensive support systems.
Firstly, there is a notable reluctance to discuss mental health issues, This highlights a persistent stigma that organizations must address to foster a culture of openness and support.
Secondly, gender disparities in seeking mental health treatment are evident, as males are more likely to pursue help than females. This suggests the need for gender-sensitive strategies within organizations to encourage all employees to access mental health resources.
Additionally, despite the higher availability of workplace mental health support, the USA compared to the rest of the world, still faces significant mental health challenges, indicating that access alone is insufficient without addressing underlying issues and stigma.
Finally, high amounts of employees believe their productivity is affected. This underscores the critical need for tech companies to implement comprehensive mental health initiatives, such as wellness programs and counseling services, to create supportive environments that enhance employee well-being and productivity.
To summarize, addressing mental health in the workplace requires a multifaceted approach that includes raising awareness, reducing stigma, and providing accessible resources. By prioritizing mental health, organizations can foster a healthier, more inclusive workplace culture that ultimately benefits both employees and the overall productivity of the organization.

Final Suggestions
•	Make sure employees know that their workplace has a well-being program.
•	Reinforce it by mentioning it in meetings and hanging posters around the office.
•	Companies that don’t have one should implement one that is working.
•	Or begin to research how a well-being initiative can benefit an individual.




  



