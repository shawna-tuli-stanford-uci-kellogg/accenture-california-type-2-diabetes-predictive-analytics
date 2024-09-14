![2560px-Accenture svg](https://user-images.githubusercontent.com/19508013/165648323-9c318167-71a7-4e3c-aa6d-4f1324f528b2.png)
![acc_applied_intell_wordmark_all_blk](https://user-images.githubusercontent.com/19508013/165773969-b2c06500-a26a-4d3f-9346-e3a058607307.png)
![avanade](https://user-images.githubusercontent.com/19508013/171925483-b62112fb-ae77-4a61-b74c-50187d7e8774.jpg)
![microsoft](https://user-images.githubusercontent.com/19508013/192884063-cd19b2ac-e5e3-4894-9adf-149792be39df.jpg)

Nominated for the Accenture V360 Awards in Innovation. 

# UCLA
• [Majority of California adults have prediabetes or diabetes](https://newsroom.ucla.edu/releases/majority-of-california-adults-have-prediabetes-or-diabetes)

# How AI can transform community health

Q1: How can we predict the risk of Type 2 diabetes in adults in California?

Q2: Are there any events, including lifestyle practices, educational level, family history, or health behaviors that are associated with the risk of Type 2 diabetes?

## Blood-sugar, data, and AI - How AI can transform community health

In the US, diabetes is the most expensive chronic condition and costs $237 billion annually. That equates to $1 out of every $4 is spent on direct medical costs for diabetes. The personal risk to diabetes patients is extensive and can include many issues including eye disease, kidney disease, heart disease, stroke and diabetes-related amputations.
What if there was an AI model that could help predict Type 2 diabetes? Could we help society and the individuals at risk? Accenture partnered with the University of California Irvine (UCI) to put the question to the test.
Accenture’s Applied Intelligence business uses the latest AI technologies to solve real-world challenges. This work is central to our commitment to harness the growing power of AI to improve outcomes that matter to everyone, helping to create a healthier, greener, and more sustainable world. These same goals are at the heart of Accenture’s purpose.
And those goals are at the heart of our partnership with the University of California Irvine (UCI) on their Data Science Capstone Program. The program enables computer science undergraduates at UCI to tackle serious problems and obtain real-world skills in problem-solving, planning and execution.
Last year, our UCI project helped to show how AI could be used to prevent wildfires. For this year’s challenge, we are exploring AI’s role in addressing the growing threat of Type 2 diabetes, which can have severe long-term health consequences for various segments of the population. In California alone, more than 3.2 million people (10.5% of the adult population) have been diagnosed with diabetes — and nearly half of all adults are prediabetic or not yet diagnosed with the condition*.

###### So what did we do to develop our framework?

## Identify, predict, and prevent

Identifying and predicting who might develop diabetes is a vital step toward prevention; the aim of this year’s 14-week program. By using data and AI to create a predictive model of the multiple factors that play a role in causing diabetes, we set out with the UCI Computer Science students to shape a new approach to help support wellness in our community.
As with any AI-led project, our first step was to identify, gather and evaluate the correct data. Because this is a health-related initiative, finding the right data can be complicated due to the sensitivities around personal information. That meant looking for publicly available data sets that we could use to conduct the required analysis. Having completed our initial search, we identified the most suitable data source to be the California Health Interview Survey. Spanning nearly a decade, this survey captures information across 785 different attributes in 12 key areas. It included demographic information, health behaviors, health insurance, employment, and income status.
Prepping for data analysis
Having gathered the correct data, students then set to work to process and transform it so that it was ready for exploratory data analysis. That narrowed down the number of attributes from 785 to 245 that could be turned into features. One of the issues that we needed to overcome was class imbalance. This is a common issue in health data, with a far higher proportion of negative cases. If not accounted for properly, the analysis can be biased. We dealt with this by using two different techniques, cost-sensitive learning and synthetic minority oversampling, which enabled us to adjust for error and bias.
Choosing the right model
We then tried several different machine-learning algorithms to identify which one worked best for our dataset and would provide the insights we were hoping to gain. Our final selection, XG Boost, combines several ML models to predict an outcome with the greatest accuracy.
We arrived at a set of 10 key risk factors for Type 2 diabetes, from age, sex, weight to diet and heart disease. These indicators will enable health and social services to identify specific risk factors and levels of impact in a given population.

## Impact

The impact that this model could have is boundless. We took publicly available data, a limited data set, and created an AI machine learning model. Imagine the possibilities of the model being used with quality data that is not limited.
A direct outcome could be that healthcare providers can predict who is at risk from diabetes and instituting educational programs. On a broader scale, the data and the insights developed could be used in urban planning, transportation, and public health by ensuring that decisions support strategic goals by holistically and innovatively.
We are proud of what our team has achieved. The end result of their work will be a paper submitted to the prestigious British Medical Journal Open Diabetes & Research Care. And the implications of what they developed could have a lasting and positive impact on public health.
For more about Accenture's AI capabilities, click here

*UCLA Health - https://www.uclahealth.org/u-magazine/majority-of-california-adults-have-prediabetes-or-diabetes

## Abstract

Type 2 diabetes is a rising problem among the California population, with nearly half of all
adults in California being pre-diabetic or undiagnosed. The purpose of this study is to determine
what factors may contribute to the presence of Type 2 diabetes, and whether the risk of Type 2
diabetes can be predicted using these factors. To achieve this, we analyzed public survey data
from the California Health Interview Survey (CHIS) - a statewide health survey conducted yearly
by the UCLA Center for Health Policy Research. Participants were aged 18 or older, and
important demographics and health topics, such as marital status, education, and exercise
tendencies, were recorded. The data analyzed spans over the course of 9 years, from 2012 to
2020 and the combined dataset contains about 190,000 surveyees and 785 covariates. After
performing feature selection using random forest classifiers, the number of relevant variables
for modeling was reduced to 245 covariates. The chosen variables were fitted using KNN,
stochastic gradient descent, decision trees, random forests, and XGBoost. To account for the
class imbalance of the dependent variable, we implemented cost-sensitive learning and SMOTE
to each model. The accuracy of each model was evaluated using its F1 and AUC scores. The
results indicate the XGBoost model had the highest scores. This model performed with a F1
score of 0.897 and an AUC score of 0.874. Given the results, the model demonstrated a strong
capability of accurately predicting the risk of Type 2 diabetes in California adults and the fitted
variables may be significantly tied to affecting the risk. Therefore, it can be valuable for an
individual to monitor these factors. In conclusion, the most significant factors for predicting the
risk of Type 2 diabetes is BMI, high blood pressure, and if they have prediabetes.
_______________________________________________________________________________________________________________________________________________________________

"Shawna brings great energy, thought and dedication to her work. She has a wide range of skills enabling her to contribute in different ways and be a high performer in various roles. Her strong work ethic makes her highly valuable." - Manish Dasaur (Accenture Chief Data & Analytics Officer, Communications & Media North America)

"I had the pleasure of working with Shawna while she was one of the key members from Accenture / Avanade team leading the students from University of California at Irvine in the Capstone course. During this course, leaders AI / Data Analytics from industry team up with student to utilize AI in addressing some of society challenges. 
Shawna led a data exploration and model development for predicting diabetes for different demographics in the state and helped build research-based credential.
Shawna led the team and did a great job - she is a true "Teacher at Heart" working well by helping and guiding the students vs. doing all the work and also "managed up" well when working with the professors. 
Thanks for the dedication, effort and the wonderful result. AI for the Good!!" - Marty Hodgett (Accenture Southern California Managing Director)

"It is an honor to provide feedback for Shawna on her above and beyond contribution to UC Irvine Capstone program which is part of Accenture/Avanade university outreach program. 
UC Irvine Outreach Program started in 2021 and it was established to form a close partnership with a local university for recruiting top talents, working with students on projects which impacts our community and clients and amplify our brand awareness. 
Shawna is leading Capstone Program engagement. Capstone courses give UC Irvine students the opportunity to put their skills to the test by letting them work with Accenture/Avanade to solve real-world problems. 
Let me say this; this engagement would not have been a success if Shawna wasn't there and throughout the two quarters where she assumed a role of manager and mentor for three students. 
Prior to the course kick-off, there is a huge challenge around finding a real-world problem with publicly available dataset that student can use to build Data and AI based product. Shawna worked with extreme diligence to find a comprehensive dataset for the use case to predict diabetes for the overall demographic of California. Based on this, we established an AI based product vision that is oriented around welfare of local community that students would work on for next 10 weeks. 
Shawna did a fantastic job in challenging students at times with critical thinking and supporting students when needed - sometimes on weekends. Shawna led a data exploration and model development for predicting diabetes for population of California and helped build research-based credential which is ready to be published on a credible research journal.
Shawna showed extreme patience and dedication to solve the people-related challenges and tirelessly worked with students to motivate them on solving for this complex Machine Learning model. She would handle communication with students, professor and senior managers and lead sprint demo, provide progress report and escalate issues. Throughout the program, there wasn't a single problem that Shawna couldn't solve. If it wasn't for Shawna's dedication, students wouldn't have delivered such product and credentials which our firm can use as credential in H&PS practice to sell more work. Based on this experience, I am convinced that Shawna is ready for the next level, and I fully support her promotion." - Vishrut Chokshi (Accenture Los Angeles Senior Manager, Data Science Enablement & Delivery Lead)

"Shawna is doing amazing job in leading the Accenture relationship with UC Irvine. She is spearheading the entire effort around Capstone Program which spans across two quarters where student work on a problem that is assigned to them by Accenture in the area of Data and AI. As a lead of this program, Shawna worked on 1. defining a problem that is around social good 2. identified relevant data 3. developed deliverables and timeline 4. helping and transitioning students. In addition, she is doing exemplary job keeping open communication with executive sponsors, keeping complete command on deliverables, understanding and solving technical challenges along the way. I am super excited to see Shawna grow in this role and very thankful for all the hard work that she does for this effort." - Vishrut Chokshi (Accenture Los Angeles Senior Manager, Data Science Enablement & Delivery Lead)

"I worked with Shawna as a mentor at UCI Data Science Capstone project on Predicting Risk of Type II Diabetes in California with AI. I was impressed with her exceptional communication skill and her eagerness to assist students. She was dedicated to answering students' questions and provided insightful responses. Also, her mentorship and coordination skills have undoubtedly contributed to the success of the team, which resulted in the project being published. In addition to her professional expertise, she consistently exhibits a friendly, patient, and unwaveringly positive demeanor. I was honored to have this great opportunity to collaborate with Shawna." - Mei-Chi Chen (Accenture San Francisco Software Engineer)

"Shawna was my mentor for a project course that was done in conjunction with Accenture. She has been extremely helpful in her role, and was always quick and eager to give advice and feedback. It is clear that she is extremely passionate about her role and has an incredible desire to make sure others are finding success." - Alvin Zou (UCI Data Science Graduate)

"I had the pleasure of having Shawna as my mentor for my UCI Data Science Capstone Project. Shawna mentored me for three months and provided advice not only on the project, but also on my career and personal life. She connected me with other professionals in the workplace who provided additional feedback on my project. What impressed me the most about Shawna was how passionate she was to make me succeed. She spared time on her days off to meet with me when I came across an issue in the project and patiently taught me when I made mistakes. I highly recommend Shawna because of how passionate she is about her job and how eager she is to share her knowledge with others to make them succeed." - Brian Wang (UCI Data Science Graduate)

"Shawna was the point of contact for a project my team was working on in conjunction with Accenture. Initially, her role was to answer any questions we had and provide some management over the progress and timeline of the project. However, Shawna went above and beyond in her mentorship. With regards to the project, she always made herself available to provide constructive feedback or give advice on how to approach problems we encountered. Outside the scope of the project, Shawna actively supported me by offering guidance on my career and ultimately helped me find a career path that I was not aware of before, but one that I believe is the right fit for me. She was able to empathize and understand who I was in order to make this judgement and I appreciate all of her words of encouragement and advice." - Kelly Im (UCI Data Science Graduate) 

![standard](https://user-images.githubusercontent.com/19508013/169395806-5f4e08f0-949e-4651-8f06-c9dfc00652b0.png)

![uci_Ics_d_fl_p7685](https://user-images.githubusercontent.com/19508013/165648227-43cf92b5-ec29-467e-bc83-44602f56bd18.png)

![UCLA-CHIS-logo-1-1024x285](https://user-images.githubusercontent.com/19508013/165639797-0fcc7fa3-6822-435d-9be5-1f1a7c277267.png)
