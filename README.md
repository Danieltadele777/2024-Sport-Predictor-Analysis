# 2024 Sport Predictor Analysis
Sports Predictor is a free feature offered to GemBet users during the Euro2024 and Copa America football competitions. Users could place predictions on specific games, earning full points for guessing the exact score and a lower amount of points for correctly predicting the outcome (winner or draw). Most rounds featured 6 events.

I conducted an in-depth analysis of **Euro2024 eGamers**, encompassing data from 11 rounds. This analysis included over 50,000 players and examined their predictions, points earned, accuracy of predictions, points by match or event, player type, and overall performance.

## Used KPIs
**User Behavior Analysis**: Analyzed engagement trends by examining predictions and changes over time. Investigated how engagement varied with each round, including the number of users participating in each round, and tracked drop-off rates over time.

**Customer Retention Rate**: Measured by the number of players consistently participating across multiple rounds.

**Customer Churn Rate**: Determined by the number of players who stopped participating over time.

**Prediction Accuracy**: Analyzed the distribution of points to assess prediction accuracy, including how often users predicted correctly.

**Top Players and Categories (High-Value Player KPIs)**: Top 5 Players: Identified the top 5 players based on points accumulated throughout the competition.

**High-Revenue Generating Players**: Categorized players to identify those who generated the most points and revenue, focusing on their activity and frequency of participation.

**Customer Preferences (Preferred Currency)**: Analyzed the preferred currency used by players to understand customer preferences.

**Customer Behavior and Drop-Off KPIs**: Player Participation by Event: Assessed the number of players participating in each event to understand customer behavior.

**Player Analysis by Time**: Conducted analysis by year, quarter, and month to track the drop-off rate of players and identify new players over time.

