# Shopware 6 production template

This repository contains the production template that enables you to build,
package and deploy Shopware 6 to production shops.

Normally the directories _custom, files and most of the public subfolders_
are excluded - only for this repo I included them.

## Install vendor with composer
````
docker-compose exec shopware bash -l
composer install
````

## Installation and usage instructions

Please refer to the
[documentation](https://developer.shopware.com/docs/guides/installation/community/dockware)
for instructions on how to use this template.
