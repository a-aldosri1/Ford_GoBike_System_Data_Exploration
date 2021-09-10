# Ford GoBike System Data Exploration
## by Abdullah Majed


## Dataset

includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area, it consist of 183412 row, the features include duration, user type, gender, date of birth..etc, unfourtnetly the website of orginal data is shutdown when i did this analysis you can check other systems data from this [page](https://github.com/BetaNYC/Bike-Share-Data-Best-Practices/wiki/Bike-Share-Data-Systems).



## Summary of Findings

i found that overall average trip take between 500 and 650. sec, in general most rides come in week weekday rather than weekend, Thursday has the most rides almost 35000, most rides happen in `8 AM` and `6 PM` they excede 20000 rides, most of our rides from people between 25 and 40, most of the users are subscribers, only `9%` are customers, most of the users are males, only `23%` are females, and `2%` other,  people spend more time riding the bike when they start between `11 AM` and `4 PM`, and the lowest duration average when they start around `6 AM`, people between 45 and 63 age spend more time riding bikes, people spend more time riding bikes on weekends, On average Customers spend `250 sec` more than subscribers, Customers perfer to ride on weekends more than Subscribers, Customers from 48 to 60 has the highest durtion average, Customers really love riding more between `10 AM` and `4 PM` with duration average between `1000 sec` and `1300 sec`, old males really like to ride at `4 AM`, Female Customers have the highest duration average with `1057 sec`, male subscribers have the lowest with `581 sec`



## Key Insights for Presentation

For the presentation, I will start by the overall duration distribution, age distribution, day of week distribution, hour of day distribution, then i will show the relation between duration and days and hours, then i will display duration vs age.

Afterwards, I introduce each of the categorical variables one by one. To start,
i will show duration vs user_type, i will focus on user_type because it affect duration pretty well.
