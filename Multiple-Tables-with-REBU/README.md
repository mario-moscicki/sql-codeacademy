I practiced what I learned about joins by combining rows from different tables.  
  
I'm a data analyst at REBU, a ridesharing platform. My supervisor given me a project which had four tables:  

trips - trips information  
riders, riders2 - users data  
cars - autonomous cars  

![code1.jpg](https://github.com/mario-moscicki/sql-codecademy/blob/master/Multiple-Tables-with-REBU/code1.jpg)
My job was to prepare the data according to his request.  
Among other things, my job was:  
- to take simple cross join  function between Riders and Cars  
- I had to create a Trip Log with the trips and its users.  

![code2.jpg](https://github.com/mario-moscicki/sql-codecademy/blob/master/Multiple-Tables-with-REBU/code2.jpg)

- I had to create link by inner join between the Trips and the Cars used during those trips. 

![code3.jpg](https://github.com/mario-moscicki/sql-codecademy/blob/master/Multiple-Tables-with-REBU/code3.jpg)

- In a certain month new riders data came. I had to stack Riders table on top of the new table named Riders2  

![code4.jpg](https://github.com/mario-moscicki/sql-codecademy/blob/master/Multiple-Tables-with-REBU/code4.jpg)

What is the average cost for a trip?  
REBU want's email all irregular users for marketing campaign. I must find users who used less than 500 times.  

![code5.jpg](https://github.com/mario-moscicki/sql-codecademy/blob/master/Multiple-Tables-with-REBU/code5.jpg)  

- Calculate the number of cars that are active.  
- Safe ty FIRST: I Wrote a query that finds the two cars that have the highest trips_completed.  

![code6.jpg](https://github.com/mario-moscicki/sql-codecademy/blob/master/Multiple-Tables-with-REBU/code6.jpg)
  
