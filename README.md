# Tuleap

Deploy Tuleap on a CentOS/8 Vagrant box using the official Tuleap Docker container.

## Getting Started

These instructions will get you up and running on your local machine for
development and testing purposes.

### Prerequisites

Install Virtualbox https://www.virtualbox.org/ 

Install Vagrant https://www.vagrantup.com/

Install git https://gitforwindows.org/

Clone the repository onto your local machine

```
git clone git@github.com:oboudry-mvp/tuleap-on-vagrant.git
cd tuleap-on-vagrant
```

Provision the virtual machine

```
vagrant up
```

Logon to the VM using `vagrant ssh` and run `docker-compose exec web cat /root/.tuleap_passwd` to get the admin password for your Tuleap installation.

Once you're finished playing with the VM, you can either suspend it (can be restarted with `vagrant up`) or destroy it.

```
vagrant suspend
vagrant destroy
```

