## SQL QUERIES
   SELECT *
   FROM log_in_attempts
   WHERE login_time > '18:00' AND success = FALSE;
## AND 
   SELECT * 
   FROM log_in_attempts 
   WHERE login_date = '2022-05-09' OR login_date = '2022-05-08';
## LIKE
   SELECT * 
   FROM log_in_attempts 
   WHERE NOT country LIKE 'MEX%';
## OR
   SELECT * 
   FROM employees 
   WHERE department = 'Finance' OR department = 'Sales';

## NOT

   SELECT * 
   FROM employees 
   WHERE NOT department = 'Information Technology';

