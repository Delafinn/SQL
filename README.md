# SQL
```
# variables checks
SHOW VARIABLES LIKE '%binlog%'\G
SHOW VARIABLES LIKE 'innodb%'\G
SHOW VARIABLES LIKE 'max_connections'\G
SHOW VARIABLES LIKE 'query_cache%'\G
SHOW VARIABLES LIKE 'log_error%'\G

# User lookup 
SELECT USER(), CURRENT_USER();
SHOW GRANTS FOR 'username'@'host';
 
# Check DB information
SELECT user, host FROM mysql.user WHERE host LIKE '%';

SHOW INDEXES FROM your_table IN your_schema;

SHOW TRIGGERS FROM your_schema LIKE 'etable_name';


```
