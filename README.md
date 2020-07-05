# af-basic
Basic Airflow 

# installation:
On a free tier Ubuntu AWS machine with x64: 

install pip: sudo apt-get update && sudo apt-get install python-pip

update to python 3.6: sudo apt-get update && sudo apt-get install python3.6

install pip3: sudo apt install python3-pip

install mysql: sudo apt update && sudo apt install mysql-server

sudo mysql 

create a new schema: create schema airflow;

create a new user: CREATE USER 'sammy'@'localhost' IDENTIFIED BY 'password'; GRANT ALL PRIVILEGES ON *.* TO 'sammy'@'localhost' WITH GRANT OPTION; exit; 

start running mysql: sudo service mysql start

check running: sudo service mysql status 

install airflow: pip3 install apache-airflow



references: 
* https://stackoverflow.com/questions/14716569/e-unable-to-locate-package-pip/14885081
* https://airflow.apache.org/docs/stable/installation.html
* https://www.digitalocean.com/community/tutorials/how-to-install-mysql-on-ubuntu-18-04
* https://docs.python-guide.org/starting/install3/linux/
* https://docs.python-guide.org/starting/install3/linux/
