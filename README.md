# util-file-php
[![Build Status](https://travis-ci.org/dominionenterprises/util-file-php.svg?branch=master)](https://travis-ci.org/dominionenterprises/util-file-php)
[![Scrutinizer Code Quality](http://img.shields.io/scrutinizer/g/dominionenterprises/util-file-php.svg?style=flat)](https://scrutinizer-ci.com/g/dominionenterprises/util-file-php/)
[![Coverage Status](https://coveralls.io/repos/dominionenterprises/util-file-php/badge.svg?branch=master&service=github)](https://coveralls.io/github/dominionenterprises/util-file-php?branch=master)

[![Latest Stable Version](http://img.shields.io/packagist/v/dominionenterprises/util-file.svg?style=flat)](https://packagist.org/packages/dominionenterprises/util-file)
[![Total Downloads](http://img.shields.io/packagist/dt/dominionenterprises/util-file.svg?style=flat)](https://packagist.org/packages/dominionenterprises/util-file)
[![License](http://img.shields.io/packagist/l/dominionenterprises/util-file.svg?style=flat)](https://packagist.org/packages/dominionenterprises/util-file)

A collection of general util-fileities for making common programming tasks easier.

## Requirements

util-file-php requires PHP 5.4 (or later).

##Composer
To add the library as a local, per-project dependency use [Composer](http://getcomposer.org)! Simply add a dependency on
`dominionenterprises/util-file` to your project's `composer.json` file such as:

```json
{
    "require": {
        "dominionenterprises/util-file": "~1.0"
    }
}
```
##Documentation
Found in the [source](src) itself, take a look!

##Contact
Developers may be contacted at:

 * [Pull Requests](https://github.com/dominionenterprises/util-file-php/pulls)
 * [Issues](https://github.com/dominionenterprises/util-file-php/issues)

##Project Build
With a checkout of the code get [Composer](http://getcomposer.org) in your PATH and run:

```sh
./build.php
```

There is also a [docker](http://www.docker.com/)-based
[fig](http://www.fig.sh/) configuration that will execute the build inside a
docker container.  This is an easy way to build the application:
```sh
fig run build
```

For more information on our build process, read through out our [Contribution Guidelines](CONTRIBUTING.md).
