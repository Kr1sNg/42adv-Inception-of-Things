# 42adv-Inception-of-Things

Kubernetes from a developer's perspective

## Vagrant

Vagrant is an open-source command-line tool created by HashiCorp for building, configuring, and managing portable virtual machine (VM) development environments.

### Vagrantfile

```
Vagrant.configure("2") do |config|
  config.vm.box = "bento/debian-12"
  config.vm.hostname = "vm1"
  config.vm.network "private_network", ip: "192.168.56.110"
end

```

### Vagrant commands

- `vagrant init bento/debian-13` : initializes a new Vagrant environment by creating a Vagrantfile

- `vagrant up`

- `vagrant status`

- `vagrant ssh`

- `vagrant halt`: stops the vagrant machine

- `vagrant suspend`: hibernate the vagrant machine

- `vagrant destroy`: stops and deletes all traces of the vagrant machine

- `vagrant validate`: validate Vagrantfile

- `vagrant global-status`

## Kubernetes (K8s)

Kubernetes (K8s) is an open-source container orchestration system that automates the deployment, scaling, and management of containerized applications.
