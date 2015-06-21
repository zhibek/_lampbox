_lampbox
========

A base setup for a LAMP-like site, using Vagrant, Chef and Berkshelf.

Installs Nginx, MySQL, Redis, PHP and common dependencies.

Installation
------------

### Clone repo and provision with vagrant:

    git clone --recursive git@github.com:zhibek/_lampbox.git
    cd _lampbox
    vagrant up


### Add the IP to your hosts file:

    10.1.1.40     _lampbox.local


### Access the box:

To access the vagrant environment from the terminal, change to the vagrant directory and type 

    vagrant ssh


### View the site:

Visit [http://_lampbox.local/](http://_lampbox.local/) to view the site.