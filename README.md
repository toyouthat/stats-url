#visitas-url-middleware
===================
A Slim 3 middleware muestra visitas por url

Se encarga de mantener actualizadas las estadísticas de uso del sitio web.
Para ello tendrá que crear una tabla nueva en la base de datos para las estadisticas Url , visitas. 
El middleware incrementará el contador de visitas asociado a cada URL.

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
