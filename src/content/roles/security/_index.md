---
title: "Ansible Security Role"
draft: false
type: docs
bookToc: false
---

# 🛡️ **Security** Role for Ansible

{{< hint danger >}}
**⚠️ IMPORTANT DISCLAIMER**  

**SECURITY OF YOUR SYSTEM IS YOUR RESPONSIBILITY**. This is not a magical role to make your system secure. You should understand the security risks of running a system in a production environment and be prepared to take the necessary steps to secure your system. Use this role as a reference for your own setup.

DO NOT USE THIS ROLE IN ANY ENVIRONMENT WHERE YOU HAVE NOT TESTED IT. DO NOT USE IT UNLESS YOU KNOW WHAT YOU ARE DOING.
{{< /hint >}}

{{< hint warning >}}
**⚠️ WARNING**  

Security is curcial as such the things you build should be secured from possible security holes that may effect you or your client or your organization.
{{< /hint >}}

Read about some of the security best practices via links available on [my notebook](https://notebook.sujaykumarh.com/software/security/?utm_source=ansible-book&utm_medium=link&utm_campaign=security-role).


## 📚 Usage

```bash
git submodule add https://github.com/sujaykumarh-ansible/role-security.git roles/sujaykumarh.security
```

this will make `sujaykumarh.security` role available in your playbook.

## 🔧 Configuration Options

these are the default options for this role and can be overridden by the playbook options as required.

```yaml
security_install: yes               # should security be installed?
```
