---
title: "Ansible Docker Setup Role"
draft: false
type: docs
bookToc: false
---

# 🐋 **Docker** Setup Role for Ansible

This role will install and configure [docker](https://docs.docker.com/).

## 📚 Usage

```bash
git submodule add https://github.com/sujaykumarh-ansible/role-docker.git roles/sujaykumarh.docker
```

this will make `sujaykumarh.docker` role available in your playbook.

## 🔧 Configuration Options

these are the default options for this role and can be overridden by the playbook options as required.

```yaml
docker_install: yes                 # should docker be installed?
docker_version: latest              # docker version to install

### docker user
docker_user_create: yes             # should docker user be created?
docker_user_group_create: yes       # should docker group be created?
docker_user_home_create: no         # should docker user home be created?
docker_user_username: docker        # docker user name
docker_user_group: docker           # docker group name
```

<br><br>

**deprecated**: these options are no longer available.

[`docker-compose` is now being deprecated](https://docs.docker.com/compose/#compose-v2-and-the-new-docker-compose-command) and is available in native docker command as `docker compose` since v2 and is recommended for use.

```yaml
### deperacted options
docker_compose_install: no        # should docker-compose be installed?
```
