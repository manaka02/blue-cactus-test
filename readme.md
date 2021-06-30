Symfony Test Blue Cactus Application
========================

The "Symfony Test Blue Cactus Application" is an application created for Competence test.

Requirements
------------

  * PHP 7.4 or higher;
  * PDO-SQLite PHP extension enabled;
  * and the [usual Symfony application requirements][2].

Installation
------------

[Download Symfony][4] to install the `symfony` binary on your computer, pull or download the source code and install dependancy

```bash
$ cd  blue-cactus/
$ composer install
```

Usage
-----
- Configure your environnement file .env (Database, MailDSN, ...)

```bash
$ cd  back-office-freelancer-Telma/
```



```bash
$ cd  back-office-freelancer-Telma/
$ symfony server:start
```

Then access the application in your browser at the given URL (<https://localhost:8000> by default).

If you don't have the Symfony binary installed, run `php -S localhost:8000 -t public/`
to use the built-in PHP web server or [configure a web server][3] like Nginx or
Apache to run the application.

Lien pour l'api
------------
Pour accéder à l'api, aller sur le lien http://votre-serveur:port/api

If you have [installed Symfony][4] binary, run this command:

[2]: https://symfony.com/doc/current/reference/requirements.html
[3]: https://symfony.com/doc/current/cookbook/configuration/web_server_configuration.html
[4]: https://symfony.com/download
