# PHP continuous integration tools

[![Minimum PHP Version](https://img.shields.io/badge/php-%3E%3D%207.2-8892BF.svg?style=flat-square)](https://php.net/)
[![Build Status](https://travis-ci.org/adlacruzes/php-ci-tools.svg?branch=master)](https://travis-ci.org/adlacruzes/php-ci-tools)
                 
PHP continuous integration tools is a library with the latest versions of my favorite tools.


## Requirements
PHP needs to be a minimum version of PHP 7.2.

## Installation

The recommended way to install is through Composer.

```sh
composer require adlacruzes/php-ci-tools
``` 

## Usage

```sh
vendor/bin/ci-tools COMMAND
```

## Commands

|Command|version| Phar
| ---                        | ---       | --- |
| composer-normalize         | 1.3.1     |     |
| composer-require-checker   | 2.0.0     | ✓   |
| infection                  | 0.14.1    | ✓   |
| php-cs-fixer               | 2.15.3    | ✓   |
| phpcbf                     | 3.5.0     | ✓   |
| phpcs                      | 3.5.0     | ✓   |
| phpstan                    | 0.11.16   |     |
| security-checker           | 6.0       | ✓   |
