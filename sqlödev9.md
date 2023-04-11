   # 1
    Select city.city, country.country from city
    join country on city.country_id = country.country_id

   # 2
    select customer.first_name,customer.last_name, payment.payment_id from customer
    join payment on payment.customer_id = customer.customer_id
    
   # 3
    select customer.first_name,customer.last_name, rental.rental_id from customer
    join rental on rental.customer_id = customer.customer_id
    
