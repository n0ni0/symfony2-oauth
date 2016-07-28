**Symfony2-oauth**
====

This demo contains a register form with two options, register using FOSUserBundle or login with facebook using HWIOAuthBundle.


Used bundles:
-----------------------

[FOSUserBundle](https://github.com/FriendsOfSymfony/FOSUserBundle) -- User management  
[HWIOAuthBundle](https://github.com/hwi/HWIOAuthBundle) -- Login users using oauth, facebook in this case





**Installation**
------------

- Clone the repository from github

```
$ git clone git@github.com:n0ni0/symfony2-oauth.git <your-path-to-install>
$ cd <your-path-to-install>
```

- Use Composer to get the dependencies

```
$ composer install
```

-  Set up the Database

```
$ php app/console doctrine:database:create
$ php app/console doctrine:schema:create
```

- Run a built-in web server

```
$ php app/console server:run
```

- And type in your favourite browser:

```
http://127.0.0.1:8000
```

> **NOTE**
>
> To use built-in web server you need PHP 5.4 or higher
> http://http://symfony.com/doc/current/cookbook/web_server/built_in.html
>
> If you're using PHP 5.3, configure your web server to point at the web/ directory of the project.
> http://symfony.com/doc/current/cookbook/configuration/web_server_configuration.html
>