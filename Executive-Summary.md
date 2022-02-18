**Technical Report**

**Problem Statement**
Our team has the great honor of being invited to the "Social Impact Forum: How we use technology to help solve social issues in today's world." The topic we choose together is hate crimes. Due to the recent pandemic, hate crimes have increased, especially in the Asian American community. Although, due to increasing reports of hate crimes, does that mean a victim will find justice? So, the question we pose to answer is: "How likely is it that a hate crime will face prosecution given the specific characteristics of the crime and the demographics of the county where it occurred? We will determine what features will play a significant role in determining if the victim's case will face prosecution justice through our research. 

Furthermore, we have focused on California because, according to the FBI, California has the highest bias-motivated hate crimes within the US for 2020. Therefore, we thought the best strategic plan to answer this question with great detail would be through data science and machine learning. Next, we thought it would be best to use classification models to help us infer correlations, derive insights, and design a system to help judge whether a hate crime will face prosecution within the victim's county.

**Background**
It is only recently that victims of hate crimes will receive a chance to seek justice against their attacker due to the installment of particular hate crime acts from congress. We are talking about only 32 years from the beginning of the "Hate Crimes Statistics Act" in Feb 1990 but only 13 years where the "The Local Law Enforcement Hate Crimes Prevention Act" was instated on a federal level in 2009. 

To understand how the judicial process of hate crimes begins, one must file a report to their local police precinct. Then it is up to the police to decide and check the laws in that county or state if it counts as a hate crime. After this, if the police deem it so, it will move up to the district attorney's office for a higher chance of prosecution. The major flaw within this process and this negative bias are that it is all up to police officers to decide a victim's fate. What would happen if the police officers were racist? What can we do to fix this process so victims' cases can reach prosecution and get justice?
 
One would think that hate crimes would decrease, but we are finding the opposite. The extensive research we have learned about hate crimes is why we have taken the call to answer the questions stated above. With more people becoming aware of the judicial process of hate crimes and the statistics that follow them, we collectively can find solutions to this cancerous topic. 

**Data Dictionary**
|Feature|Type|Dataset|Description|
|---|---|---|---|
|classification|object|classification_data|Data we used to create our models without EDA graphics|
|hate crimes and prosecution| object| hate_crimes_and_ prosec_all_years | A merged dataset to help us create EDA visualizations. 
|prosecution_all_year|object|prosecution_all_year|Clean version of the prosecution all years before the merge. Helped to create EDA visuals

**Summary Statistics**



**Recommendations**
Through the vast knowledge we have gained from tackling the social issue of hate crimes, we recommend:
1. Where you live (city or county) is a crucial feature in prosecuting your case.
2. Adapting the Random Forest Classification model will be the foundational design for all hate crimes reported.
3. Victims are more likely to report crimes if they know they will be prosecuted and pressuring prosecutors to have higher hate crime conviction rates.

**Conclusions**
(Did we answer the problem statement...?)


In addition, our research has noticed a trend that hate crimes increase around momentous societal events. For example, in 2001, the 9/11 attacks, Muslim communities were severely targeted with hate crimes, or today around the Corona Virus pandemic, Asian American communities are the new targets for violence. With these events, it is more than enough reason to design random forest models to help increase the classification to help victims get their case to prosecution.

**Sources**
https://openjustice.doj.ca.gov/data
https://www.justice.gov/hatecrimes/hate-crime-statistics
https://ucr.fbi.gov/hate-crime/2018/topic-pages/incidents-and-offenses
https://www.usnews.com/news/best-states/articles/2020-11-17/fbi-report-california-new-york-report-highest-numbers-of-hate-crimes
https://www.hrc.org/resources/hate-crimes-timeline