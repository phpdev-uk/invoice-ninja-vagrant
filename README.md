# invoice-ninja-vagrant

Vagrant configuration for Invoice Ninja.

## Dependencies

 * Vagrant
 * Ansible

## Usage

To start the VM, run: `vagrant up`. The first time you run this command, Vagrant
may download `ubuntu/bionic64`, which is several hundred megabytes in size.

You may wish to run `vagrant box update` before `vagrant up` to ensure that you
have the latest version of the base box. A new version is released most weeks.
