

------------------------------------------------------------------------------PMS-----------------------------------------------------------------------------------------------------
create database project;
use project;

create table project.employee(
emp_id varchar(5) not null,
phone_no int(10),
first_name varchar(20) not null,
last_name varchar(20) not null,
salary int(10),
dob date not null,
license int(10) unique,
start_date date not null, 
end_data date,
primary key(emp_id)
); 


select * from employee;

insert into 
	project.employee(emp_id, phone_no, first_name, last_name, salary, dob, license, start_date)
values
	('E001', 987654321, 'Rajesh', 'Verma', 50000, date '1980-04-14', 12001, date '2010-02-01'),
    ('E002', 987654321, 'Vinod', 'Khanna', 20000, date '1972-12-14', 12002, date '2000-02-15'),
    ('E003', 987654322, 'Ramesh', 'Singh', 100000, date '1975-12-01', 12003, date '2012-02-12'),
    ('E004', 987654313, 'Suresh', 'Srivastva', 70000, date '1995-11-18', 12004, date '2011-02-21'),
    ('E005', 987615214, 'Dipank', 'Rathod', 40000, date '1978-10-22', 12005, date '2002-02-25'),
    ('E006', 987613215, 'Rathod', 'Singh', 50000, date '1973-01-21', 12006, date '2009-02-21'),
    ('E007', 987643216, 'Sardar', 'Khan', 60000, date '1984-06-26', 12007, date '2014-02-12'),
    ('E008', 986543217, 'Faizal', 'Khan', 70000, date '1991-04-01', 12008, date '2005-02-02'),
    ('E009', 986543218, 'Rohit', 'Mehra', 90000, date '1973-02-15', 12009, date '2003-02-28'),
    ('E010', 986543219, 'Shubham', 'Verma', 80000, date '1971-02-12', 12010, date '2012-02-05');
select emp_id, first_name, lastname, salary
from employee;


    
select * from employee;
    
create table project.presciption_drugs(
name varchar(225),
pres_id varchar(10),
quantity int(20)
);

alter table project.presciption_drugs
modify pres_id varchar(10);

insert into 
	project.presciption_drugs(name, pres_id, quantity)
values
	('Acetaminophen', 'P001', 2),
	('Adderall', 'P002', 4),
    ('Cyclobenzaprine', 'P003', 2),
    ('Januvia', 'P004', 1),
    ('Prednisone', 'P005', 4),
    ('Entresto', 'P006', 5),
    ('Invokana', 'P007', 3),
    ('Lyrica', 'P008', 2),
    ('Farxiga', 'P009', 2),
    ('Humira', 'P010', 5),
    ('Cephalexin', 'P011', 1),
    ('Azithromycin', 'P012', 4),
    ('Ibuprofen', 'P013', 5),
    ('Omeprazole', 'P014', 3),
    ('Wellbutrin', 'P015', 2),
    ('Xanax', 'P016', 1),
    ('Trazodone', 'P017', 4),
    ('Gilenya', 'P018', 2),
    ('Hydrochlorothiazide', 'P019', 2),
    ('Naproxen', 'P020', 3);
    
    select * from project.presciption_drugs;



Create Table Customers
(
Customer_Id varchar(10),
C_Name varchar(50),
Address Varchar(60),
Gender Varchar(20),
Phone_No double,
DOB date,
Age int,
Primary key(Customer_id)
);

Create Table pres
(
Pres_Id varchar(10),
Customer_Id varchar(10),
Pres_date date,
Primary key(Pres_Id)
);

ALTER TABLE pres
   ADD FOREIGN KEY (Customer_Id) REFERENCES customers (Customer_Id);
   
INSERT INTO 
	Customers(Customer_Id ,C_Name,Address,Gender,Phone_No,DOB,Age)
