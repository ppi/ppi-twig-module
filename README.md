PPI Twig Module
=================

[@php]:     http://php.net/             "PHP: Hypertext Preprocessor"
[@ppi]:     http://ppi.io/              "PPI Framework - The PHP Meta Framework!"
[@twig]:    http://twig.sensiolabs.org/ "The flexible, fast, and secure template engine for PHP"

[Twig][@twig] template engine module for [PPI2][@ppi].

[![Build Status](https://secure.travis-ci.org/ppi/ppi-twig-module.png)](http://travis-ci.org/ppi/ppi-twig-module)

Twig
----

<img src="http://twig.sensiolabs.org/images/twig-logo.png" height="100" />

> Twig is a template language for PHP, released under the new BSD license.

> Twig uses a syntax similar to the Django and Jinja template languages which inspired the Twig runtime environment.

Requirements
------------

* [PHP][@php] 5.3.3 and up
* [PPI Framework 2][@ppi] (2.1.x)

Installation
------------

### 1. Install Composer

If you don't have Composer yet, download it following the instructions on
http://getcomposer.org/ or just run the following command:

``` bash
curl -s http://getcomposer.org/installer | php
```

### 2. Add ppi/twig-module to your composer.json and install it

``` bash
$ php composer.phar require ppi/twig-module dev-master
```

Composer will install the module to your project's `vendor/ppi` directory.

### 3. Enable the module

Enable this module by editing `app/config/modules.yml`:

``` yml
modules:
    - PPI\TwigModule
    # ...
```

License
-------

This module is licensed under the MIT License. See the [LICENSE file](https://github.com/ppi/ppi-twig-module/blob/master/LICENSE) for details.

Authors
-------

* Paul Dragoonis - <paul@ppi.io> ~ [twitter.com/dr4goonis](http://twitter.com/dr4goonis)
* Vítor Brandão - <vitor@ppi.io> ~ [twitter.com/noiselabs](http://twitter.com/noiselabs)

See also the list of [contributors](https://github.com/ppi/ppi-twig-module/contributors) who participated in this project.

Submitting bugs and feature requests
------------------------------------

Bugs and feature requests are tracked on [GitHub](https://github.com/ppi/ppi-twig-module/issues).

About PPI
---------

<img src="https://upload.wikimedia.org/wikipedia/commons/7/7d/Ppi-framework-logo.png" width="74" height="50" />

> PPI is an open source PHP meta-framework. It has taken the good bits from Symfony2, ZendFramework2 & Doctrine2 and combined them together to create a solid and very easy web application framework. It can be considered the boilerplate of PHP frameworks.
