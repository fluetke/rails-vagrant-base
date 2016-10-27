# Vagrant VM for starting a Rails Project
This `Vagrantfile` and provisioning script are aimed to have a basic, Ubuntu-based VM using Vagrant for starting a new Rails project.

More information on neurotrophs blog: [https://www.neurotroph.de/2016/04/vagrant-vm-for-starting-a-rails-project/](https://www.neurotroph.de/2016/04/vagrant-vm-for-starting-a-rails-project/)

Edit: I have updated the vagrant scripts to use the official Ubuntu 16.04 LTS vagrant box, which is setup a little different from the standard vagrant setting i.e. there's no vagrant user, instead the user ubuntu is used. --fluetke

## Installation
Clone this repository to your project's directory

	git clone https://github.com/fluetke/rails-vagrant-base.git .

and `vagrant up` your VM.

## Requirements
This `Vagrantfile` has been tested using *Vagrant 1.8.6* and *VirtualBox 5.1.8*.

## Configuration
Out-of-the-box you will get *Ruby 2.3.1* and *Rails 5.0.0.1*. You can configure your preferred versions in the `vagrant.bootstrap.sh` script by setting the variables in the beginning of the file, e.g.:

	RUBY=2.2.0
	RAILS=4.2.6

## License
No license. Just use it, change it, fork it, modify it, sell it, whatever... I hope this saves you some time. If you find any errors or bugs, please create an issue at GitHub. Thanks.
