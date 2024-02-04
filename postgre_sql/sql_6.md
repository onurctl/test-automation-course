# 1

SELECT AVG(rental_rate) FROM film; 

-- 2.98000...

# 2

SELECT COUNT(*) FROM film
WHERE title LIKE 'C%';

-- 92

# 3

SELECT MAX(length) FROM film
WHERE rental_rate = 0.99;

-- 184

# 4

SELECT COUNT(DISTINCT replacement_cost) FROM film
WHERE length > 150;

-- 21
