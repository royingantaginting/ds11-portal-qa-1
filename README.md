drupal-phing
============

Drupal phing template

## Installation
The following packages need to be installed before using this template. This guide is tested on ubuntu 12.04
1. Install nodejs and npm, sudo apt-get install npm nodejs
2. Install node csslint, sudo npm -g install csslint
3. Install node jshint, sudo npm -g install jshint

## Set up
1. Clone this repository into your machine
2. Put file build.properties and directory build under drupal folder
3. Execute phing target, from drupal directory execute command phing -f build/build.xml
4. All test results will be put under build/tests. Checkstyle, phpmd, php-cpd, phploc, and coder review result will be under build/logs.
