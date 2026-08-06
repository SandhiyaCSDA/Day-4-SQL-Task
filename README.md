# Day-4-SQL-Task
Day 4 SQL Task
alter table Teachers modify Teachers_id varchar(20);
insert into Teachers (Teachers_id,Name,Age,Department,Email_id,Phone_Number)
values
('24UCSDS002','KAVIYA',30,'COMPUTER SCIENCE','kaviya90@gmail.com','6385749614'),
('24UUBOS002','KARTHI',31,'BCOM','Karthik00@gmail.com','6385749544'),
('24UCSDS008','DEEPIKA',29,'COMPUTER SCIENCE','deepika29@gmail','8855741236'),
('24UBAAS030','ARUNKUMAR',28,'BBA','arunkumarr@gmail.com','9657581236'),
('24UCSDS016','ASWINI',29,'COMPUTER SCIENCE','ashwini@gamil.com','6887456321'),
('24UBCOS015','SHARATHY',45,'BCOM','sharathy42@gmail.com','9685741112'),
('24UCSDS028','ABINIH',23,'COMPUTER SCIENCE','abith23@gmail.com','8958741436'),
('24UBAAS010','KARTHIRAJ',50,'BBA','karthikraj12@gamil.com','6358748836'),
('24UCSDS020','KANNANGI',30,'COMPUTER SCIENCE','kannagi12@gmail.com','6987457111'),
('24UBCOS011','RATHA',35,'BCOM','ratha@gmail.com','9685754222');
select * from Teachers;
select*from students;
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
