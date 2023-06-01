# Shopware 6 production template

This repository contains the production template that enables you to build,
package and deploy Shopware 6 to production shops.

## Install Mutagen on your host machine (only for Mac users)
In order to do this you should have *Homebrew* installed on your machine. Execute these two commands in the terminal: 
````
brew install mutagen-io/mutagen/mutagen
brew install mutagen-io/mutagen/mutagen-compose
````
With this installed the command to start the container is:
````
mutagen-compose up
````
or if you prefer to run it as a daemon:
````
mutagen-compose up -d
````
It could take a while on the first start, but after that it should be more performant.

**Happy coding**

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
