# project_1_server_Linux_Local

Project-#1 & #2: Manual and automated provisionning of a Web App on a local machine
This project sets up a web app in on a local machine using vagrant to configure the differnt servers on Virtualbox, these VMs interrract with each other via HTTP protocole. Users login to the site, their credentials are stored in the MySql database, each time data is fetched from the data base, a copy is cached in memcached offload the database from being overwhelmed with many reads, thus optimising data reads. RabbitMq is used to couple between the services.

Services involved:
Linux  Centos 
Apache
Nginix
RabbitMQ
Memcached
MySql
Wordpress
