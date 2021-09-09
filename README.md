# Ansible-101
Notes and examples from learning ansible

## Install ansible

1. Create a virtual environment (assuming virtualenv is installed):

```
virtualenv --python=python3 .venv/ansible-101
```

2. activate virtual env:

```
source .venv/ansible-101/bin/activate
```

3. make sure you have python >3.5 and a fairly new version of pip based on python 3.x
```
python --version
pip --version
```
(If `pip` is otherwise use `pip3` instaed of `pip`)

4. Install ansible
```
pip install ansible
```

## Install vagrant for a local inventory of VMs

It's useful to have a local inventory of virtual machines to tryout ansible commands and features. You can also use servers in the cloud but this requires less setup and equally powerful.

The recommended method in the course is to use [vagrant](https://www.vagrantup.com/). Follow the instructions in that site to download and install vagrant.