values 
	('C001','Piyush','Kandivali','Male',9029728712,Null,22 ),
   ('C002','Yash Moar','Thane','Male',9381194521,'1998-01-16',21 ),
   ('C003','Pratik Pai','Virar','Male',7350202146,'1997-03-11', 22),
   ('C004','Anmol Pandita','Andheri','Male',7894561230,'1991-01-04',28 ),
   ('C005','Ketaki Ransing','Thane','Female',8291536323,'1990-02-09', 29),
   ('C006','Aditi Parmar','Kalyan','Female',7506335103,'1996-05-30', 23),
   ('C007','Manish Parmar','Kandivali','Male',7794875190,'1992-06-21',27 ),
   ('C008','Srushti Yadahalli','Goregaon','Female',9619326790,'1999-08-15',21 ),
   ('C009','Sreekar L','Ghatkopar','Male',9930700411,'1997-11-13', 23),
   ('C010','Vaibhav Pudke','Andheri','Male',9767273964,'1995-11-19', 25),
   ('C011','Anuja Sharma','Andheri','Female',8888896957,'1994-12-10', 26),
   ('C012','Amogh Zare','Boriwali','Male',9867416562,'1991-10-04', 29),
   ('C013','Rupal Handoo','Andheri','Female',9971556906,'1992-08-02',28 ),
   ('C014','Kaushik Jha','Bandra','Male',7045766745,'1993-09-15', 27),
   ('C015','Pritam Mane','Kandivali','Male',9004648566,'1994-04-22',25 ),
   ('C016','Vedant Kumar','Powai','Male',8108106620,'1998-05-24', 21),
   ('C017','Vishakha Pathak','Powai','Female',9834427912,'1999-06-26',20 ),
   ('C018','Pradhuman Singh','Santa cruz','Male',9004549993,'1992-01-08',27 ),
   ('C019','Shriya Akella','Goregaon','Female',9619310534,'1998-02-10', 21),
   ('C020','Shrishti Kaushik','Virar','Female',7738907480,'1995-06-20', 24);
   select * from customers;


INSERT INTO pres(Pres_Id,Customer_Id,Pres_date )
Values
   ('P001','C001','2020-04-12'),
   ('P002','C002','2020-06-14'),
   ('P003','C003','2017-05-11'),
   ('P004','C004','2018-07-01'),
   ('P005','C005','2019-10-02'),
   ('P006','C006','2020-06-06'),
   ('P007','C007','2016-10-19'),
   ('P008','C008','2015-12-21'),
   ('P009','C009','2018-11-24'),
   ('P010','C010','2019-11-01'),
   ('P011','C011','2017-06-09'),
   ('P012','C012','2018-05-29'),
   ('P013','C013','2019-05-21'),
   ('P014','C014','2020-04-13'),
   ('P015','C015','2020-05-12'),
   ('P016','C016','2015-02-19'),
   ('P017','C017','2015-10-12'),
   ('P018','C018','2019-09-10'),
   ('P019','C019','2019-06-30'),
   ('P021','C001','2015-04-12'),
   ('P022','C002','2018-12-20'),
   ('P023','C003','2017-02-17'),
   ('P024','C004','2016-03-05'),
   ('P025','C005','2020-05-02');



create table Bill(
bill_no varchar(35) primary key,
order_id varchar(35),
customer_no varchar(35),
quantity int,
total_sum int,
tax_applied int,
grand_total_amount int
);

insert into Bill 
(bill_no, order_id, customer_no, quantity, total_sum)
values
('B001','O001','C001',5,200),
('B002','O001','C001',1,100),
('B003','O002','C002',10,2200),
('B004','O003','C003',6,350),
('B005','O004','C004',2,50),
('B006','O005','C005',7,1000),
('B007','O006','C006',3,250),
('B008','O006','C006',6,355),
('B009','O007','C007',9,650),
('B010','O008','C008',20,4599),
('B011','O008','C008',14,799),
('B012','O009','C009',1,33),
('B013','O010','C010',1,70),
('B014','O011','C011',2,200),
('B015','O012','C012',4,300),
('B016','O013','C013',6,780),
('B017','O013','C013',8,960),
('B018','O014','C014',4,320),
('B019','O015','C015',3,66),
('B020','O016','C016',2,40),
('B021','O017','C017',1,200),
('B022','O018','C018',5,600),
('B023','O019','C019',20,2999),
('B024','O020','C020',6,280),
('B025','O020','C020',7,350),
('B026','O021','C005',3,450),
('B027','O021','C005',1,799),
('B028','O022','C004',2,59),
('B029','O023','C018',9,687),
('B030','O024','C011',7,225),
('B031','O025','C006',5,360);

