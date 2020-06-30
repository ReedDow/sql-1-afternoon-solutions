-- create table person(
-- 	id serial primary key,
--   name varchar(100),
--   age integer,
--   height integer,
--   city varchar(200),
--   favorite_color varchar(100)
-- );
-- insert into person(name, age, height, city, favorite_color)
-- values 
-- 	('Peter', 21, 176, 'St. Louis', 'blue'),
--   ('Susan', 34, 162, 'New York City', 'green'),
--   ('Pablo', 45, 180, 'St. Paul', 'yellow'),
--   ('Theresa', 51, 170, 'Buffalo', 'orange'),
--   ('Margaret', 23, 155, 'Edmonton', 'green');
-- select * from person order by height desc;
-- select * from person order by height asc;
-- select * from person order by age desc;
-- select * from person order by age >20;
-- select * from person where age = 18;
-- select * from person where age < 20 or age > 30;
-- select * from person where age != 27;
-- select * from person where favorite_color != 'red';
-- select * from person where favorite_color != 'red' and favorite_color !='blue';
-- select * from person where favorite_color = 'orange' or favorite_color = 'green';
-- select * from person where favorite_color in ('orange', 'green', 'blue');
-- select * from person where favorite_color in ('purple', 'yellow');


-- create table orders(
--   order_id serial primary key,
--   person_id int,
--   product_name varchar(200),
--   product_price float,
--   quantity int
-- );
-- insert into orders(person_id, product_name, product_price, quantity)
-- values
-- (124, 'shoes', 45, 1),
-- (372, 'couch', 980, 1),
-- (456, 'Playstation 5', 499, 2),
-- (232, 'soup', 4, 3),
-- (421, 'clock', 25, 5);
-- select * from orders
-- select sum(quantity) from orders;
-- select sum(product_price) from orders;
-- select sum (quantity * product_price) from orders where person_id = 456;


-- insert into artist(name)
-- values
-- ('Lisa'),
-- ('Alex'),
-- ('Pedro')
-- select * from artist order by name desc limit 10;
-- select * from artist order by name asc limit 5;
-- select * from artist where name like 'Black%';
-- select * from artist where name like '%Black%';


-- select * from employee where city = 'Calgary';
-- select max(birth_date) from employee;
-- select min(birth_date) from employee;
-- select * from employee where first_name = 'Nancy';
-- select * from employee where reports_to = 2;
-- select count(*) from employee where city = 'Lethbridge';


-- select count(*) from invoice where billing_country = 'USA';
-- select max(total) from invoice;
-- select min(total) from invoice;
-- select * from invoice where total > 5;
-- select count(*) from invoice where total < 5;
-- select count(*) from invoice where billing_state in ('CA', 'TX', 'AZ');
-- select avg(total) from invoice; 
-- select sum(total) from invoice;


