---
title: "Ansible raspberry-pi setup role"
draft: false
type: docs
bookToc: false
---

# 🍓 Ansible raspberry-pi setup role

Ansible Configure Raspberry pi with default setup Role. 

**Whats setup**

* Timezone
* Remove vscode and microsoft keys
* set hostname
* install packages
* setup python
* update and upgrade system
* reboot system if needed

## 📚 Usage

```bash
git submodule add https://github.com/sujaykumarh-ansible/role-pi-setup.git roles/sujaykumarh.pi-setup
```

this will make `sujaykumarh.pi-setup` role available in your playbook.

## 🔧 Configuration Options

these are the default options for this role and can be overridden by the playbook options as required.

```yaml
pi_setup_hostname: raspberrypi      # hostname for the raspberry pi
pi_setup_timezone: Asia/Kolkata     # your timezone

pi_setup_basic_pkgs:                # basic packages to install
    - curl
    - wget
    - git
    - cron
    - nano

## Options Config
pi_setup_update_system: no           # update system
pi_setup_reboot_system: no           # reboot system after update?
pi_setup_update_pkg_cache: no        # update apt pkg list

pi_setup_install_basic_pkgs: yes     # install basic pkgs

pi_setup_set_timezone: yes           # set timezone
pi_setup_set_hostname: yes           # set system hostname
pi_setup_set_default_python: yes     # set default python to python 3
pi_setup_set_default_pip: yes        # set default pip to python3-pip

pi_setup_remove_microsoftkeys: yes   # disable to not remove microsoft keys
```
