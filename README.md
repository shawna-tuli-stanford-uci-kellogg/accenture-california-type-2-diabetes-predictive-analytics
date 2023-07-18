![avanade](https://user-images.githubusercontent.com/19508013/171925483-b62112fb-ae77-4a61-b74c-50187d7e8774.jpg)

![2560px-Accenture svg](https://user-images.githubusercontent.com/19508013/165648323-9c318167-71a7-4e3c-aa6d-4f1324f528b2.png)

![acc_applied_intell_wordmark_all_blk](https://user-images.githubusercontent.com/19508013/165773969-b2c06500-a26a-4d3f-9346-e3a058607307.png)

![microsoft](https://user-images.githubusercontent.com/19508013/192884063-cd19b2ac-e5e3-4894-9adf-149792be39df.jpg)

# UCLA
• [Majority of California adults have prediabetes or diabetes](https://newsroom.ucla.edu/releases/majority-of-california-adults-have-prediabetes-or-diabetes)

# How AI can transform community health

Q1: How can we predict the risk of type 2 diabetes in adults in California?

Q2: Are there any events, including lifestyle practices, educational level, family history, or health behaviors that are associated with the risk of type 2 diabetes?

## Blood-sugar, data, and AI - How AI can transform community health

In the US, diabetes is the most expensive chronic condition and costs $237 billion annually. That equates to $1 out of every $4 is spent on direct medical costs for diabetes. The personal risk to diabetes patients is extensive and can include many issues including eye disease, kidney disease, heart disease, stroke and diabetes-related amputations.
What if there was an AI model that could help predict Type-2 diabetes? Could we help society and the individuals at risk? Accenture partnered with the University of California Irvine (UCI) to put the question to the test.
Accenture’s Applied Intelligence business uses the latest AI technologies to solve real-world challenges. This work is central to our commitment to harness the growing power of AI to improve outcomes that matter to everyone, helping to create a healthier, greener, and more sustainable world. These same goals are at the heart of Accenture’s purpose.
And those goals are at the heart of our partnership with the University of California Irvine (UCI) on their Data Science Capstone Program. The program enables computer science undergraduates at UCI to tackle serious problems and obtain real-world skills in problem-solving, planning and execution.
Last year, our UCI project helped to show how AI could be used to prevent wildfires. For this year’s challenge, we are exploring AI’s role in addressing the growing threat of Type-2 diabetes, which can have severe long-term health consequences for various segments of the population. In California alone, more than 3.2 million people (10.5% of the adult population) have been diagnosed with diabetes — and nearly half of all adults are prediabetic or not yet diagnosed with the condition*.

###### So what did we do to develop our framework?

## Identify, predict, and prevent

Identifying and predicting who might develop diabetes is a vital step toward prevention; the aim of this year’s 14-week program. By using data and AI to create a predictive model of the multiple factors that play a role in causing diabetes, we set out with the UCI Computer Science students to shape a new approach to help support wellness in our community.
As with any AI-led project, our first step was to identify, gather and evaluate the correct data. Because this is a health-related initiative, finding the right data can be complicated due to the sensitivities around personal information. That meant looking for publicly available data sets that we could use to conduct the required analysis. Having completed our initial search, we identified the most suitable data source to be the California Health Interview Survey. Spanning nearly a decade, this survey captures information across 785 different attributes in 12 key areas. It included demographic information, health behaviors, health insurance, employment, and income status.
Prepping for data analysis
Having gathered the correct data, students then set to work to process and transform it so that it was ready for exploratory data analysis. That narrowed down the number of attributes from 785 to 245 that could be turned into features. One of the issues that we needed to overcome was class imbalance. This is a common issue in health data, with a far higher proportion of negative cases. If not accounted for properly, the analysis can be biased. We dealt with this by using two different techniques, cost-sensitive learning and synthetic minority oversampling, which enabled us to adjust for error and bias.
Choosing the right model
We then tried several different machine-learning algorithms to identify which one worked best for our dataset and would provide the insights we were hoping to gain. Our final selection, XG Boost, combines several ML models to predict an outcome with the greatest accuracy.
We arrived at a set of 10 key risk factors for Type-2 diabetes, from age, sex, weight to diet and heart disease. These indicators will enable health and social services to identify specific risk factors and levels of impact in a given population.

## Impact

The impact that this model could have is boundless. We took publicly available data, a limited data set, and created an AI machine learning model. Imagine the possibilities of the model being used with quality data that is not limited.
A direct outcome could be that healthcare providers can predict who is at risk from diabetes and instituting educational programs. On a broader scale, the data and the insights developed could be used in urban planning, transportation, and public health by ensuring that decisions support strategic goals by holistically and innovatively.
We are proud of what our team has achieved. The end result of their work will be a paper submitted to the prestigious British Medical Journal Open Diabetes & Research Care. And the implications of what they developed could have a lasting and positive impact on public health.
For more about Accenture's AI capabilities, click here

*UCLA Health - https://www.uclahealth.org/u-magazine/majority-of-california-adults-have-prediabetes-or-diabetes

# Abstract

Type 2 diabetes is a rising problem among the California population, with nearly half of all
adults in California being pre-diabetic or undiagnosed. The purpose of this study is to determine
what factors may contribute to the presence of type 2 diabetes, and whether the risk of type 2
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
capability of accurately predicting the risk of type 2 diabetes in California adults and the fitted
variables may be significantly tied to affecting the risk. Therefore, it can be valuable for an
individual to monitor these factors. In conclusion, the most significant factors for predicting the
risk of type 2 diabetes is BMI, high blood pressure, and if they have prediabetes.
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

# Presentation

![image](https://user-images.githubusercontent.com/19508013/177665861-fa9560b6-191a-433a-bb79-f81a1a471336.png)

<img width="1014" alt="Screen Shot 2023-02-22 at 5 46 49 PM" src="https://user-images.githubusercontent.com/19508013/220808978-f1472f5e-c123-4af6-bdab-da37c6e6456c.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 46 54 PM" src="https://user-images.githubusercontent.com/19508013/220809065-a145c108-b8c9-4900-babb-c63eebef0d97.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 47 00 PM" src="https://user-images.githubusercontent.com/19508013/220809069-06984013-fcf7-42e7-8036-40e2f79c2712.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 47 18 PM" src="https://user-images.githubusercontent.com/19508013/220809070-1fcf0033-cb9c-4104-af92-e88939ba3589.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 47 23 PM" src="https://user-images.githubusercontent.com/19508013/220809071-877317ad-27a6-4436-af0a-c42adc48b537.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 47 28 PM" src="https://user-images.githubusercontent.com/19508013/220809073-96bb803d-193c-4094-a2bf-4d8d07ff1827.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 47 32 PM" src="https://user-images.githubusercontent.com/19508013/220809075-b1894140-5a80-4be8-9855-d656d4718662.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 47 36 PM" src="https://user-images.githubusercontent.com/19508013/220809077-449b7797-4177-4880-8465-f21357d4ec2f.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 47 47 PM" src="https://user-images.githubusercontent.com/19508013/220809078-081cf77f-afdd-4a28-9be0-f63c1bd6a171.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 47 51 PM" src="https://user-images.githubusercontent.com/19508013/220809080-22ff4b0e-86bd-4c26-9e48-64d5ab7789b6.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 47 54 PM" src="https://user-images.githubusercontent.com/19508013/220809082-2d6b6255-e822-476f-94c4-1a283756c785.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 47 59 PM" src="https://user-images.githubusercontent.com/19508013/220809084-468e29de-d4ef-46df-a6d1-a2fdb74abd2d.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 48 04 PM" src="https://user-images.githubusercontent.com/19508013/220809086-507a0870-57c1-4fc7-8736-cf823f3a863d.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 48 11 PM" src="https://user-images.githubusercontent.com/19508013/220809087-5e70bffc-2d19-4950-8b9c-45d899b10bc5.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 48 15 PM" src="https://user-images.githubusercontent.com/19508013/220809088-1d490352-9bfe-433a-b206-5c1436fc72ec.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 49 06 PM" src="https://user-images.githubusercontent.com/19508013/220809090-2b16104b-e01e-4129-966b-006878295ad1.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 49 34 PM" src="https://user-images.githubusercontent.com/19508013/220809092-0fe46ccb-13d2-4d7a-8360-fdd84f54ca5a.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 49 39 PM" src="https://user-images.githubusercontent.com/19508013/220809094-a4be38ac-e004-4203-82f0-fd72ef9cdff0.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 49 42 PM" src="https://user-images.githubusercontent.com/19508013/220809095-60d47d17-031d-442c-ac75-b1f5dec1cbbd.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 50 55 PM" src="https://user-images.githubusercontent.com/19508013/220809097-c99c904a-eb1a-4f53-bfeb-f0ce58ff8679.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 50 58 PM" src="https://user-images.githubusercontent.com/19508013/220809100-c895bdd1-28eb-4e0e-8fe6-72dd1278ed28.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 51 06 PM" src="https://user-images.githubusercontent.com/19508013/220809101-183b697d-ed22-4ccb-931d-2f2968f628d6.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 51 10 PM" src="https://user-images.githubusercontent.com/19508013/220809103-fb8b1a80-b81f-4185-b512-a4e1a91d6fad.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 51 19 PM" src="https://user-images.githubusercontent.com/19508013/220809104-d13026d8-05e1-41fb-aa77-5204c4b33337.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 51 25 PM" src="https://user-images.githubusercontent.com/19508013/220809105-d37485c4-e033-4a47-94fe-9d3592eceea3.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 51 35 PM" src="https://user-images.githubusercontent.com/19508013/220809107-c460b646-7d3b-47f8-9391-b14bbf73fa07.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 51 38 PM" src="https://user-images.githubusercontent.com/19508013/220809109-b7a57dfd-9712-46aa-b19a-5f7ac2111f20.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 51 42 PM" src="https://user-images.githubusercontent.com/19508013/220809111-47523c28-4d8d-4842-841d-69e4fa813466.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 51 52 PM" src="https://user-images.githubusercontent.com/19508013/220809113-2b107809-ceb4-45f7-9249-3da365f90410.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 51 56 PM" src="https://user-images.githubusercontent.com/19508013/220809114-9af3691d-c0db-470f-a583-33608733a95d.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 52 06 PM" src="https://user-images.githubusercontent.com/19508013/220809115-00d62d7b-74c0-4239-993b-99a44c99bf88.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 52 10 PM" src="https://user-images.githubusercontent.com/19508013/220809117-f3b16671-b461-432a-bbd7-24fd9d24db33.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 52 13 PM" src="https://user-images.githubusercontent.com/19508013/220809119-0d9d7477-5628-46be-9fb1-890c3be7db13.png">
<img width="1014" alt="Screen Shot 2023-02-22 at 5 52 17 PM" src="https://user-images.githubusercontent.com/19508013/220809121-33b846e2-7642-4cb5-8274-9e0d819727dc.png">

# Student Presentation

![image](https://user-images.githubusercontent.com/19508013/171302807-bbd09064-e7fe-4ff2-8060-ebff2525ec11.png)

<img width="1169" alt="Screen Shot 2022-05-31 at 9 31 47 PM" src="https://user-images.githubusercontent.com/19508013/171328089-45bfb4bb-bd07-465c-b6ad-d82ab3beee26.png">

<img width="1165" alt="Screen Shot 2022-05-31 at 9 32 05 PM" src="https://user-images.githubusercontent.com/19508013/171328122-9ec0703c-c909-4d9b-b3f7-d93b86e3648a.png">

<img width="1164" alt="Screen Shot 2022-05-31 at 9 32 29 PM" src="https://user-images.githubusercontent.com/19508013/171328167-ec97bf10-183d-475a-80a1-b8c863e3d007.png">

<img width="1167" alt="Screen Shot 2022-05-31 at 9 32 55 PM" src="https://user-images.githubusercontent.com/19508013/171328215-26703c02-a957-4516-bffc-73a8f3e4aae3.png">

<img width="1166" alt="Screen Shot 2022-05-31 at 9 33 18 PM" src="https://user-images.githubusercontent.com/19508013/171328259-7b9e8fe4-b3e1-4579-8dac-de09832f5dca.png">

<img width="1167" alt="Screen Shot 2022-05-31 at 9 33 45 PM" src="https://user-images.githubusercontent.com/19508013/171328298-743e7aa8-c4a0-4790-888f-1ab958cad7aa.png">

<img width="1168" alt="Screen Shot 2022-05-31 at 9 34 08 PM" src="https://user-images.githubusercontent.com/19508013/171328326-b662128c-273e-47ff-8ea9-7d69abe5ab63.png">

<img width="1166" alt="Screen Shot 2022-05-31 at 9 34 34 PM" src="https://user-images.githubusercontent.com/19508013/171328368-4a563c81-99c3-4fd9-9e4b-57d253a756a9.png">

<img width="1164" alt="Screen Shot 2022-05-31 at 9 35 01 PM" src="https://user-images.githubusercontent.com/19508013/171328416-48e37eb2-8eff-4b70-aa5f-b94a859bab1b.png">

<img width="1165" alt="Screen Shot 2022-05-31 at 9 35 27 PM" src="https://user-images.githubusercontent.com/19508013/171328446-04f18cf3-4b75-4516-8bbd-07ce741029f3.png">

<img width="1165" alt="Screen Shot 2022-05-31 at 9 35 49 PM" src="https://user-images.githubusercontent.com/19508013/171328476-803e54c1-91c1-483e-b221-6f68fff6a78f.png">

<img width="1169" alt="Screen Shot 2022-05-31 at 9 36 11 PM" src="https://user-images.githubusercontent.com/19508013/171328528-e6a781a2-2f07-444f-bbce-aa07c9a688b9.png">

<img width="1165" alt="Screen Shot 2022-05-31 at 9 36 31 PM" src="https://user-images.githubusercontent.com/19508013/171328543-582243db-3a78-4778-bd3b-798a69c50dfa.png">

<img width="1167" alt="Screen Shot 2022-05-31 at 9 37 04 PM" src="https://user-images.githubusercontent.com/19508013/171328597-8aa41568-9df5-4151-84b6-170e420ac622.png">

<img width="1165" alt="Screen Shot 2022-05-31 at 9 37 23 PM" src="https://user-images.githubusercontent.com/19508013/171328620-d7e0e2e3-ad37-4dfa-9808-cde20131105f.png">

<img width="1168" alt="Screen Shot 2022-05-31 at 9 37 44 PM" src="https://user-images.githubusercontent.com/19508013/171328655-c1ad3da6-f90a-4e35-bcf7-7fbcfa8ebd74.png">

<img width="1165" alt="Screen Shot 2022-05-31 at 9 38 11 PM" src="https://user-images.githubusercontent.com/19508013/171328725-c9182259-eeac-4818-b82f-897c40b5ea3c.png">

<img width="1164" alt="Screen Shot 2022-05-31 at 9 38 42 PM" src="https://user-images.githubusercontent.com/19508013/171328790-171ff245-bd0c-484a-9729-bcdaf735d075.png">

<img width="1166" alt="Screen Shot 2022-05-31 at 9 39 09 PM" src="https://user-images.githubusercontent.com/19508013/171328846-432b868d-4fd7-4487-b72d-c623f9aaf04e.png">

<img width="1166" alt="Screen Shot 2022-05-31 at 9 39 29 PM" src="https://user-images.githubusercontent.com/19508013/171328884-98abb0cf-89eb-4d87-a22b-e46166fe661f.png">

<img width="1163" alt="Screen Shot 2022-05-31 at 9 39 59 PM" src="https://user-images.githubusercontent.com/19508013/171328940-7bd52057-1d06-4099-a3ee-dbb30966376f.png">

<img width="1166" alt="Screen Shot 2022-05-31 at 9 40 15 PM" src="https://user-images.githubusercontent.com/19508013/171328972-3cc404c9-6e27-45e2-b6a8-00b84fb65753.png">

<img width="1164" alt="Screen Shot 2022-05-31 at 9 40 36 PM" src="https://user-images.githubusercontent.com/19508013/171329013-c9fb1ab5-3285-4b30-9c01-e1314aff729b.png">

<img width="1164" alt="Screen Shot 2022-05-31 at 9 41 07 PM" src="https://user-images.githubusercontent.com/19508013/171329064-a8faf429-6f9d-4b35-9b76-07ce171687aa.png">
