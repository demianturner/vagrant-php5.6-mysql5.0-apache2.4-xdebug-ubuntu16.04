Vagrant box with PHP 5.6 + mysql 5.0 + apache2.4 + xdebug + ubuntu16.04
=======================================================================
forked from cakebake/vagrant-php56

Vagrant box **php56.seagullframework.dev** with

-	PHP 5.6
-	XDebug 
-	Apache
-	Composer
-	MySQL (Root-User login with `root:root`\)

Installation
------------

1.	Download or Clone this repo
2.	Add a new hosts entry (on Linux to **/etc/hosts**) `192.168.33.99 seagullframework.dev www.seagullframework.dev php56.seagullframework.dev www.php56.seagullframework.dev`
3.	Open your terminal, navigate to this folder and start vagrant with `vagrant up`
4.	Open your browser and go to `http://localhost:8080` or `http://php56.seagullframework.dev`

Usage
-----

See vagrant documentation.

Configuration
-------------

Take a look at `Vagrantfile` and `puphpet/config.yml` to change vm definition. After changes reload your VM with `vagrant reload --provision`.

XDebug is setup to work with PhpStorm. You could change XDebug settings in `puphpet/config.yml` and reload your VM with `vagrant reload --provision`.

License
-------

MIT
