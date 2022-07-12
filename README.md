# symfony-in-docker

PROJECT START STEPS:

    Pre-requisites:
    1. php must be installed
    2. Composer must be installed (https://getcomposer.org/download/)

    Steps:
    1. To run this application, do the following:
        1.a. Go to the project root directory.
        1.b. Run the following commands in the terminal/command line to build the app:
            - composer install
        1.c. Run the following command(s) in the terminal/command line to run the app:
            - php -S 127.0.0.1:8080 -t public

    
    CLOUD-IDE SETUP STEPS(follow the below steps in case you are using the Cloud IDE instead of your Local IDE):
	1. Please run the below commands from the project root to setup MySQL and MongoDB in this workspace:
		- chmod 0755 ./database-setup.sh
		- sh ./database-setup.sh
	2. In case you want to connect to MySQL or MongoDB, kindly use the following credentials in your application:
		2.a. MySQL
			- host: localhost
			- port: 3306
			- username: root
			- password: admin
			- database: db
		2.b. MongoDB
			- host: localhost
			- port: 27017
			- username: root
			- password: admin
			- database: db
