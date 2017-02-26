# Old-style mysql functions support for PHP 7

In PHP 7 functions like mysql_connect, mysql_query and so on were completely removed. But there is much of code, which still needs them. 
This simple file allows to redirect calls to same functions from MySQLi extension. Just put it to the root directory of your site and append 
include 'mysql.php'; 
in the start of your index.php file.
