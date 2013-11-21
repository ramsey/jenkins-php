# Jenkins Jobs Template PHP Tools

This is a meta package for [Composer](http://getcomposer.org/) that provides the [PHP Quality Assurance Toolchain](http://phpqatools.org/) tools needed for the [Template for Jenkins Jobs for PHP Projects](http://jenkins-php.org/). It provides the following packages:

* [PHPUnit](http://phpunit.de/)
* [phpDox](http://phpdox.de/)
* [PHP_CodeSniffer](http://www.squizlabs.com/php-codesniffer)
* [PHP_CodeBrowser](https://github.com/Mayflower/PHP_CodeBrowser)
* [PHP Depend](http://pdepend.org/)
* [PHPLOC](https://github.com/sebastianbergmann/phploc)
* [PHP Mess Detector](http://phpmd.org/)
* [Copy/Paste Detector (CPD) for PHP code](https://github.com/sebastianbergmann/phpcpd)
* [phpDocumentor](http://phpdoc.org/)

I recommend including this meta package in your `composer.json` require-dev section:

    php composer.phar require --dev rhumsaa/jenkins-php=~1.2

You'll need to set mimimum-stability to "dev." It sucks, but some of the packages included have dependencies on unstable packages, so this is necessary in order to install all the requirements.
