Custom library of bare-bones MYSQL query and manipulation functions to perform basic SELECT, INSERT, and UPDATE queries.

Library provides a VERY lightweight wrapper to to sanitize data and run simple MySQL queries.  Accepts associative arrays for both query and data, and return associative arrays with results.

Functions assume a MySQL connection has been established, and that a database has been selected, e.g. 

$db=mysql_connect (MYSQL_SERVER, MYSQL_USER, MYSQL_PASSWORD) or die ('I cannot connect to the database because: ' . mysql_error());
mysql_select_db (MYSQL_DATABASE);

See inline comments for further documentation
