# **NYC Citibike Analysis: A Tableau Project**
## **Overview**
### *Purpose of the analysis*
The purpose of this analysis was to review the data concerning the utilization of the Citibike service in New York City, in order to determine if this kind of business would be in demand in Des Moines, Iowa. The data analyzed corresponds to the month of August 2019, when bike utilization tends to be higher due to the warm weather in the city. Thus, we extracted and transformed the data through Python and Jupyter Notebook, and then loaded it into Tableau in order to create visualizations that would help us understand and present the data in a clean and concise manner. 

For this analysis, we used the following tools:
1. Python
2. Jupyter Notebook
3. The Pandas library
4. Tableau

## **Results**
### *What did we discover?*
In order to analyze the NYC Citibike data, and after cleaning the corresponding CSV file, we loaded the data into Tableau and created a series of visualizations. These visualizations cover different aspects of the Citibike service, such as the age, type and gender of users. In the following paragraphs you can find a brief analysis of what we discovered. However, if you want to look at the visualizations into more detail, you can click on the following link: [Dashboard Link.](https://public.tableau.com/views/NYCCitibikeAnalysis_16754015895630/NYCCitibikeAnalysis?:language=en-US&:display_count=n&:origin=viz_share_link)

### 1. Average Trip Duration by Age
![Trip_Duration_by_Birth_Year](https://user-images.githubusercontent.com/113153777/216846897-57311526-f98c-4c75-8815-a834a22a35fc.png)

The first visualization we included looks into the average trip duration by age. As we can clearly see in this chart, average trip duration seems to go up the younger users are. This can be due to the physical abilities of younger users, who probably have more stamina. However, it should be noted that users born in 1970 are even more avid users or the service. This could be due to the context they grew up in, as during the 70s it was very common for people to own bikes. 
### 2. Bike Utilization
![Bike_Utilization](https://user-images.githubusercontent.com/113153777/216846927-7ea9eba3-1a00-4d3b-aad1-5c13ca69f2dc.png)

The second visualization reviews bike utilization. This means that we looked at the amount of bikes that are utilized the most, taking into account the Trip Duration and their Bike ID. Then, we classified the bikes according to the Trip Duration in the following manner:
1. High: Bikes with more than 1.000.000 hours of utilization.
2. Medium: Bikes with less than 1.000.000 and more than 500.000 hours of utilization.
3. Low: Bikes with less than 500.000 hours of utilization.

We discovered, thus, that most bikes are utilized for less than 500.000 hours a month, with only a few being used for more than 500.000 or 1.000.000 hours. 

### 3. Checkout Times for Users
![Checkout_Times_Users](https://user-images.githubusercontent.com/113153777/216846969-da91d662-2175-4be7-b508-4b09a94a319a.png)

This graph examines the amount of time users checkout bikes. As we can clearly see, most bikes are used for a range of 1 to 25 minutes, with 5 minutes being the usual trip duration. This could give us some information on our user's habits, meaning that they probably use the bikes for short distances, and as a means of transportation instead of leisure. 

### 4. Checkout Times by Gender
![Checkout_Times_Gender](https://user-images.githubusercontent.com/113153777/216847010-82187223-f78a-4fe6-b71b-d996a5b0751b.png)

This graph looks into the information of the third visualization into more detail, giving us some insight on the utilization patterns by gender. As we can see, although the pattern seems to be similar for every gender, most of the users seem to be male. 

### 5. Trips by Weekday
![Trips_by_Weekday](https://user-images.githubusercontent.com/113153777/216847040-70b218ea-1404-4cc9-9b78-1028dfc5022e.png)

This visualization examines the utilization patterns depending on the hours of the day, as well as the weekday. This heatmap lets us know that the heaviest use hours, from Monday to Friday, correspond to the hours in which people get in and out of work. During the weekend, users seem to prefer the period between 9 am and 7 pm, as well as Saturday. 

### 6. Trips by Gender (Weekday per Hour)
![Trips_by_Gender](https://user-images.githubusercontent.com/113153777/216847069-e0f2e2c3-41eb-4a95-aba4-2985d38c7115.png)

This graph examines the same data as the Trips by Weekday visualization, with an added component of Gender. The use pattern is very similar to what we explained for the previous visualization. However, we can clearly see here that it is male users who use the service more. This could mean that female users prefer other types of transport, like buses or private transport. 

### 7. User Trips by Gender
![User_Trips_by_Gender](https://user-images.githubusercontent.com/113153777/216847084-c7258b02-c0f8-449c-91ab-59a31ac98326.png)

The last visualization looks into the Types of Users, by Gender and Weekday. As it turns out, female and male users who rely more on the service also tend to be Suscribers. However, the opposite is true for users of Unknown gender, who seem to be one-time customers. Again, this graph also shows that males are the main users of the service. 

## **Summary**
This analysis provided many clues regarding the Citibike service in NYC which will, hopefully, allow us to determine if this type of business would be succesful for Des Moines, Iowa. Through the data, we learned that the service could be more attractive for users who are:
* Male
* Young
* Office workers 
* People who might not have cars and use bikes as a means of transportation for short distances
### *Additional recommendations*
Although the information that we gathered provides various elements that can help us characterize the use habits of Citibike users in NYC, some additional visualizations might be needed in order to get a comprehensive analysis for Des Moines. In particular, the focus could be on the use habits of female users, who seem to use the service less than male users. For this, two visualizations could be performed: 
1. A visualization that examines the Year of Birth and Trip Duration for female users. This visualization would be similar to the first one in this report, however, the added component of gender would help us examine if age plays a part in the habits of female users.
2. A visualization that examines the Start Station Coordinates for female users. This way, we could examine the start stations that are more popular for female users, and try to determine if geography has a role in their habits. For this, we would also need the Start Station Name and ID. 
