---
title: "Ansible Firewall Setup Role"
draft: false
type: docs
bookToc: false
---

# 🧱 **Firewall** Setup Role for Ansible

{{< hint warning >}}
**⚠️ WARNING**  

This role will install and configure [UFW](https://launchpad.net/ufw) to handle incoming traffic.
{{< /hint >}}

Using firewall rules is a good way to ensure that your network is secure and only allow traffic on the ports you need. This role will install and configure UFW to handle incoming traffic, and will allow you to configure the rules you need read configuration options for configuring the rules.

ufw is chosen because it is the most widely used firewall and is the most up to date and reliable. 

additionally you can install [**fail2ban**](http://www.fail2ban.org/wiki/index.php/Main_Page) for additional protection against attacks.

## 📚 Usage

## 🔧 Configuration Options
