# Bike Sharing Analysis

## Overview of Analysis

### Purpose of Analysis
The intent of this analysis is to support presentations to potential investors in a bikesharing program in Des Moines. The focus of the presentation is on analysis of data from a current bike sharing service in New York City.

### Approach
To conduct this analysis, we used a database from August 2019 for the NYC Citi Bike program and analyzed the data to understand ridership in that program. To ensure the data was usable, it was reformatted to ensure the correct data types were available. Then Tableau Public was used to 

## Results
### Key Findings
After reviewing a series of data images for the NYC Citi Bike program, , the following observations were made.

- NYC Citi Bike provides services in 4 of the 5 bouroughs in NYC. The majority of checkouts originate in Manhattan.
![name](https://github.com/jessica1258/bikesharing/blob/main/Trips%20by%20Origin.png)
- Although they contribute fewer trips, trips for Female customers follow a similar pattern as Male customers. The most common checkout duration is 5 minutes for Males and 6 minutes for Females.
![name](https://github.com/jessica1258/bikesharing/blob/main/Checkout%20Time%20by%20Gender.png)
- In aggregate, the checkout pattern for all customers is driven by the high number of checkouts by subscribers and follows a similar trend. The most common checkout time is 5 minutes.
![name](https://github.com/jessica1258/bikesharing/blob/main/Checkout%20Time%20for%20User.png)
- Both Male and Female customers show a similar pattern of Weekday use.
![name](https://github.com/jessica1258/bikesharing/blob/main/Trips%20by%20Gender%20(Weekday%20per%20Hour).png)
- High utilization times tend to correspond to weekday commutes with the highest number of trips falling between 7am and 9am and 5pm and 7pm on weekdays. Wednesday and Thursday evening tend to see lower and higher usage, respectively than other weeknights.
![name](https://github.com/jessica1258/bikesharing/blob/main/Trips%20by%20Weekday%20per%20Hour.png)
- The impact of the User type can more clearly be seen using a bar chart. Customers who are not Subscribers show higher use on weekends rather than weekdays in contrast to commute driven behavior of Subscribers.
![name](https://github.com/jessica1258/bikesharing/blob/main/User%20Trips%20Weekday.png)
- A summary of this trend at a higher level show a subltle difference in weekend versus weekday use by gender and subscriber.
![name](https://github.com/jessica1258/bikesharing/blob/main/User%20Trips%20by%20Gender%20by%20Weekday.png)
 

### Summary Statistics
The full summary of findings can be found in the following storyboard.

![NYC Citi Bike Checkouts]([https://github.com/jessica1258/bikesharing/blob/main/User%20Trips%20by%20Gender%20by%20Weekday.png](https://public.tableau.com/app/profile/jessica6277/viz/CitiBikeChallenge_16756621327310/NYCCitiBikeCheckouts?publish=yes))

## Summary
### Overall Findings
Based on the high level analysis, the majority of bike trips are those by users wtih subscriptions. Those Subscribers are majority Male and primarily use bikes to commute short distances during the week. There is a second group of users who have higher usage on weekends and are less connected to commute patters and checkout bikes for longer durations. 

### Opportunities for Further Analysis
Further analysis can be conducted in two areas that will be critical for investment decisions.  
- First, population and commuting comparisons should be done between NYC and Des Moines in order to adjust potential trend to account for different patterns in exhisting behavior.
- Second, origin and destination analysis should be conducted to understand other behavioral patterns 
