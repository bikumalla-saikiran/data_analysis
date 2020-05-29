# Communicate data findings with Ford gobike system data
## by Saikiran Bikumalla



## Dataset

> Ford GoBike is the Bay Area's bike share system. Bay Area Bike Share was introduced in 2013 as a pilot program for the region, with 700 bikes and 70 stations across San Francisco and San Jose. Once expansion is complete, Ford GoBike will grow to 7,000 bikes across San Francisco, the East Bay and San Jose. Ford GoBike, like other bike share systems, consists of a fleet of specially designed, sturdy and durable bikes that are locked into a network of docking stations throughout the city. The bikes can be unlocked from one station and returned to any other station in the system, making them ideal for one-way trips. People use bike share to commute to work or school, run errands, get to appointments or social engagements and more. It's a fun, convenient and affordable way to get around.The bikes are available for use 24 hours/day, 7 days/week, 365 days/year and riders have access to all bikes in the network when they become a member or purchase a pass.

> I chose Ford GoBike System Data : [Fordgobike](https://www.fordgobike.com/system-data) as my source data 
1. This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.
2. Multiple data files will need to be joined together if a full year’s coverage is desired.
3. The features included in the dataset : 
Trip Duration (seconds) , Start Time and Date , End Time and Date , Start Station ID , Start Station Name , Start Station Latitude , Start Station Longitude , End Station ID , End Station Name, End Station Latitude , End Station Longitude , Bike ID , User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual) , Member Year of Birth, Member Gender

## Summary of Findings

> There are two types of clients using the system: Subscribers and Customers. Subscribers are primarily daily commuters, having short trips to and from work, who rent a bike on weekdays at 8-9am and 5-6pm. Customers are usually tourists or occassional riders who use the system mainly on weekends to explore the Bay Area. I tried to find out what are the key factors affect trip duration. It turns out that Weather does not have a big effect on the trip duration but user type does have an impact on trip duration. According the analysis, I found subscribers tend to rend the bikes for longer trips. 

> The efficient/short period of usage for subscribers corresponds to their high concentration on rush hours(8-9am and 5-6pm) Monday through Friday, indicating the use is primarily for work commute. The more flexible and relaxing pattern of customer usage shows that they're taking advantage of the bike sharing system differently from the subscribers, heavily over weekends for city tour or leisure purpose probably. 


## Key Insights for Presentation

> Different usage pattern/habit between the two type of riders are seen from the exploration. Subscribers use the system heavily on work days i.e. Monday through Friday whereas customers ride a lot on weekends, especially in the afternoon. Many trips concentrated around 8-9am and 17-18pm on work days for subscribers, yet customers tend to use more in the late afternoon around 17pm Monday to Friday. The efficient/short period of usage for subscribers corresponds to their high concentration on rush hours Monday through Friday, indicating the use is primarily for work commute. The more relaxing and flexible pattern of customer use shows that they're taking advantage of the bike sharing system quite differently from the subscribers, heavily over weekends and in the afternoon, for city tour or leisure purpose probably.
