# NocoDB

Deploy NocoDB on a CentOS/8 Vagrant box using the postgresql docker-compose.yml file.

## Getting Started

These instructions will get you up and running on your local machine for
development and testing purposes.

### Prerequisites

Install Virtualbox https://www.virtualbox.org/ 

Install Vagrant https://www.vagrantup.com/

Install git https://gitforwindows.org/

Clone the repository onto your local machine

```
git clone https://github.com/marvinpac-it/nocodb.git
cd nocodb
```

Provision the virtual machine

```
vagrant up
```

Logon to the VM using `vagrant ssh`.

NocoDB is accessible on the host computer through port 8080

http://localhost:8080

Once you're finished playing with the VM, you can either suspend it (can be restarted with `vagrant up`) or destroy it.

```
vagrant suspend
vagrant destroy
```

