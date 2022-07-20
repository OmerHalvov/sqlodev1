# sqlodev1
Patika SQL Ödev-1

Cevap-1:
select title, description from film;

Cevap-2:
select * from film where length >60 and length <75;

Cevap-3:
select * from film where rental_rate=0.99 and (replacement_cost=12.99 or replacement_cost=12.99);

Cevap-4:
select* from customer where first_name='Mary'
last name: Smith

Cevap-5:
select * from film where not (length>50 and rental_rate=2.99 and rental_rate=4.99);
