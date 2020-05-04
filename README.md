# PHP continuous integration tools

[![Minimum PHP Version](https://img.shields.io/badge/php-%3E%3D%207.2-8892BF.svg?style=flat-square)](https://php.net/)
[![Build Status](https://travis-ci.org/adlacruzes/php-ci-tools.svg?branch=master)](https://travis-ci.org/adlacruzes/php-ci-tools)
                 
PHP continuous integration tools is a library with the latest versions of my favorite PHP tools.

## Requirements

PHP needs to be a minimum version of PHP 7.2.

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

| Command                    | Version     | Phar   | Link
| ---                        | :---:       | :---:  | --- |
| composer-normalize         | 2.5.1       | ✓      | https://github.com/ergebnis/composer-normalize
| composer-require-checker   | 2.1.0       | ✓      | https://github.com/maglnet/ComposerRequireChecker
| infection                  | 0.15.3      | ✓      | https://github.com/infection/infection
| php-cs-fixer               | 2.16.3      | ✓      | https://github.com/FriendsOfPHP/PHP-CS-Fixer
| php-parallel-lint          | master      | ✓      | https://github.com/JakubOnderka/PHP-Parallel-Lint
| phpcbf                     | 3.5.5       | ✓      | https://github.com/squizlabs/PHP_CodeSniffer
| phpcs                      | 3.5.5       | ✓      | https://github.com/squizlabs/PHP_CodeSniffer
| phpstan                    | 0.12.20     |        | https://github.com/phpstan/phpstan
| security-checker           | 6.0.3       | ✓      | https://github.com/sensiolabs/security-checker
