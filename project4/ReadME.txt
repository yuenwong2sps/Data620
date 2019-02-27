2015 Flight Delays and Cancellations

Team: Fireflies
Members: Chunhui Zhu, John Wong and Chunmei Zhu
Date: 2/25/2019
Abstract

For each node we are going to us one airport (like JFK) as centrality, and we are going to discover the number of the flights arrives (positive) and number of flights depart (negative). We try to discover when get the most flight business. And we will try to evaluate the operation efficiency in each airport (  'DEPARTURE_TIME' - 'ARRIVAL_TIME' ), and give the recommendation for distributive work for the flights.  In addition, we can perform analysis on categorical data such as day of the week, flight status, etc.


Data

The U.S. Department of Transportation's (DOT) Bureau of Transportation Statistics tracks the on-time performance of domestic flights operated by large air carriers. Summary information on the number of on-time, delayed, canceled, and diverted flights is published in DOT's monthly Air Travel Consumer Report and in this dataset of 2015 flight delays and cancellations.
https://www.kaggle.com/usdot/flight-delays/home
In "flights.csv"
Rows: 5819079
Columns: 31

Index(['YEAR', 'MONTH', 'DAY', 'DAY_OF_WEEK', 'AIRLINE', 'FLIGHT_NUMBER',
       'TAIL_NUMBER', 'ORIGIN_AIRPORT', 'DESTINATION_AIRPORT',
       'SCHEDULED_DEPARTURE', 'DEPARTURE_TIME', 'DEPARTURE_DELAY', 'TAXI_OUT',
       'WHEELS_OFF', 'SCHEDULED_TIME', 'ELAPSED_TIME', 'AIR_TIME', 'DISTANCE',
       'WHEELS_ON', 'TAXI_IN', 'SCHEDULED_ARRIVAL', 'ARRIVAL_TIME',
       'ARRIVAL_DELAY', 'DIVERTED', 'CANCELLED', 'CANCELLATION_REASON',
       'AIR_SYSTEM_DELAY', 'SECURITY_DELAY', 'AIRLINE_DELAY',
       'LATE_AIRCRAFT_DELAY', 'WEATHER_DELAY'],
      dtype='object')






Example data sets:
MONTH,AIRLINE,ORIGIN_AIRPORT,DESTINATION_AIRPORT,ARRIVAL_DELAY,DEPARTURE_DELAY,DISTANCE
1,AA,ABQ,DFW,1.0,-3.0,569
1,AA,ATL,DFW,-7.0,-2.0,731
1,AA,ATL,MIA,-1.5,-3.0,594
1,AA,AUS,DFW,-5.0,-4.0,190
1,AA,AUS,JFK,-3.0,-5.0,1521
1,AA,AUS,LAX,-16.0,-6.0,1242
1,AA,AUS,ORD,-6.0,-5.0,978
1,AA,BDL,DFW,-2.0,0.0,1471
1,AA,BDL,MIA,2.0,-2.0,1194
1,AA,BHM,DFW,-10.0,-5.0,597
1,AA,BNA,DFW,-8.0,-4.0,631
1,AA,BNA,LAX,-11.0,-3.0,1797
1,AA,BNA,MIA,5.0,-3.0,806
1,AA,BOS,DFW,-7.0,-3.0,1562
1,AA,BOS,JFK,-3.0,-5.0,187
1,AA,BOS,LAX,-7.0,-2.0,2611

Methods

Use NLP 
