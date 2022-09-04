# Ford GoBike System Data
## *by Chisom Maduka*

## Introduction

Ford GoBike is a regional public bicycle sharing system covering the greater part of San Francisco Bay area, and represents the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States.

In this project, data visulization will be performed by using univariate, bivariate, and multivariate plots to explore and gather more information about individual Ford GoBike user behaviours and preferences by studying trends, changes and differences in the month of February 2019.

## Dataset

I extracted the Ford GoBike dataset for February, 2019 containing the following parameters: Trip Duration (seconds), Start Time, End Time, Start Station ID, Start Station Name, Start Station Latitude, Start Station Longitude, End Station ID, End Station Name, End Station Latitude, End Station Longitude, Bike ID, User Type (Subscriber or Customer), Member Birth Year, Member Gender and Bike Share for all Trip.

After series of data assessment, basic data cleaning was performed to produce an error free data needed for analysis. This included dropping redundant columns and creating new ones from some old columns, as well as changing their datatypes. Out of the 183412 original entries, there was 174760 entries left, and the resulting features which I focused on during investigation was:

duration_sec 
start_station_name 
bike_id 
user_type 
member_gender 
age 
start_hour 
duration_min 
duration_hour 
day_of_week 
week_type

## Summary of Findings
During the course of explorating the Ford GoBike dataset, some meaningful insights were uncovered:

Overall, there were about 174,760 data entries, in which over 100,000 biked between 3 to 15 mins duration. Many of these trips happened during peak hours in the mornings and evenings between 7 to 9am and 4 to 6pm respectively. Furthermore, we had 90.5% of the total population being subscribers, who are registered members of the biking system and just 9.5% being cusomers or visitors that are not regular users. 83.5% Weekdays (Monday to Friday) happened to have more sales than 16.5% weekends (Saturday and Sunday), with Thursday toppinng the list of frequent users. I classified users ages into 3 groups namely: young adults (18-40years), older adults (40-70years) and seniors (above 70years) and statistical age distribution showed that 79% were young adults, who happen to be the most frequent users. The older adults were about 21% and although some senior groups travelled, their population was significantly low and negligible.

Further investigation proved that the older the age, the less rides and shorter distance was observed and subscribers had the highest population across all age brackets. Over 80% of subscribers travelled every hour of the day at shorter time compared to customers, who travelled withing a longer period of time. The younger ones happened to travel longer, generating more revenue than the older ones. Hence they can be considered as the target audience, and these are between ages 18 to 45 years (young adults).

## Key Insights for Presentation

The trend in user behavior remained consistent everyday of the week, as many users were recorded to have travelled during peak hours between 7-9am and 4-6pm. This may be explained by the period when people go to work and at the time of return back home. The trend spreaded quite evenly between 10am and 3pm, which indicated working period for many and so, not as much commuters were recorded. Also subscribers having a larger population (90.5%) were significantly more than the customers every hour of the day, including on weekends but more than twice lesser than on weekdays. This can be explained by the busy and working practices that propels many to consistently bike to various locations at the same or different time from Mondays all through Fridays. But on Saturdays and Sundays, quite a number of users probably rest or reduce their movements, resulting in lower out turn. Lastly, young adults (between 18-40yyears) accounting for 0ver 70% of the population are considered the target market since statistics showed that they travel more often and at longer time, which signifies more revenue generated.