# Overview

# Installation for production

TBD

# Installation for development

## Prerequisites

1. Install [VirtualBox and Vagrant](http://docs.vagrantup.com/v1/docs/getting-started/index.html)

2. Run `vagrant plugin install vagrant-salt`

5. Get the Ubuntu 12.10 Quantal x86_64 base box: `vagrant box add quantal64
   https://github.com/downloads/roderik/VagrantQuantal64Box/quantal64.box`

## Host OS steps

From this project's root run:

    ~/Sandbox/template0(master)$ vagrant up

That will provision the development VM start-up. When the provisioning is done, you can ssh into the
guest OS by

    ~/Sandbox/template0(master)$ vagrant ssh

and [continue the installation there](http://memegenerator.net/instance/33516935).

## Guest OS steps

    vagrant@quantal64:~> cd /vagrant
    vagrant@quantal64:/vagrant> ./guest_os_install.sh

# Change log

## v0.0.1 published on YYYY-MM-YY

1. ?
1. ?
