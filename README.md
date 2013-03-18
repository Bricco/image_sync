image_sync
==========

Drupal module that syncornizing images from production via http

## How to use?

## Checkout the module to your projects module folder.
$ git clone https://github.com/Bricco/image_sync.git 


## Or add it to your make file.

projects[image_sync][type] = "module"
projects[image_sync][download][type] = "git"
projects[image_sync][download][url] = "https://github.com/Bricco/image_sync.git"

## Enable the module
$ drush en image_sync

## Visit the settings page