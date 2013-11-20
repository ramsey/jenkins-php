# Jenkins Jobs Template PHP Tools

This is a meta package for [Composer](http://getcomposer.org/) that provides the [PHP Quality Assurance Toolchain](http://phpqatools.org/) tools needed for the [Template for Jenkins Jobs for PHP Projects](http://jenkins-php.org/). It provides the following packages:

* [PHPUnit](http://phpunit.de/)
* [phpDocumentor](http://phpdoc.org/)
* [PHP_CodeSniffer](http://www.squizlabs.com/php-codesniffer)
* [PHP Depend](http://pdepend.org/)
* [PHPLOC](https://github.com/sebastianbergmann/phploc)
* [PHP Mess Detector](http://phpmd.org/)
* [Copy/Paste Detector (CPD) for PHP code](https://github.com/sebastianbergmann/phpcpd)

The Template for Jenkins Jobs for PHP Projects uses [phpDox](http://phpdox.de/). However, due to dependency issues, phpDox is not ready for inclusion in this package. Therefore, this package uses [phpDocumentor](http://phpdoc.org/) instead.
