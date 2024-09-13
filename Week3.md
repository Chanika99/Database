#Week3

Nape Vithanage Chanika Anjalee

###Assignment 1 

select * from goal;
![Q1.png](Q1.png)

###Assignment 2

select name, type from airport where iso_country="FI";
![Q2.png](Q2.png)

###Assignment 3

select name from airport where iso_country="FI" oder by name asc;
![Q3.png](Q3.png)

###Assignment 4

select name, type from airport where iso_country="FI" oder by type asc,name asc;
![Q4.png](Q4.png)

###Assignment 5

select name from country where name like "F%";
![Q5.png](Q5.png)

###Assignmet 6

select name from country where name like "%F%";
![Q6.png](Q6.png)

###Assignmet 7

select location from game where screen_name="Vesa";
![Q7.png](Q7.png)

###Assignment 8

select co2_consumed from game where screen_name="Ilkka";
![Q8.png](Q8.png)

###Assignment 9

select DISTINCT co2_budget from game;
![Q9.png](Q9.png)

###Assignment 10

select screen_name, co2_budget, co2_consumed, co2_budget - co2_consumed as co2_left from game where screen_name="Ilkka";
![Q10.png](Q10.png)