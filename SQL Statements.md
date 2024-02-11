## Statements to select and use query
  SELECT * FROM 
  log_in_attempts 
  WHERE login_date > '2022-05-09';

## use of operators
   SELECT * FROM 
   log_in_attempts 
   WHERE login_date > '2022-05-09';

   SELECT * 
   FROM log_in_attempts 
   WHERE login_date >= '2022-05-09';

## Use of between statements
   SELECT * 
   FROM log_in_attempts 
   WHERE login_date BETWEEN '2022-05-09' AND '2022-05-11';

   SELECT * 
   FROM log_in_attempts 
   WHERE login_time < '07:00:00';

  ## Use of between statement for time 
    SELECT * 
    FROM log_in_attempts 
    WHERE login_time BETWEEN '06:00:00' AND '07:00:00';

  ## Numeric data 
    SELECT event_id, username, login_date 
    FROM log_in_attempts 
    WHERE event_id >= 100;
