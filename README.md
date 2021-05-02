# Ansible CIS Benchmark for Ubuntu Linux 20.04 LTS

[Ansible](https://www.ansible.com/) role for auditing and hardening [Ubuntu 20.04 LTS](https://ubuntu.com/) [Vagrant](https://www.vagrantup.com/) virtual machine based on the [Center for Internet Security (CIS)](https://www.cisecurity.org/) [Benchmark](https://www.cisecurity.org/benchmark/ubuntu_linux/).

## Prerequisites

1. [Vagrant](https://www.vagrantup.com/docs/installation)
2. [Ubuntu 20.04 LTS Vagrant box](https://app.vagrantup.com/ubuntu/boxes/focal64)
3. [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)

## Usage

1. Clone Git repository.
```sh
$ git clone git@github.com:adhipras/ansible-cis-benchmark-ubuntu-20.04.git
```

2. Go to `ansible-cis-benchmark-ubuntu-20.04` directory.
```sh
$ cd ansible-cis-benchmark-ubuntu-20.04
```

3. Create and configure virtual machine.
```sh
$ vagrant up
```

## Disclaimer

There are some sections I skipped because I thought it would be better to be handled manually, for example: disk partitioning.
