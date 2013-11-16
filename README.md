# soyel.fr website

Based on :

* Symfony 2.3 Standard Edition
* Sonata Project
* KNP Menu Bundle
* FOS User Bundle
* HTML5 Boilerplate
* Normalize CSS
* Bootstrap
* JQuery
* Modernizr
* Markitup!
* And much more...

## Install process

First of all, install needed vendors with [Composer](http://getcomposer.org/).

    php composer.phar update

Get your own parameters.yml

    cd app/config
    mv parameters.yml.dist parameters.yml

Modify the content of the `parameters.yml` file to reflect your needs and then
run these commands :

    php app/console doctrine:database:create
	php app/console doctrine:schema:create
	php app/console assets:install

And everything should be ready to tweak, fork or enhance.

## License

This website source code is under the [WTF Public License][2]. All external
vendors projects are under their own license.

[1]: http://getcomposer.org/
[2]: https://github.com/soyel/soyel.fr/blob/master/LICENSE