# sk-php-selector
PHP selector for centos 6/7 

# RUN AT YOUR OWN RISK

This install php 5.4, 5.5, 5.6, 7.0, 7.1, 7.2 and 7.3 in your centos 6 and centos 7

**sk-php-selecto2.sh is fot testing but with it you can select aditional versions of php

# So you can select just one version runing it as:

bash sk-php-selector2.sh php72

# Or install multiple version

bash sk-php-selector2.sh php56 php71

# or install all

bash sk-php-selector2.sh all

This works fine, the configuration of php need some work so try firts in test enviroment

------------

This can break phpmyadmin, in this case you need delete some mod_php files in /etc/httpd/conf.d/ you can move out all php??.conf just leave php.conf ( not delete maybe you need restore it )

This is aleatory and need more debugin, not always was broken so I cant say you exactly, but the solution is wasy
