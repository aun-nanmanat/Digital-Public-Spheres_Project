# Policy Brief: The Spread of Misinformation and Disinformation on Reddit: The Case Study of Vegan and Meat Consumption
## Project Overview
### Objective: 
To analyze how misinformation and disinformation about veganism and meat consumption spread on Reddit, and to propose actionable recommendations for the World Health Organization (WHO) to improve public understanding and promote accurate dietary information.

### Key Techniques and Methodologies:
- **Data Extraction:** Employed web scraping with Reddit's API to collect comments from relevant subreddits.

- **Data Preprocessing:** Cleaned and processed text data to ensure reliability, and removed flagged comments.

- **Topic Modeling:** Used Latent Dirichlet Allocation (LDA) to uncover hidden themes in discussions.

- **KMeans Clustering:** Identified key themes and organized data into groups based on similarities.

- **Sentiment Analysis:** Analyzed sentiment polarity using TextBlob, and visualized sentiment distribution.

### Key Findings:
- **Impact of Misinformation:** Inaccurate information on Reddit significantly influences public perceptions of dietary behaviors.

- **Demand for Reliable Information:** Users showed a clear demand for scientifically evidence-based information about dietary topics.

- **Sentiment Trends:** Predominantly negative sentiments were observed in discussions about veganism, with critical views towards vegan diets.

### Model Performance:
- **Topic Modeling:** Revealed complex discourse on health and nutrition aspects of veganism and meat consumption.

- **KMeans Clustering:** Highlighted a range of concerns and discussions, emphasizing the need for reliable information.

- **Sentiment Analysis:** Demonstrated varying degrees of sentiment, with most datasets showing a majority of negative sentiments.

### Policy Recommendations for WHO:
- **Engagement on Social Media:** Create an official Reddit profile, and conduct Ask Me Anything (AMA) sessions.

- **Monitoring and Education:** Increase monitoring of misinformation trends, and develop targeted educational resources.

- **Collaboration with Organizations:** Work with entities like NewsGuard to combat disinformation.

### Impact:
- **Enhanced Public Health Communication:** Improved quality of public health discourse on dietary choices.

- **Informed Eating Choices:** Promoted accurate dietary information, enhancing global health outcomes.

### Challenges and Considerations:
- **Technical Expertise and Resources:** Addressing challenges related to technical expertise, resource allocation, and potential resistance from online communities.
Conclusion:

- **Importance of Trustworthy Information:** Highlighted the critical need for reliable information in shaping public discourse.

- **Proactive Interventions:** Proposed strategies to counteract misinformation and foster informed healthy public dialogue.

## Executive Summary
The increasing number of misinformation and disinformation across various social media platforms has become one of the big issues that we must be aware of and pay attention to. Our policy brief addresses the prevalent issue of inaccurate information affecting public perceptions of diet and health on a digital platform. Therefore, our primary goal is to provide actionable insights and evidence-based recommendations for a policy framework to promote accurate information and improve public understanding of dietary choices in the online community. With a focus on Reddit, this study aims to offer several data-driven insights and apply various analytical techniques including topic modeling, KMeans clustering, and sentiment analysis on text to systematically analyze how misinformation and disinformation about veganism and meat consumption are spread and their impact on public audience surrounding health and nutrition decisions.

Our results emphasize the impact of inaccurate or misleading material on Reddit on people’s perceptions of dietary behaviors and the significance of access to reliable information. Additionally, our findings also show the demand from some users on Reddit for scientifically evidence-based information about dietary-related topics. By providing a comprehensive overview of how misleading information distorts public dialogue concerning diet, the brief proposes actionable recommendations for the World Health Organization (WHO). These include engaging directly on social media, enhancing monitoring of misinformation trends, and developing targeted educational resources aimed at improving the public’s dietary decisions and health outcomes.

## Introduction
Since the evolution of the Internet has transformed conventional modes of human interaction and introduced novel avenues for communication (Chen & Lin, 2019), it is imperative to recognize the importance of a well-functioning digital public sphere on online platforms as primary channels for communication. Despite geographical distances and differences, members of the online community might consider themselves as part of common public discourses in which everyone contributes equally and engages in public reasoning. To function successfully, a democratic public sphere must provide rights and opportunities that guarantee equitable and meaningful freedom of expression (Cohen & Fung, 2021).

