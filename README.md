# Overview

# Installation for production

TBD

# Installation for development

## Prerequisites

1. Install [VirtualBox and Vagrant](http://docs.vagrantup.com/v1/docs/getting-started/index.html)

2. Run `vagrant plugin install vagrant-salt`

3. Get the Ubuntu 12.04 Precise x86_64 base box: `vagrant box add precise64 http://files.vagrantup.com/precise64.box`

## Host OS steps

From this project's root run:

    ~/Sandbox/template0(master)$ vagrant up

That will provision the development VM start-up. When the provisioning is done, you can ssh into the
guest OS by

    ~/Sandbox/template0(master)$ vagrant ssh

## Running the tests

In the guest OS'es `/vagrant` directory say:

    vagrant@quantal64:/vagrant$ ./vendor/bin/phpunit

# Change log

## v0.0.1 published on YYYY-MM-YY

1. ?
1. ?
