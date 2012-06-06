Set up a PHP development box super fast
=======================================

Installation
------------

* Install vagrant using the installation instructions in the [Getting Started document](http://vagrantup.com/v1/docs/getting-started/index.html)
* Add a Ubuntu Precise box using the [available official boxes](https://github.com/mitchellh/vagrant/wiki/Available-Vagrant-Boxes), for example: ```vagrant box add precise64 http://files.vagrantup.com/precise64.box```
* Clone this repository
* Run ```vagrant init precise64``` for a single time (use choosen box name) inside the cloned repository
* After running ```vagrant up``` the box is set up using Puppet
* You should now have your working nginx pointing to the www directory as document root under http://localhost:9090/ (showing phpinfo() ouput actually)

Installed components
--------------------

* [Nginx](http://nginx.org)
* [php-fpm](http://php-fpm.org)
* git
* [Composer](http://getcomposer.org/)

