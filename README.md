# phpmyadmin-not-found


sudo nano /etc/apache2/apache2.conf
Then add the following line to the end of the file:

Include /etc/phpmyadmin/apache.conf
Then restart apache:

/etc/init.d/apache2 restart
