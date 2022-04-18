# bikesharing
## Overview of the analysis
### Purpose
  - Create analysis for the bike-sharing program to show the investors there is enough demands in Des Moines to implement the business
### Results
#### For the checkout time graph
 
  ![Screen Shot 2022-04-13 at 11 09 47 AM](https://user-images.githubusercontent.com/63434761/163244427-778d9c65-7ba7-4ce4-af20-f350cb9517ef.png)
  
  - First glance of this graph, the peak tripduration is 5 minutes (about 146,752 bikes) and the usages of bikes significantly go down after 5 mintues
  - The graph also shows the usages of bikes after 60th minute are consistanly low

#### For the checkout time with genders graph

  ![Screen Shot 2022-04-13 at 11 10 15 AM](https://user-images.githubusercontent.com/63434761/163247268-06ca25e3-24b4-42d1-884d-ec401b5beaa2.png)

  - The amount of males using the service is almost triple compares to female usage for 5 minutes tripduration (33,041 for female and 108,087 for male)
  - After 50th minute, the amount of male and female using the bike service are relatively same

#### Trips by Weekday per hour

  ![Screen Shot 2022-04-13 at 11 10 33 AM](https://user-images.githubusercontent.com/63434761/163248870-ecb1e2d4-79f9-46ee-8c31-e69733aa7270.png)
  
  - Looking at this heatmap, we can see there are few notable timestamp where users use the service the most
    + During weekday, the service is heavily used around 7 AM - 8 AM and 5 PM - 6 PM
    + During weekend, the most busy windown timeframe is from 11 AM - 3 PM

#### Trip by Gender(Weekday per hour) 

  ![Screen Shot 2022-04-13 at 11 11 03 AM](https://user-images.githubusercontent.com/63434761/163249744-bfedaccb-a820-4c70-ba6a-a939a0e2c581.png)
  
  - The heatmap shows more details how both genders use the service with different hour. However, both use the bike in relatively same time
  - The only difference of these 2 genders is higher amount of males' usage

#### User trips by gender by weekday

  ![Screen Shot 2022-04-13 at 11 11 18 AM](https://user-images.githubusercontent.com/63434761/163251961-75faa732-6878-4fea-a8e8-5a7deec898b9.png)
  
  - We have a bit more ingsights of different users who use the service
    + Customer: they predominant use the bike on the weekend and hardly use this during weekday
    + Subcribers: they mainly use the bike on the weekday
 
 ### Summary
  
  - Looking at the charts, we can see that there are 2 types of bike users with different purposes
    + For customers, their main purpose to use the bike seems to be roaming around the city on their free time hence the busiest time for them around 11 AM - 3 PM during the weekend
    + For subsribers, they use the bike mainly during the weekday around 8 AM and 6 PM. Hence, they mostly use the bike to get to work maybe because of the rush hour
  - Base on the analysis, we can also conclude that male users are the main customers
  Recommendation: Since we know that man use the service heavily, we should run more graphs and heatmap to know more insights
  
  [Link to dashboard](https://public.tableau.com/app/profile/khanh.nguyen7504/viz/Updatedtableau/AnalysisStory?publish=yes)