Nowadays, social media has evolved as an attractive tool for the majority of people to obtain information on personal interests, and trending societal concerns, and as a source of leisure and relaxation (Ye, 2023). Social media, which covers a wide range of online platforms, may encourage online interactions, user-generated content production, and involvement in virtual communities (Dewing, 2010). Connections and communications through social media, including recommendations from friends and interactions with strangers or anonymous users, significantly influence people’s beliefs and decision-making processes (Sema, 2013).

On one hand, social media can foster the right to access diverse sources of information, including those provided by fellow citizens and media through various social platforms (Dahl, 2006). On the other hand, it is essential for participants within the digital world to willingly acknowledge the importance of the truth and understand that it is common for public discussions to involve uncertainty, error, and disagreement. Even though seeking truth within digital public discourse is challenging, people should not intentionally misrepresent their beliefs, mislead the public’s perceptions, and carelessly ignore the accuracy of their statements (Cohen, 2009).

Noticeably, health-related concerns took center stage for everyone throughout the COVID-19 pandemic, highlighting a significant shift towards digital mass media and social media serving as the primary means of connectivity (Solanki & Mahajan, 2023). However, the widespread dissemination of misinformation and disinformation on social media platforms can hinder a well-functioning digital public sphere by obstructing access to instructive information necessary for understanding matters of public concern within society. As such, it is important to understand the difference in definition between misinformation and disinformation. Regarding the American Psychological Association (APA), “misinformation refers to false or inaccurate information that is inadvertently spread, while disinformation entails deliberately spreading misleading falsehoods to deceive” (n.d.). Similarly, Britannica defines “Misinformation is the inadvertent spread of false information without intent to harm, while disinformation is false information designed to mislead others and is deliberately spread with the intent to confuse fact and fiction” (Palfrey, 2024). Hence, we conclude that “misinformation” means unintentionally false information, whereas “disinformation” refers to deliberately misleading falsehoods.

In this context, we aim to address a policy issue surrounding the “access” and “truth” elements, focusing on the dissemination of false and misleading information about veganism and meat consumption regarding health and nutrition aspects, which can have profound consequences on public health. For example, false information on social media can lead to confusion among the public regarding health-related issues, hindering informed decision-making about food choices and dietary habits and leading individuals to adopt potentially harmful health behaviors. Additionally, when individuals encounter conflicting information or perceive inconsistencies between official health guidelines and information shared on social media, they may begin to question the credibility and trustworthiness of health authorities.

As such, we would like to select the World Health Organization (WHO) as our target audience for several reasons. Firstly, the WHO is globally recognized as an authority and possesses credibility in matters of public health. Secondly, the WHO’s reach extends to a global scale, enabling it to influence health-related discussions and policies worldwide. Thirdly, the WHO plays a key role in shaping health policies at both national and international levels, making it a crucial stakeholder in addressing misinformation across online platforms. Lastly, the WHO currently provides a channel for reporting misinformation online for various social media platforms via its official website, except Reddit, notably revealing a gap in addressing online misinformation concerning health and nutrition within the Reddit community. By engaging with the WHO, we aim to contribute to efforts aimed at combating the spread of false information and promoting accurate health-related discourse on digital platforms.

## Conclusion
Through detailed explorations, our report reveals the multifaceted issues and implications of misinformation and disinformation about veganism and meat consumption within the Reddit community. There is a variety of concerns and doubts within dietary-related discussions. On one hand, some people may have misconceptions about vegan consumption and the physical effects on children’s growth and individuals’ aging, concerns about the nutritional inadequacy of vegan diets, and perceptions of veganism as an eating disorder. On the other hand, some participants on Reddit ask for scientific evidence to clarify some confusion about dietary-related topics, especially the vegan diet’s safety for newborns. As mentioned, we can see how false information negatively impacts public understanding, public discourse, and dietary choices. These findings underscore the critical need for proactive intervention and effective strategies by health authorities, especially the WHO to counteract misinformation and foster an informed and healthy public dialogue.

The brief highlights the importance of trustworthy information in shaping public discourse and makes practical suggestions to the World Health Organisation (WHO). Key recommendations include direct engagement on Reddit, increased monitoring of disinformation patterns, and the development of focused teaching tools. The WHO is encouraged to build an official Reddit profile, engage in Ask Me Anything (AMA) sessions, and work with organizations such as NewsGuard to successfully battle disinformation. The paper also offers long-term implementations, such as sponsoring programs to combat disinformation and establishing a specific channel for disputing misleading claims with a collection of scientifically reliable research. These initiatives aim to improve the quality of public health discourse and promote informed eating choices.

