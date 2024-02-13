## INNER JOIN 
![image](https://github.com/Shadowsweep/Google_cybersecuritylabs/assets/122604770/7a24c518-77b9-4014-97c0-a5c59faaca62)
## LEFT JOIN
![image](https://github.com/Shadowsweep/Google_cybersecuritylabs/assets/122604770/8b242a96-4c1b-4e1d-afd5-ba66e88046cf)

## RIGHT JOIN
![image](https://github.com/Shadowsweep/Google_cybersecuritylabs/assets/122604770/1a3a2087-1cee-42b2-bdbf-5a2393c1041c)
## SQL QUERIES
SELECT * 
FROM machines;

SELECT * 
FROM machines 
INNER JOIN employees ON machines.device_id = employees.device_id;

## LEFT JOIN

SELECT * 
FROM machines 
LEFT JOIN employees ON machines.device_id = employees.device_id;

## RIGHT JOIN

SELECT * 
FROM machines 
RIGHT JOIN employees ON machines.device_id = employees.device_id;

## INNER JOIN

SELECT * 
FROM employees 
INNER JOIN log_in_attempts ON employees.username = log_in_attempts.username;

