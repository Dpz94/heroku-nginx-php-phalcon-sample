Sample Phalcon Project
----------------------
This is a sample project for our Heroku buildpack https://github.com/droc-ventures/heroku-nginx-php-phalcon.

Configurations
--------------
There are sample configurations for Nginx and PHP within this project. The Nginx configuration has some tweaks and includes the necessary rewrites to properly redirect to the controllers. If you decide to rename the ```public``` folder, you need to update the root path in the Nginx conf ```/conf/vendor/nginx/conf/nginx.conf```.

Testing
-------
This project is based on the Phalcon tutorial and only contains two controllers ```/Index``` and ```/Test```, but it's enough to test your buildpack installation.