While these measures are expected to have positive economic, social, and political impacts, challenges such as technical expertise, resource allocation, and resistance from online communities are anticipated. Addressing these challenges will be crucial for the successful implementation of the recommendations.

In conclusion, the policy brief underscores the critical need for robust policy frameworks to address misinformation on digital platforms. By implementing the proposed strategies, the WHO can significantly enhance public health communication, promote accurate dietary information, and improve global health outcomes.

## Reference Lists

American Psychological Association. (n.d.). Misinformation and disinformation. [https://www.apa.org/topics/journalism-facts/misinformation-disinformation](https://www.apa.org/topics/journalism-facts/misinformation-disinformation)

Boston University. (n.d.). Guide to Reddit AMAs. PR Social. [https://www.bu.edu/prsocial/best-practices/social-media/guide-to-reddit-amas/](https://www.bu.edu/prsocial/best-practices/social-media/guide-to-reddit-amas/)

Bryant, C. (2024). Veganuary’s impact has been huge – here are the stats to prove it. The Conversation. [https://theconversation.com/veganuarys-impact-has-been-huge-here-are-the-stats-to-prov
e-it-221062](https://theconversation.com/veganuarys-impact-has-been-huge-here-are-the-stats-to-prove-it-221062)

Carlile, C. (2024). Meat Industry using “misinformation” to block dietary change, report finds. DeSmog. [https://www.desmog.com/2024/03/01/meat-industry-using-misinformation-to-block-dieta
ry-change-report-finds/](https://www.desmog.com/2024/03/01/meat-industry-using-misinformation-to-block-dietary-change-report-finds/)

Carrington, D. (2021). Record 500,000 people pledge to eat only vegan food in January. The Guardian. [https://www.theguardian.com/environment/2021/jan/05/veganuary-record-number-people
-pledge-eat-vegan-food-january](https://www.theguardian.com/environment/2021/jan/05/veganuary-record-number-people-pledge-eat-vegan-food-january)

Carrington, D. (2023). Gigantic power of meat industry blocking green alternatives, study finds. The Guardian. [https://www.theguardian.com/environment/2023/aug/18/gigantic-power-of-meat-industry -blocking-green-alternatives-study-finds](https://www.theguardian.com/environment/2023/aug/18/gigantic-power-of-meat-industry-blocking-green-alternatives-study-finds)

Changing Markets Foundation. (2023). Truth, Lies and Culture Wars – Social listening analysis of meat and dairy persuasion narratives (p. 20). Ripple Research. [https://changingmarkets.org/wp-content/uploads/2024/01/Truth-lies-and-culture-wars-fin al.pdf](https://changingmarkets.org/wp-content/uploads/2024/01/Truth-lies-and-culture-wars-final.pdf)

Chen, S.-C., & Lin, C.-P. (2019). Understanding the effect of social media marketing activities: The mediation of social identification, perceived value, and satisfaction. Technological Forecasting and Social Change, 140, 22-32. [https://doi.org/10.1016/j.techfore.2018.11.025](https://doi.org/10.1016/j.techfore.2018.11.025)

Cohen, J. & Fung, A. (2021). Democracy and the digital public sphere. In L. Bernholz, H. Landemore & R. Reich (Eds.), Digital technology and democratic theory (pp. 23-61). University of Chicago Press. [https://doi.org/10.7208/chicago/9780226748603.003.0002](https://doi.org/10.7208/chicago/9780226748603.003.0002)

Colón, S. (2024). veganism. Encyclopedia Britannica. [https://www.britannica.com/topic/veganism](https://www.britannica.com/topic/veganism)

Dahl, R. (2006). On political equality. Yale University Press. [https://archive.org/details/robert-a.-dahl-on-political-equality-yale-university-press-2006/ page/n25/mode/2up](https://archive.org/details/robert-a.-dahl-on-political-equality-yale-university-press-2006/page/n25/mode/2up)

Dewing, M. (2010). Social Media: An Introduction. Social Affairs Division, Parliamentary Information and Research Service [https://bdp.parl.ca/staticfiles/PublicWebsite/Home/ResearchPublications/InBriefs/PDF/20 10-03-e.pdf](https://bdp.parl.ca/staticfiles/PublicWebsite/Home/ResearchPublications/InBriefs/PDF/2010-03-e.pdf)

East Stratcom Task Force. (2015). Home Page - EUvsDisinfo. https://euvsdisinfo.eu/ Effron, E. (2023). Reports to governments, the EU Commission, and the who. NewsGuard. [https://www.newsguardtech.com/special-reports/who-reports/](https://www.newsguardtech.com/special-reports/who-reports/)

European Commission. (2022). Social Observatory for Disinformation and Social Media Analysis. [https://cordis.europa.eu/project/id/825469](https://cordis.europa.eu/project/id/825469)

Google. (2024). The search interest on vegan, veganism, and plant-based diet from 2014 to 2024. Google Trends. [https://trends.google.com/trends/explore?date=2014-01-01%202024-05-08&q=vegan,%2
Fg%2F11cknh9qp1,%2Fm%2F07_hy](https://trends.google.com/trends/explore?date=2014-01-01%202024-05-08&q=vegan,%2Fg%2F11cknh9qp1,%2Fm%2F07_hy)

Hargreaves, S. M., Rosenfeld, D. L., Moreira, A. V. B., & Zandonadi, R. P. (2023). Plant-based and vegetarian diets: an overview and definition of these dietary patterns. European journal of nutrition, 62(3), 1109–1121. [https://doi.org/10.1007/s00394-023-03086-z](https://doi.org/10.1007/s00394-023-03086-z)

Hartwell, M., Torgerson, T., Essex, R., Campbell, B., Belardo, D., & Vassar, M. (2021). Public Awareness of a Plant-Based Diet Following the Release of “Game Changers” and “What The Health” Documentaries. American journal of lifestyle medicine, 16(2), 190–196. [https://doi.org/10.1177/15598276211044106](https://doi.org/10.1177/15598276211044106)

Harvard T.H. Chan. (2016). U.S. dietary guidelines discussed in Reddit ‘AMA’. School of Public Health. [https://www.hsph.harvard.edu/news/hsph-in-the-news/u-s-dietary-guidelines-discussed-in
-reddit-ama/](https://www.hsph.harvard.edu/news/hsph-in-the-news/u-s-dietary-guidelines-discussed-in-reddit-ama/)

Lippi, G., Mattiuzzi, C., & Cervellin, G. (2016). Meat consumption and cancer risk: a critical review of published meta-analyses. Critical reviews in oncology/hematology, 97, 1–14. [https://doi.org/10.1016/j.critrevonc.2015.11.008](https://doi.org/10.1016/j.critrevonc.2015.11.008)

Netflix. (2017). What the Health [Television series]. Netflix. [https://www.netflix.com/de-en/title/80174177](https://www.netflix.com/de-en/title/80174177)

Netflix. (2018). The Game Changers [Television series]. Netflix. [https://www.netflix.com/de-en/title/81157840](https://www.netflix.com/de-en/title/81157840)

NewsGuard. (2023). AI Red-teaming Interim Report. [https://www.newsguardtech.com/wp-content/uploads/2022/10/FINAL_WHO_Report_October2022.pdf](https://www.newsguardtech.com/wp-content/uploads/2022/10/FINAL_WHO_Report_October2022.pdf)

Palfrey, J. (2024). Misinformation and disinformation. Encyclopedia Britannica. [https://www.britannica.com/topic/misinformation-and-disinformation](https://www.britannica.com/topic/misinformation-and-disinformation)

Tan, R. (2017). The vegetarian spectrum: A glossary of terms. MICHELIN Guide. [https://guide.michelin.com/en/article/features/the-vegetarian-spectrum-a-glossary-of-terms-sg](https://guide.michelin.com/en/article/features/the-vegetarian-spectrum-a-glossary-of-terms-sg)

Reddit. (2016). Italy proposal to jail vegans who impose diet on children. r/nottheonion. [https://www.reddit.com/r/nottheonion/comments/4x3vcp/italy_proposal_to_jail_vegans_ who_impose_diet_on/](https://www.reddit.com/r/nottheonion/comments/4x3vcp/italy_proposal_to_jail_vegans_who_impose_diet_on/)

Reddit. (2016). Science AMA Series: I’m Vasanti Malik, research scientist at the Harvard T.H. Chan School of Public Health. I’m here to answer your questions about Dietary Guidelines in the U.S.; Ask Me Anything!. r/science. [https://www.reddit.com/r/science/comments/4br5g7/science_ama_series_im_vasanti_malik_research/](https://www.reddit.com/r/science/comments/4br5g7/science_ama_series_im_vasanti_malik_research/)

Reddit. (2018). CMV: A diet can include meat and be as environmentally friendly as a vegan diet. r/changemyview. [https://www.reddit.com/r/changemyview/comments/8zxkxc/cmv_a_diet_can_include_meat_and_be_as/](https://www.reddit.com/r/changemyview/comments/8zxkxc/cmv_a_diet_can_include_meat_and_be_as/)

Reddit. (2018). CMV: veganism is both mentally and physically unhealthy. r/changemyview. [https://www.reddit.com/r/changemyview/comments/9a78qw/cmv_veganism_is_both_mentally_and_physically/](https://www.reddit.com/r/changemyview/comments/9a78qw/cmv_veganism_is_both_mentally_and_physically/)

Reddit. (2020). Veganism is an eating disorder. r/AntiVegan. [https://www.reddit.com/r/AntiVegan/comments/ezeckg/veganism_is_an_eating_disorder/](https://www.reddit.com/r/AntiVegan/comments/ezeckg/veganism_is_an_eating_disorder/)

Reddit. (2020). Veganism > malnutrition. r/insanepeoplefacebook. [https://www.reddit.com/r/insanepeoplefacebook/comments/e4rjwc/veganism_malnutrition/](https://www.reddit.com/r/insanepeoplefacebook/comments/e4rjwc/veganism_malnutrition/)

Reddit. (2021). Good Job Italy!. r/AntiVegan. [https://www.reddit.com/r/AntiVegan/comments/penjya/good_job_italy/](https://www.reddit.com/r/AntiVegan/comments/penjya/good_job_italy/)

Reddit. (2021). Red meat is good for you. r/TrueUnpopularOpinion. [https://www.reddit.com/r/TrueUnpopularOpinion/comments/qvsi4b/red_meat_is_good_for_you/](https://www.reddit.com/r/TrueUnpopularOpinion/comments/qvsi4b/red_meat_is_good_for_you/)

Reddit. (2023). Vegan bad. r/terriblefacebookmemes. [https://www.reddit.com/r/terriblefacebookmemes/comments/13222ii/vegan_bad/](https://www.reddit.com/r/terriblefacebookmemes/comments/13222ii/vegan_bad/)

Reddit. (2023). Vegan = bad. r/terriblefacebookmemes. [https://www.reddit.com/r/terriblefacebookmemes/comments/10kgyth/vegan_bad/](https://www.reddit.com/r/terriblefacebookmemes/comments/10kgyth/vegan_bad/)

Reddit. (2023). Veganism is truly unhealthy. r/TrueUnpopularOpinion. [https://www.reddit.com/r/TrueUnpopularOpinion/comments/175kekk/veganism_is_truly_unhealthy/](https://www.reddit.com/r/TrueUnpopularOpinion/comments/175kekk/veganism_is_truly_unhealthy/)

Reddit. (2024). What is an AMA and how do I host one? - reddit help. [https://support.reddithelp.com/hc/en-us/articles/115002427523-What-is-an-AMA-and-how-do-I-host-one](https://support.reddithelp.com/hc/en-us/articles/115002427523-What-is-an-AMA-and-how-do-I-host-one)

Rini, L., Bayudan, S., Faber, I., Schouteten, J. J., Perez-Cueto, F. J. A., Bechtold, K.-B., Gellynck, X., Bom Frøst, M., & De Steur, H. (2024). The role of social media in driving beliefs, attitudes, and intentions of meat reduction towards plant-based meat behavioral intentions. Food Quality and Preference, 113, 1–10. [https://doi.org/10.1016/j.foodqual.2023.105059](https://doi.org/10.1016/j.foodqual.2023.105059)

Sema, P. (2013). Does Social Media Affect Consumer Decision-Making?. MBA Student Scholarship, 24. [https://scholarsarchive.jwu.edu/mba_student/24](https://scholarsarchive.jwu.edu/mba_student/24)

Smithers, R. (2019). Veganuary ends on record high with 250,000 participants. The Guardian. [https://www.theguardian.com/lifeandstyle/2019/jan/31/veganuary-record-high-participants-plant-based](https://www.theguardian.com/lifeandstyle/2019/jan/31/veganuary-record-high-participants-plant-based)

Solanki, S., & Mahajan, P. (2023). Impact of Social Media on Dietary Choices. International Journal of Scientific Research in Science and Technology, 10(3), 879-887. [https://ijsrst.com/home/issue/view/article.php?id=IJSRST523103154](https://ijsrst.com/home/issue/view/article.php?id=IJSRST523103154)

Tuso, P. J., Ismail, M. H., Ha, B. P., & Bartolotto, C. (2013). Nutritional update for physicians: plant-based diets. The Permanente journal, 17(2), 61–66. [https://doi.org/10.7812/TPP/12-085](https://doi.org/10.7812/TPP/12-085)

Vegan Society. (2016). Definition of veganism. [https://www.vegansociety.com/go-vegan/definition-veganism](https://www.vegansociety.com/go-vegan/definition-veganism)

World Health Organization. (n.d.). Home page [Facebook channel]. Facebook. [https://www.facebook.com/WHO](https://www.facebook.com/WHO)

World Health Organization. (n.d.). Home page [Instagram channel]. Instagram. [https://www.instagram.com/who/](https://www.instagram.com/who/)

World Health Organization. (n.d.). Home page [LinkedIn channel]. LinkedIn. [https://www.linkedin.com/company/world-health-organization/](https://www.linkedin.com/company/world-health-organization/)

World Health Organization. (n.d.). Home page [SnapChat channel]. SnapChat. [https://www.snapchat.com/add/who](https://www.snapchat.com/add/who)

World Health Organization. (n.d.). Home page [TikTok channel]. TikTok. [https://www.tiktok.com/@who?lang=en](https://www.tiktok.com/@who?lang=en)

World Health Organization. (n.d.). Home page [X channel]. X. [https://twitter.com/intent/follow?source=followbutton&variant=1.0&screen_name=who](https://twitter.com/intent/follow?source=followbutton&variant=1.0&screen_name=who)

World Health Organization. (n.d.). Home page [YouTube channel]. YouTube. [https://www.youtube.com/user/who](https://www.youtube.com/user/who)

World Health Organization. (n.d.). FAO/WHO nutrient requirements for children aged 0–4 years. [https://www.who.int/groups/fao-who-nutrient-requirements-for-children-aged-0-36-months](https://www.who.int/groups/fao-who-nutrient-requirements-for-children-aged-0-36-months)

Wrona, A. (2024). The internet seems to think Italy outlawed veganism for kids. here’s what we found. Yahoo! Style. [https://uk.news.yahoo.com/style/internet-seems-think-italy-outlawed-190000648.html?guccounter=1&guce_referrer=aHR0cHM6Ly93d3cuZ29vZ2xlLmNvbS8&guce_referrer_sig=AQAAAIXv6n-AMXDBlrBITCEiAL1eDbPvnJgoA_HRH158wQaf9Lm5JEl4XsROEjbBx-GlbJn_apUdWM927asSKe6yWco0EGEwULB-Hf3Y-3TSMBLpT_MhjhXd8DacBAuRHzxiZwv_tgMshHA2lo3vV-RCXIS2Db-w4LGBA5XwGMzXrcM2](https://uk.news.yahoo.com/style/internet-seems-think-italy-outlawed-190000648.html?guccounter=1&guce_referrer=aHR0cHM6Ly93d3cuZ29vZ2xlLmNvbS8&guce_referrer_sig=AQAAAIXv6n-AMXDBlrBITCEiAL1eDbPvnJgoA_HRH158wQaf9Lm5JEl4XsROEjbBx-GlbJn_apUdWM927asSKe6yWco0EGEwULB-Hf3Y-3TSMBLpT_MhjhXd8DacBAuRHzxiZwv_tgMshHA2lo3vV-RCXIS2Db-w4LGBA5XwGMzXrcM2)

Ye, T. (2023). Social Media and Its Impact: Individuals and Society. Journal of Education, Humanities and Social Sciences, 8, 642-646. [https://www.researchgate.net/publication/368375556_Social_Media_and_Its_Impact_Ind ividuals_and_Society](https://www.researchgate.net/publication/368375556_Social_Media_and_Its_Impact_Individuals_and_Society)
