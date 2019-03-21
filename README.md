# Databases-Assignment_8
### Master IP: 68.183.191.61 
Set up the slave with the following command (change the password to what's in the credentials.txt):
```mysql
CHANGE MASTER TO MASTER_HOST='68.183.191.61', MASTER_USER='slave_user', MASTER_PASSWORD='REPLACE_ME';
```
To start the slave, run this last command:
```mysql
START SLAVE;
```
