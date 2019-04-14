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

Once the VM has started, vist the following URL to complete the installation:

http://127.0.0.1:8080

## Terms and Privacy

Self-hosted instances of Invoice Ninja are subject to:

Privacy Policy:
https://www.invoiceninja.com/self-hosting-privacy-data-control/

Terms:
https://www.invoiceninja.com/self-hosting-terms-service/

The author of this repository has no association with Invoice Ninja and
has no control over their processing of any data which they collect from
self-hosted instances.

