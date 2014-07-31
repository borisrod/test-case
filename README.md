test-case
=========

The AntiMattr test case is a library that provides assistance for PHPUnit.

Installation
============

Use composer to install

```bash
composer install
```

Please use the pre-commit hook to run fix code to PSR standard

Install once with

```bash
./bin/install.sh 
Copying /test-case/bin/pre-commit.sh -> /test-case/bin/../.git/hooks/pre-commit
```

Testing
=======

```bash
$ vendor/bin/phpunit 
```

Code Sniffer and Fixer
======================

```bash
$ vendor/bin/php-cs-fixer fix src/
$ vendor/bin/php-cs-fixer fix tests/
```
