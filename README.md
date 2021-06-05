# Excess-Drug-Consumption-Classifier

The problem to be soved in this project is related to drug consumption and the lack of knowledge in identifying those who are most at risk at devloping excessive drug consumption 
habits for particular drugs. Although some drugs are illegal in many countries, and a lot of money has been spent on both tackling the produiction and tackling of 
said illegal drugs, this has not prevented their widespread usage. Additionally, even legally aquired drugs such as alcohol or nicotin through cigarettes are shown
to be harmful, with the exception of alcohol which is tolerable in more moderate doses. Addicition and misuse of drugs remains a constant battle with no resolution
insight. It costs the NHS and extraordinary amount of money and current very punitive methods to prevent it can backfire and create the opposite intended effect.
Taking the health harms, costs of crime and wider impacts on society together,we estimate the total costs of drugs to society in the UK are over £19 billion, which is more 
than twice the value of the market itself.
	
Through this project, it may be able to help inform of those most at risk for excessive drug consumption. The results of which may be useful for a variety of reasons:
- Directly find people who are at a higher risk and take more preventative measures when educating them on potential dangers to drugs.
- For addicts or people who are currently at risk of developing an addiction, if a certain facet of their personality is strong indicator for a given drug, it may easier to appeal to them in one way over another.
- Parent when raising their childer can understand how their child's personality and habits may or may not create complications through an addictive or bad coping mindset.
- 
The data used comes from a culmination of owners particularly: 
-Elaine Fehrman-Men's Personality Disorder and National Women's Directorate,Rampton Hospital, Nottingham
-Vincent Egan, Department of Psychiatry and Applied Psychology, University of Nottingham
-Evgeny M. Mirkes, Department of Mathematics, University of Leicester

Database contains records for 1885 respondents. For each respondent 12 attributes are known: Personality measurements which include NEO-FFI-R (neuroticism, extraversion, openness to experience, agreeableness, and conscientiousness), BIS-11 (impulsivity), and ImpSS (sensation seeking), level of education, age, gender, country of residence and ethnicity. All input attributes are originally categorical and are quantified. After quantification values of all input features can be considered as real-valued. In addition, participants were questioned concerning their use of 18 legal and illegal drugs (alcohol, amphetamines, amyl nitrite, benzodiazepine, cannabis, chocolate, cocaine, caffeine, crack, ecstasy, heroin, ketamine, legal highs, LSD, methadone, mushrooms, nicotine and volatile substance abuse and one fictitious drug (Semeron) which was introduced to identify over-claimers. For each drug they have to select one of the answers: never used the drug, used it over a decade ago, or in the last decade, year,month, week, or day.

Database contains 18 classification problems. Each of independent label variables contains seven classes: "Never Used", "Used over a Decade Ago", "Used in Last Decade", "Used in Last Year", "Used in Last Month", "Used in Last Week", and "Used in Last Day".

The predictors in this case will be all the attributes besides the classes for the drugs, which will be the labels. To convert this problem into a multi-label classification
problem, the classes will be compressed into a binary class indicating excessive and negligent usage.

A variety of evaluation metrics were investigated but the area under the roc curve was used to evaluate the models.

Determining the impact of the model on some of the stakeholder's KPIs may not be immediate given as the model is better suited to preventing excessive drug usage as opposed to curing it, but the success can be measured in a marked decrease in the people and costs associated with drugs.
