using port way
1- browser request info.php
2- nginx sees php -> passes request to php-block
3- nginx forwards the request on port 9000 which we defined
4- php-fpm executes the php code "info.php" and returns the result
5- nginx recives the output and send it to the browser