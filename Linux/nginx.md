# Nginx

# Configuration Files:

php: /etc/php.ini

php-fpm: /etc/php-fpm.d/www.conf

nginx: /etc/nginx/conf.d/default.conf

nginx html files: /usr/share/nginx/html/

# Setup Nginx:

sudo yum install epel-release

sudo yum install nginx

sudo systemctl start nginx

sudo systemctl enable nginx

# Setup MySQL

sudo yum install mariadb-server mariadb

sudo systemctl start mariadb

sudo mysql_secure_installation

sudo systemctl enable mariadb

# Setup PHP
sudo yum install php php-mysql php-fpm

Setup php-fpm and nginx configuration files

