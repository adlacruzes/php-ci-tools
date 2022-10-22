# PHP continuous integration tools

[![Minimum PHP Version](https://img.shields.io/badge/php-%3E%3D%207.4-8892BF.svg?style=flat-square)](https://php.net/)
![Github actions](https://github.com/adlacruzes/php-ci-tools/workflows/Continuous%20Integration/badge.svg?branch=master)
                 
PHP continuous integration tools is a library with the latest versions of my favorite PHP tools.

## Installation

The recommended way to install is through Composer.

```sh
composer require adlacruzes/php-ci-tools
``` 

## Usage

Commands are managed by the vendor command `ci-tools`

```sh
vendor/bin/ci-tools COMMAND
```

## Commands

| Command                  | Version | Link                                               |
|--------------------------|:-------:|:---------------------------------------------------|
| composer-normalize       | 2.15.0  | https://github.com/ergebnis/composer-normalize     |
| composer-require-checker |  3.2.0  | https://github.com/maglnet/ComposerRequireChecker  |
| infection                | 0.24.0  | https://github.com/infection/infection             |
| php-cs-fixer             |  3.0.0  | https://github.com/FriendsOfPHP/PHP-CS-Fixer       |
| phpcbf                   |  3.7.1  | https://github.com/squizlabs/PHP_CodeSniffer       |
| phpcs                    |  3.7.1  | https://github.com/squizlabs/PHP_CodeSniffer       |
| phpstan                  | 0.12.93 | https://github.com/phpstan/phpstan                 |
