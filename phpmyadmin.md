To install phpMyAdmin without Docker, you can follow these steps:

Install PHP:

Ensure you have PHP installed on your Macbook. You can use Homebrew to install PHP as mentioned earlier:

bash
Copy code
brew install php
Install phpMyAdmin:

You can use Homebrew's phpMyAdmin formula to install phpMyAdmin:

bash
Copy code
brew tap phpmyadmin/phpmyadmin
brew install phpmyadmin
Configuration:

Configure phpMyAdmin as needed. The configuration file is typically located in /usr/local/etc/phpmyadmin/config.inc.php.

Starting phpMyAdmin:

Start phpMyAdmin by navigating to its installation directory and using the PHP built-in server:

bash
Copy code
cd /usr/local/share/phpmyadmin
php -S localhost:8080
Then, access phpMyAdmin in your web browser at http://localhost:8080.

