# 1

CREATE TABLE employee(
  
  id INTEGER,
  
  name VARCHAR(50) NOT NULL,
  
  birthday DATE,
  
  email VARCHAR(100)

);

# 2 Mockaroo

Insert:

![mockaroo](/postgre_sql/img/insert-from-mockaroo.png)

After Insert:

![after-mockaroo](/postgre_sql/img/after-insert-from-mockaroo.png)

# 3

UPDATE employee
SET name = 'updatename',
	birthday='1999-06-06',
    email = 'xxx@gmail.com'
WHERE id = 26; 

UPDATE employee
SET name = 'updatename',
	birthday='1999-06-06',
    email = 'xxx@gmail.com'
WHERE name = 'Jess';

UPDATE employee
SET name = 'updatename',
	birthday='1999-06-06',
    email = 'xxx@gmail.com'
WHERE email = 'afussey13@digg.com'; 

UPDATE employee
SET name = 'updatename',
	birthday='1999-06-06',
    email = 'xxx@gmail.com'
WHERE birthday = '1941-01-18';

UPDATE employee
SET name = 'zzz',
	birthday='1999-06-06',
    email = 'xxx@gmail.com'
WHERE id = 25; 

# 4

DELETE FROM employee
WHERE name ='Nichol';

DELETE FROM employee
WHERE name ='Cate';

DELETE FROM employee
WHERE id > 12;

DELETE FROM employee
WHERE birthday = '1915-08-02';

DELETE FROM employee
WHERE email = 'apoolton18@g.co';

