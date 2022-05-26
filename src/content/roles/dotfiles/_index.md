---
title: "Ansible Docker Setup Role"
draft: false
type: docs
bookToc: false
---

# 💲 **dotfiles** Setup Role for Ansible

This role will install and configure my [dotfiles](https://github.com/sujaykumarh/dotfiles).

## 📚 Usage

```bash
git submodule add https://github.com/sujaykumarh-ansible/role-dotfiles.git roles/sujaykumarh.dotfiles
```

this will make `sujaykumarh.dotfiles` role available in your playbook.

## 🔧 Configuration Options

these are the default options for this role and can be overridden by the playbook options as required.

```yaml
dotfiles_install: yes               # should dotfiles be installed?

dotfiles_path: ${HOME}/dotfiles     # path to setup dotfiles

dotfiles_user: $(id -u):$(id -g)    # user and group for dotfiles
```
