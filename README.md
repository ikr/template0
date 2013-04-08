# Overview

# Installation for production

TBD

# Installation for development

## Prerequisites

1. Install [VirtualBox and Vagrant](http://docs.vagrantup.com/v1/docs/getting-started/index.html)

2. Run `vagrant gem install vagrant-salt`

5. Get the Ubuntu Server 12.10 amd64 Minimal base box: `vagrant box
   add quantal64 http://goo.gl/wxdwM`

## Host OS steps

From this project's root run:

    deployment(master)$ vagrant up

That will provision the development VM start-up. When the provisioning is done, you can ssh into the
guest OS by

    deployment(master)$ vagrant ssh

and [continue the installation there](http://memegenerator.net/instance/33516935).

## Guest OS steps

    vagrant@aldan:~> cd /vagrant
    vagrant@aldan:/vagrant> ./guest_os_install.sh

# Change log

## v0.0.1 published on YYYY-MM-YY

1. ?
1. ?