## Table of contents
 - [Project Overview](#project-overview)
 - [Data Source](#data-source)
 - [Tools Used](#tools-used)
 - [Data cleaning](#data-cleaning)
 - [Exploratory data analysis](#exploratory-data-analysis)
 - [Hypothesis Testing](#hypothesis-testing)
 - [Data Analysis](#data-analysis)
 - [Findings](#findings)
 - [Power BI Visualization](#power-bi-visualization)
 - [Recommendations](#recommendations)
 - [Limitations](#limitations)
 - [References](#references)
 - [Presentation Video](#presentation-video)

### [Project Overview]()
This project analyzes player behavior and prediction accuracy in GemBet's Sports Predictor during the Euro2024 football competition. Using data from 11 rounds and over 50,000 players, the study examines user engagement trends, prediction accuracy, and player preferences.

Key insights include:

- User Engagement: Trends in player participation, retention, and churn across rounds.
- Prediction Accuracy: Assessment of how often users correctly predicted match outcomes.
- Top Players: Identification of top-performing players and their impact on revenue.
- Customer Preferences: Analysis of preferred currencies among players.
- Event Participation: Understanding player behavior and drop-off rates by event.

These insights are aimed at enhancing user engagement and optimizing future features.

### [Data Source]()
The dataset is obtained from the EURO2024 Analysis task report.

### [Tools Used]()
- Excel: For initial data exploration and summary statistics
- Google BigQuery: Primary data cleaning
- SQL: For data cleaning and transformation
- Panda: For data cleaning, inspection and analysis
- Power BI: Visualization, DAX, measures

### [Data cleaning]()
To clean the data I performed the following tasks:
- Reading the SCHEMA, data dictionary and understanding the details of the data
- Handling null values and understanding the columns
- Handling missing values and duplicates
- Data cleaning, formatting, and also dates and numbers adjustment

 ### [Exploratory Data analysis]()
In this analysis, I explored key questions to understand player behavior and prediction accuracy during the Euro2024 competition:

1. How did player engagement change across rounds? 
2. What was the average prediction accuracy? 
3. Who were the top players, and what set them apart? 
4. What were the preferred currencies, and did they influence behavior? 
5. How did participation vary by event and round? 
6. What were the trends in player retention and churn? 
7. Did player behavior change by time of year or specific events? 

### [Hypothesis Testing]()
- Engagement dropped in later rounds, with higher retention in the early stages
- Prediction accuracy was moderate, with most points earned by predicting outcomes rather than exact scores
- The top 5 players participated in nearly every round and had above-average prediction accuracy
- Certain currencies were preferred, correlating with higher engagement and accuracy
- Participation was highest in early rounds and high-profile events, declining in less prominent ones.
- Players who scored early or participated frequently were more likely to be retained.
- Seasonal spikes in engagement were observed around major football events

### [Data Analysis]()
For data analysis and cleaning I used SQL. 

### [Findings]()
- Player Engagement: Player participation was almost consistent during the competition. High-profile events and popular teams drove the most engagement.

- Prediction Accuracy: Most players struggled to predict exact scores, with only a small percentage consistently accurate. However, many players were able to correctly predict outcomes (win/loss/draw), leading to moderate point accumulation.

- Top Players: The top 5 players distinguished themselves by their frequent participation and higher accuracy. These players significantly influenced the overall points distribution.

- Currency Preferences: Certain currencies were preferred by players, with these preferences linked to higher engagement and better prediction performance, indicating potential regional or demographic trends.

- Retention and Churn: Retention was strongest among players who performed well early or who participated consistently. Players who failed to score early or participated irregularly showed higher churn rates.

- Event-Specific Behavior: Participation and accuracy were higher during major events, with noticeable drops during less significant matches, suggesting that the prominence of events influences player behavior.

- Seasonal Trends: There were seasonal spikes in player activity, particularly around major football events, indicating that timing can significantly impact player engagement.

### [Power BI Visualization]()
<img width="1468" alt="1" src="https://github.com/user-attachments/assets/ae1697d0-fcc8-4fdd-a363-88c9557802cc">
<img width="1470" alt="2" src="https://github.com/user-attachments/assets/f0b26804-93eb-4bb0-9172-0b1d2183a60f">
<img width="1470" alt="3" src="https://github.com/user-attachments/assets/ccca07ed-61ae-4511-be55-d860494dba35">
<img width="1469" alt="4" src="https://github.com/user-attachments/assets/8162ffbf-fa83-41ec-80c4-aebf371c984e">


### [Recommendations]()
Based on the analysis I recommended the following actions:
1. High revenue generated category: From the four categories Casino registered the highest number of players: 1,853 or 64% of the overall number of players.
2. High revenue generated type:  It is noted that the highest number of players came from the 'Regular' player category (81.25%).
3. Customer preferences: Players used 3 types of currencies. SGD or the Singapore dollar used 93.37%! SGD is the preferred method of currency by players. Unfortunately, the USD was used only once but did not generate any points.
4. Customer retention rate:  7,020 players attended all the events. This means that 13.45% of the players attended all events compared to the total player base!

Based on the findings from the analysis, the following recommendations are proposed:

- Enhance Early Round Engagement: Introduce incentives or promotions in early rounds to maintain high engagement as the competition progresses. Engagement drops in later rounds, so maintaining momentum early on could reduce churn.
- Improve Prediction Accuracy Support: Provide tips, stats, or insights before matches to help players make more accurate predictions. Since most players struggled with exact score predictions, offering support could increase satisfaction and engagement.
- Leverage Top Players: Create leaderboards or special rewards for top-performing players to recognize and motivate them. Highlighting and rewarding top players could enhance retention and attract more participants aiming to reach the top.
- Optimize Currency Options: Tailor promotions and offers based on the preferred currencies identified in the analysis. Understanding currency preferences can lead to more personalized and effective marketing strategies, driving higher engagement.
- Focus on High-Profile Events: Promote and focus resources on high-profile matches and events to maximize participation and engagement. Participation spikes during major events, so leveraging these moments can boost overall engagement.
- Monitor and Reduce Churn: Implement targeted retention strategies for players who show signs of dropping off, such as personalized offers or reminders. Reducing churn, especially among those who fail to score early, could improve overall participation and retention rates.
- Capitalize on Seasonal Trends: Plan marketing campaigns around major football events and seasons to capitalize on increased player activity. Seasonal spikes in engagement suggest that timing marketing efforts can lead to better player acquisition and retention.

### [Limitations]()
While the analysis provided valuable insights, a few limitations should be noted:
- Prediction Data Granularity: The data did not include detailed information on how players made their predictions (e.g., based on specific insights or randomly), which could have provided a deeper understanding of prediction behavior.
Impact: This lack of granularity may have affected the ability to fully assess prediction accuracy.

- Behavioral Insights: The analysis primarily focused on quantitative data, with limited insight into the qualitative reasons behind player behavior (e.g., why certain players dropped off).
Impact: Understanding the "why" behind certain trends could have led to more targeted recommendations.

- Currency Preference Analysis: The currency preference analysis was based on the available data, which might not fully reflect the entire player base or account for currency fluctuations.
Impact: This may limit the accuracy of conclusions regarding player preferences.

- External Factors: External factors such as marketing campaigns, match timings, or competitor activities were not accounted for in the analysis.
Impact: These factors could have influenced player engagement and behavior, potentially confounding the results.

- Seasonal Trends: The analysis of seasonal trends was limited to the available time frame, which might not fully capture longer-term patterns.
Impact: Insights into seasonal spikes might be incomplete, affecting recommendations related to timing strategies.

### [References]()
No reference materials were used in this analysis

### [Presentation Video]()
[Watch my presentation video for this analysis](https://drive.google.com) to see the detailed analysis and insights!


