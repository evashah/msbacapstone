# msbacapstone
2016-17 MSBA Capstone using Yelp Academic Dataset

R - Code

1) Extract Friends List from User JSON file

2) Read RDS file and summarize data: Reads userIDs and friendID list, calculate the number of friends per userID and the fraction of users that have friends or a social edge

Data saved on Google Shared Drive

1) User_Friends.csv: Includes userIDs, number of friends and list of friendIDs per user

2) Friends_list.rds: List of UserIDs and list of friendsIDs per user

Link = https://drive.google.com/open?id=0BwrA7eAVD8Y9Q3hzTUlweUhJc0k

Summary Output:

Table: Number of friends

 Minimum    Average    Maximum 
---------  ---------  ---------
    0          6        3812   
    
    
Table: Fraction of users with a social edge (9 or less)

 Percent of Users    Number of Friends 
------------------  -------------------
      54.84                  0         
      12.00                  1         
       6.38                  2         
       4.20                  3         
       3.00                  4         
       2.25                  5         
       1.81                  6         
       1.45                  7         
       1.22                  8         
       1.04                  9   



