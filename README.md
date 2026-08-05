# Day-4-SQL-Task
Day 4 SQL Task
select*from students 
order by name asc;
select * from teachers
order by department asc;
select distinct department from students;
select name from teachers limit 5;
select name, Bloodgroup, Age
from students
group by name,bloodgroup,age;
select name, Bloodgroup, Age
from students
group by name,bloodgroup,age
having age>19
