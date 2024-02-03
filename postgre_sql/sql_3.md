# LIKE, ILIKE

# 1

SELECT country FROM country WHERE country ILIKE 'A%a'

# 2

SELECT country FROM country WHERE country ILIKE '_____%n' 

(at least 6 characters & ends with 'n')

# 3

SELECT title FROM film WHERE title ILIKE '%T%T%T%T%';

(contains at least four 'T')

# 4

SELECT * FROM film WHERE title LIKE 'C%' AND length > 90 AND rental_rate = 2.99
