Install and configure a MySQL server
sudo apt-get install mysql-server
mysql --version
sudo systemctl status mysql.service
sudo mysql_secure_installation

connect to mysql
alter user 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password disini';
create user "root"@"%" identified by "password disini";
