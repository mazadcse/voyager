# Voyager

## Commands
composer create-project --prefer-dist laravel/laravel blog "6.*"

composer require tcg/voyager

php artisan voyager:install

php artisan voyager:install --with-dummy

php artisan serve


## Clear
-----------------------
php artisan config:clear
php artisan cache:clear
php artisan view:clear
php artisan route:clear
composer dump-autoload



## Command to start serve
-----------------------
php artisan serve --host=192.168.78.10 --port=5314 &
php artisan serve --host=210.4.76.133 --port=5314 &

exit

Command to kill/stop serve:
ps -ef | grep "$PWD/server.php"

[root@dev-deeds brta_arch]# root      6817  6813  0 17:14 ?        00:00:00 /usr/bin/php -S 192.168.78.10:5000 /var/www/brta_arch/server.php
bash: root: command not found...
[root@dev-deeds brta_arch]# root      7032  6973  0 17:17 pts/2    00:00:00 grep --color=auto /var/www/brta_arch/server.php

kill 6817

## Auth
email: admin@admin.com
password: password
