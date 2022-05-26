---
title: "Ansible SSH Config Role"
draft: false
type: docs
bookToc: false
---

# 🔌 **SSH** Config Role for Ansible

This role is used to configure SSH for Ansible.


## 📚 Usage

```bash
git submodule add https://github.com/sujaykumarh-ansible/role-ssh.git roles/sujaykumarh.ssh
```

this will make `sujaykumarh.ssh` role available in your playbook.

## 🔧 Configuration Options

these are the default options for this role and can be overridden by the playbook options as required.

```yaml
ssh_install: yes               # should ssh be installed?
```
