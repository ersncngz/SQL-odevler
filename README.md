# ODEV 1

## 1 - SELECT title, description FROM film
## 2 - SELECT * FROM film WHERE length > 60;
## 3 - SELECT * FROM film WHERE rental_rate = 0.99 AND replacement_cost = 12.99 OR replacement_cost = 28.99
## 4 - SELECT first_name, last_name FROM customer WHERE  first_name = 'Mary'
## 5 - SELECT * FROM film WHERE NOT (length > 50 AND  rental_rate = 2.99 OR  rental_rate = 4.99)
 # ODEV 2

 ## 1 - SELECT * FROM film WHERE replacement_cost BETWEEN 12.99 AND 16.99
 ## 2 - SELECT first_name, last_name FROM actor WHERE first_name IN ('Penelope' , 'Nick', 'Ed')
 ## 3 - SELECT * FROM film WHERE rental_rate IN(0.99, 2.99, 4.99) OR replacement_cost IN(12.99, 15.99, 28.99)

# ODEV 3 

## 1 - SELECT country FROM country WHERE country LIKE 'A%a'
## 2 - SELECT country FROM country WHERE country LIKE '_____n'
## 3 - SELECT title FROM film WHERE title ILIKE '%T%%T%%T%%T%'
## 4 - SELECT * FROM film WHERE title LIKE '%C' AND length > 90 AND rental_rate = 2.99G
