#visitas-url-middleware
===================
A Slim 3 middleware muestra visitas por url

##Práctica final del módulo 3

##Install the Middleware
----------------------
```
composer require toyouthat/start-url
```

##Use the Middleware
------------------
```
$app->add(new \Slim\Middleware\SafeURLMiddleware());
```