update bill
set tax_applied = 0.15*total_sum;

update bill
set grand_total_amount = tax_applied + total_sum;

create table Orders(
customer_no varchar(35),
order_id varchar(35) primary key,
order_date date,
presp_id varchar(35),
emp_id varchar(35)
);


insert into Orders 
(emp_id, order_id, customer_no, order_date, presp_id)
values
('E001','O001','C001','2020-03-22','P001'),
('E001','O002','C002','2020-03-23','P002'),
('E001','O003','C003','2020-03-23','P003'),
('E002','O004','C004','2020-03-23','P004'),
('E002','O005','C005','2020-03-24','P005'),
('E002','O006','C006','2020-03-24','P006'),
('E002','O007','C007','2020-03-24','P007'),
('E003','O008','C008','2020-03-25','P008'),
('E004','O009','C009','2020-03-25','P009'),
('E004','O010','C010','2020-03-25','P010'),
('E004','O011','C011','2020-03-26','P011'),
('E004','O012','C012','2020-03-26','P012'),
('E005','O013','C013','2020-03-26','P013'),
('E005','O014','C014','2020-03-27','P014'),
('E005','O015','C015','2020-03-27','P015'),
('E006','O016','C016','2020-03-27','P016'),
('E006','O017','C017','2020-03-28','P017'),
('E006','O018','C018','2020-03-28','P018'),
('E006','O019','C019','2020-03-28','P019'),
('E007','O020','C020','2020-03-28','P020'),
('E007','O021','C005','2020-03-29','P021'),
('E007','O022','C004','2020-03-29','P022'),
('E008','O023','C018','2020-03-29','P023'),
('E008','O024','C011','2020-03-29','P024'),
('E009','O025','C006','2020-03-29','P025');

 create table medicineList
   (
   Price double,
   StockQty double,
   DrugName varchar(60),
   ExpiryDate date,
   Primary key(DrugName )
   );
   
  INSERT INTO  medicineList( DrugName,Price,StockQty,ExpiryDate )
   Values ('Acetaminophen', 500, 100,'2021-05-11'),
	('Adderall', 50, 100,'2022-06-20'),
    ('Cyclobenzaprine', 77, 50,'2019-04-13'),
    ('Januvia', 235, 500,'2022-09-10'),
    ('Prednisone', 600, 100,'2021-11-11'),
    ('Entresto', 1000, 200,'2021-06-01'),
    ('Invokana', 950, 300,'2021-07-30'),
    ('Lyrica', 740, 400,'2022-02-16'),
    ('Farxiga', 140, 400,'2021-12-12'),
    ('Humira', 165, 500,'2022-03-13'),
    ('Cephalexin', 560,200,'2018-05-21'),
    ('Azithromycin', 190,100,'2022-06-16'),
    ('Ibuprofen', 100, 300,'2021-09-13'),
    ('Omeprazole', 870, 200,'2023-04-20'),
    ('Wellbutrin', 700, 400,'2017-07-23'),
    ('Xanax', 990, 95,'2021-01-21'),
    ('Trazodone', 260, 50,'2022-09-20'),
    ('Gilenya', 30, 400,'2019-10-15'),
    ('Hydrochlorothiazide', 300,200,'2023-09-17'),
    ('Naproxen', 400, 100,'2022-01-10'),
    ('Amlodipine',550,300,'2021-02-17'),
     ('Amoxicillin',350,200,'2022-03-19'),
     ('Ativan',250,100,'2021-04-13'),
     ('Metoprolol',150,500,'2022-05-21'),
    ('Loratadine',50,300,'2023-06-04'),
    ('Doxycycline',200,400,'2019-07-26'),
     ('Onpattro',300,100,'2021-08-14');
     SELECT * FROM medicineList;

------------------------------------------------------------------END---------------------------------------------------------------------------------------------

select c.customer_id, c.c_name, l.name, l.quantity, l.pres_date
from customers as c
left join 
		(select p.name, p.quantity, pr.pres_date, pr.customer_id
		from presciption_drugs as p
		inner join pres as pr
		on p.pres_id=pr.pres_id) as l
on c.customer_id=l.customer_id;

