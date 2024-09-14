#week 3, Exercise 2

### Q1
Select * form goal;
![ex 2 q1.png](ex%202%20q1.png)

### Q2
select name,type from airport where iso_country = "FI";
![ex2q2.png](ex2q2.png)

### Q3
select name from airport where iso_contry = "FI" order by name asc;
![ex2q3.png](ex2q3.png)

### Q4
select name,type from airport where iso_country = "FI" order by type asc;
![ex2q4.png](ex2q4.png)

### Q5
select name from country where name like 'F%';
![ex2q5.png](ex2q5.png)

### Q6
select name from country where name like "%F%";
![ex2q6.png](ex2q6.png)

### Q7
select location from game where screen_name = "Vesa",
![ex2q7.png](ex2q7.png)

### Q8
select co2_consumed from game where screen_name = "Ilkka";
![ex2q8.png](ex2q8.png)

### Q9
select DISTINCT co2_budget from game;
![ex2q9.png](ex2q9.png)


### Q10
select screen_name,co2_budget,co2_consumed,co2_budget-co2_consumed as co2_left from game where screen_name = "Ilkka";
![ex2q10.png](ex2q10.png)
