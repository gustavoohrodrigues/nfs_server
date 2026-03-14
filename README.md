# Ansible Role: NFS Server

Automates the installation and configuration of an NFS server.

---

## 📌 Overview

The **nfs_server** role configures a Linux host to act as a Network File System (NFS) server, enabling shared storage across multiple machines in a network.

---

## 🚀 Features

* NFS server installation
* Export configuration
* Shared storage automation
* Infrastructure-ready configuration

---

## 🧰 Requirements

* Ansible >= 2.9
* Linux server supporting NFS

---

## ⚙️ Role Variables

Example configuration:

```yaml
nfs_export_dir: /srv/nfs
nfs_allowed_hosts: "*"
```

---

## ▶️ Example Playbook

```yaml
- hosts: nfs_servers
  become: true
  roles:
    - gustavoohrodrigues.nfs_server
```

---

## 📦 Installation

```bash
ansible-galaxy install gustavoohrodrigues.nfs_server
```

---

## Author

**Gustavo Henrique Rodrigues**

SysAdmin

LinkedIn
https://www.linkedin.com/in/gustavo-henrique-rodrigues-3070a5260

---

## 📜 License

MIT
