# bikesharing
## Project Overview
Use Tableau to do analysis of NYC CitiBike sharing data from August 2019. We will need to provide the data shows the number of customer types, use length of time etc. for CitiBike company for further decision making. The major question as follow: 

- Who uses bikesharing programs often? (Age/Gender/Usertype)
- What area customers use the bikesharing program the most? 
- When is the most and the least time of day are bikesharing used? 
- How many bikes are used in this bikesharing program? 

## Results

Please refer to this link for detail story of the analysis. [link to dashboard](https://public.tableau.com/app/profile/yawen.liang/viz/Citibike_Challenge_16488752773330/NYCCitiBikeAnalysis "link to dashboard")


1. We can see the customer breakdown by the follow graph. From August 2019, we have 2,344,224 trips in total. There are two types of customers: we have subscribers and general customers. The graph also shown the bikesharing usage by gender. 

![Customer Breakdown](https://user-images.githubusercontent.com/94089680/161397908-13beed91-d69a-4ba4-983b-7c7504c979ae.png)

2. We can see the top starting location is lower Manhattan area. It indicated that as a tourists and business center. We have more customers would use bike sharing programs in this location. 

<img width="1384" alt="Top Start Location" src="https://user-images.githubusercontent.com/94089680/161397917-9aeb0901-b4aa-4bd8-bf31-9128d1b61eb3.png">

3. Based on the graph shown below, the best time to repair and maintenance for CitiBikes is from 2AM to 5AM. That's the peak time where the least amount of customers would use CitiBikes.

<img width="1384" alt="Bike Repairing Time" src="https://user-images.githubusercontent.com/94089680/161398073-564b605e-0f7c-4548-b5fc-3fe4d3180ae7.png">


4. As the graph shown below, we can identify by the bike ID to determine which CitiBikes need repair frequently. There are high usage bikes need to repair frequently and the lower usage bikes needs consistant maintenace.  

![Bikeid usage](https://user-images.githubusercontent.com/94089680/161398680-93b0ba7b-bd63-4756-bd5f-7fd14fc8bdc4.png)

5. We find out that the duration of bike usage time is between 0 to 20 minutes. In other words, it points out the customers are using CitiBikes with short trips. Referring to the previous "Top Start Location" graph. Customers are using CitiBikes mostly in lower Manhattan area. With the same usage, male customers are significantly higher than other users. 

![Top Duration](https://user-images.githubusercontent.com/94089680/161398782-ee8d1f96-898d-4265-bdf2-86decc2113b3.png)

6. The bikesharing high usage time is peak hours (7AM to 9AM & 5PM to 7PM) during weekdays. It seems like besides tourists, customers are most likely to use CitiBikes commute to work. 

<img width="544" alt="Number of Trips Weekday per Hour" src="https://user-images.githubusercontent.com/94089680/161398959-7ed5e32b-5fee-4b79-a678-6a61a199c0b4.png">

7. Eventhough majority of customers are using CitiBikes commute to work, male customers usage are significantly higher than female customers. Not only the peak hours usage, but the usage in general are higher amoung male customers. 

<img width="1367" alt="Number of Trips by Gender" src="https://user-images.githubusercontent.com/94089680/161399238-56539996-1ccb-4462-a3f4-e4305800bffe.png">

8. Lastly, CitiBikes users are mostly subscribers. Within the subscribers, male subcribers are 2 times more than female or other subscribers. 

<img width="421" alt="Customer types" src="https://user-images.githubusercontent.com/94089680/161399379-ea45f81f-30a6-401c-94cc-4d3b57569c95.png">

## Summary
In conclusion, bikeshare services are popular in metropolitan areas, where the resident density is high and parking spaces are limited. The user base mostly of male subscribers, providing regular income to the program. The company should consider doingm marketing to promote the bikesharing program to attract female riders. In addition, male users could be a reliable market. The main usage focused on the working hour commute times.

In order to pursue additional analysis and visualization, I would explore:

- Trips starting and ending locations during the rush hour time-windows. To visualized the flow of traffic between neighborhoods at peak hours;
- Beside the weekday trips, we should perform further analysis about the weekend bike usage. Simply analyze where will customer use bikes during the weekend. To understand if tourist will have a longer average duration when using the bikes compare to the regular subscribers. 