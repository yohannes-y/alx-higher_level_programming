Use “container-on-demand” to run MySQL

In the container, credentials are root/root

    Ask for container Ubuntu 20.04
    Connect via SSH
    OR connect via the Web terminal
    In the container, you should start MySQL before playing with it:

$ service mysql start                                                   
 * Starting MySQL database server mysqld 
$
$ cat 0-list_databases.sql | mysql -uroot -p                               
Database                                                                                   
information_schema                                                                         
mysql                                                                                      
performance_schema                                                                         
sys                      
$

In the container, credentials are root/root
