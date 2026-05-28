# 🎫 osTicket Installation Guide

---

# 🖥️ System Requirements

- Ubuntu Server 22.04
- Apache2
- PHP
- MySQL/MariaDB

---

# 📦 Install Dependencies

```bash
sudo apt update && sudo apt upgrade -y
sudo apt install apache2 mysql-server php libapache2-mod-php php-mysql unzip wget -y
```

---

# 🌐 Download osTicket

```bash
wget https://github.com/osTicket/osTicket/releases/download/v1.18.1/osTicket-v1.18.1.zip
unzip osTicket-v1.18.1.zip
```

---

# 📂 Configure Web Directory

```bash
sudo mv upload /var/www/html/osticket
```

---

# 🔐 Set Permissions

```bash
sudo chmod -R 755 /var/www/html/osticket
```

---

# 🗄️ Configure Database

```sql
CREATE DATABASE osticket;
```

---

# 🚀 Start Services

```bash
sudo systemctl restart apache2
sudo systemctl enable apache2
```

---

# 🌍 Access Web Installer

Navigate to:

```text
http://SERVER-IP/osticket
```

---

# ✅ Installation Complete

Configure:
- admin account
- departments
- SLA plans
- agents