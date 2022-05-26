---
title: "Ansible Cloudflare Tunnel Role"
draft: false
type: docs
bookToc: false
---

# 💂 Cloudflare Tunnel Role for Ansible

This role is used to setup [Cloudflare Tunnel](https://developers.cloudflare.com/cloudflare-one/connections/connect-apps/).



## 📚 Usage

```bash
git submodule add https://github.com/sujaykumarh-ansible/role-cf-tunnel.git roles/sujaykumarh.cf-tunnel
```

this will make `sujaykumarh.cf-tunnel` role available in your playbook.

## 🔧 Configuration Options

these are the default options for this role and can be overridden by the playbook options as required.

```yaml
cf_tunnel_install: yes               # should cf-tunnel be installed?
```
