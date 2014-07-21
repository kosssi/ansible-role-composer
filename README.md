# ansible-role-composer

[![Build Status](https://travis-ci.org/kosssi/ansible-role-composer.svg?branch=master)](https://travis-ci.org/kosssi/ansible-role-composer)

Installs Composer, the PHP Dependency Manager.

## Requirements

- php (version 5.3+) should be installed.

## Role Defaults Variables

    composer_path: /usr/local/bin/composer
    composer_update: true
    composer_update_day: 20

The path where composer will be installed and available to your system. Should be in your user's `$PATH` so you can run
commands simply with `composer` instead of the full path.

## Example Playbook

      roles:
        - { role: kosssi.composer }

## Vagrant

If you have vagrant, you can test this role:

    cd tests
    vagrant up

## License

MIT
