# ssh-set-up-command-to-run-in-Vs-code-terminal
Ssh set up commands………………..
ls-l
sudo systemctl disable unattended-upgrades

sudo systemctl stop unattended-upgrades

sudo apt remove unattended-upgrades

sudo apt-mark hold unattended-upgrades

sudo apt-get update -y

sudo apt-get install apache2 -y

sudo apt-get install php libapache2-mod-php php-mysql php-curl php-cgi -y

sudo apt-get install mysql-server -y

sudo mysql

php -v

sudo apt-get install phpmyadmin php-mbstring php-zip php-gd php-json -y

sudo chmod -R 777 /var/www/html

sudo a2enmod rewrite

sudo sed -i '/<Directory \/var\/www\/>/,/<\/Directory>/ s/AllowOverride None/AllowOverride All/' /etc/apache2/apache2.conf

sudo sed -i 's/bind-address.*/bind-address = 0.0.0.0/' /etc/mysql/mysql.conf.d/mysqld.cnf
