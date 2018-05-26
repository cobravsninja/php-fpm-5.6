# php-fpm-5.6

Simple alpine based image with php-fpm-5.6 inside and default fpm params which listens for incoming connections on /tmp/php.sock (that's right, TCP has been disabled). Could be useful for old LAMP 2-3 visitors per day web sites. List of installed packages:

- php5-fpm
- php5-cli 
- php5-common 
- php5-suhosin
- php5-mysql 
- php5-mysqli 
- php5-mcrypt 
- php5-gd 
