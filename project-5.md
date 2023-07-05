## **Documentation for Project 5**

### Installing MySQL Server 
`sudo apt update`
`sudo apt install mysql-server -y`
![MySQL-Server-Installed](./Images/update.png)
![MySQL-Server-Installed](./Images/mysql.png)


### Installing MySQL Client 
`sudo apt update`
`sudo apt-get install libmysqlclient21`
`sudo apt install mysql-client -y`
![MySQL-Server-Installed](./Images/mysql-repo.png)
![MySQL-Server-Installed](./Images/mysql-client.png)
![MySQL-Server-Installed](./Images/mySql%20(2).png)

### Binding IP Address
`sudo vi /etc/mysql/mysql.conf.d/mysqld.cnf`
![Binding-IP-Address](./Images/binding-address.png)

### Connecting to Mysql server from Mysql Client
`sudo mysql -u remote_user -h 172.31.15.255`
![Connection-to-mysql server](./Images/connecting-mysql-client.png)
![Connection-to-mysql server](./Images/mysql-user.png)