select b.customer_no, c.c_name, sum(b.total_sum) as Total_sum
from bill as b
inner join customers as c
on b.customer_no = c.customer_id
group by b.customer_no
having c.customer_no = "C001";
order by Total_sum desc;


create view newemp as
select emp_id, first_name, last_name, salary
from employee
insert into 
	project.employee(emp_id, phone_no, first_name, last_name, salary, dob, license, start_date)
values
    ('E010', 986543219, 'Shubham', 'Verma', 80000, date '1971-02-12', 12010, date '2012-02-05');
delete from newemp
where emp_id='E010';
select * from newemp;


select * from employee;
drop view if exists newemp;

SELECT DrugName,ExpiryDate,Price,StockQty
FROM medicineList
WHERE ExpiryDate<SYSDATE();


select orders.order_date,
count(*) total_orders,
sum(grand_total_amount) as total_revenue
from orders
left join bill
on  bill.order_id = orders.order_id
group by order_date;

select orders.order_date, orders.emp_id,
sum(grand_total_amount) as total_revenue_processed_by_the_employee,
sum(quantity) as total_medicines_processed_by_the_employee
from bill
left join orders
on bill.order_id = orders.order_id
group by emp_id,order_date;

select * from presc

select * from customers;

update customer 
set c_name = "ayush"

CREATE TABLE Employeee(emp_id INTEGER PRIMARY KEY, dept_id INTEGER, mngr_id INTEGER, emp_name VARCHAR(20), salary INTEGER); 
CREATE TABLE Department(dept_id INTEGER PRIMARY KEY, dept_name VARCHAR(20));

INSERT INTO 
	Department (dept_id, dept_name) 
VALUES 
	(1, 'Finance'), 
    (2, 'Legal'), 
    (3, 'IT'), 
    (4, 'Admin'), 
    (5, 'Empty Department');

INSERT INTO 
	Employeee(emp_id, dept_id, mngr_id, emp_name, salary) 
VALUES
	( 1, 1, 1, 'CEO', 100), 
    ( 2, 3, 1, 'CTO', 95), 
    ( 3, 2, 1, 'CFO', 100), 
    ( 4, 3, 2, 'Java Developer', 90), 
    ( 5, 3, 2, 'DBA', 90), 
    ( 6, 4, 1, 'Adm 1', 20), 
    ( 7, 4, 1, 'Adm 2', 110), 
    ( 8, 3, 2, 'Web Developer', 50), 
    ( 9, 3, 1, 'Middleware', 60), 
    ( 10, 2, 3, 'Legal 1', 110), 
    ( 11, 3, 3, 'Network', 80), 
    ( 12, 3, 1, 'UNIX', 200);
    
select a.emp_id,a.dept_id, b.dept_id, a.emp_name, a.salary, b.salary, b.emp_id
from employeee a
inner join employeee b
on a.mngr_id = b.emp_id
where a.salary > b.salary; 

SELECT a.emp_name, a.dept_id
from employeee a 
join(
	SELECT a.dept_id, MAX(salary) as max_salary
	from employeee
	inner join department
	using(dept_id)
	group by dept_id ) b
ON a.salary = b.max_salary AND a.dept_id = b.dept_id; 

SELECT a.dept_id, MAX(salary) as max_salary
from employeee
inner join department
using(dept_id)
group by dept_id 
where count(*) < 3;

select dept_id,  count(*)
from employeee
group by dept_id
having count(*) < 3;

select dept_name, count(dept_id)
from employeee a 
join department d 
using (dept_id)
group by dept_id;

select a.emp_name from employeee a
inner join employeee b
on a.mngr_id = b.emp_id
where a.dept_id <> b.dept_id;

select d.dept_name, sum(e.salary)
from employeee e
inner join department d
using (dept_id)
group by d.dept_id

select DISTINCT salary, emp_name
from employeee
order by salary desc
limit 1,2;


select emp_id, salary
from employeee a
where 4 = (select count(salary) from employeee b where b.salary > a.salary);

select * from employeee;

select emp_name, salary, count(salary) as sal
from employeee
group by salary
having sal > 1

select * from 
( select employeee.*, row_number() over (order by salary desc) as row_num from Employeee ) 
where row_num = 2;

select max(salary) from employeee
where salary not in (select max(salary) from employeee)
