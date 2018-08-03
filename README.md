# set-memory-limit-in-htaccess

In your .htaccess you can try this code:

<IfModule mod_php5.c>
php_value memory_limit 64M
</IfModule>
