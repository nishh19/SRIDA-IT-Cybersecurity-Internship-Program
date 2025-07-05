
#  OpenCart Installation Guide

| **Version** | OpenCart 4.x                         |
|-------------|--------------------------------------|
| **Stack**   | LAMP (Linux + Apache + MySQL + PHP) |

---

## Installation Steps

### 1. Install LAMP Stack

```bash
sudo apt install apache2 mysql-server php php-mysql php-curl php-zip php-xml php-mbstring
````

### 2. Download and Extract OpenCart

```bash
wget https://github.com/opencart/opencart/releases/download/4.x.x.x/opencart.zip
unzip opencart.zip -d /var/www/html/opencart
```

### 3. Set Permissions & Create Database

```bash
sudo chown -R www-data:www-data /var/www/html/opencart
sudo mysql
```

Inside MySQL shell:

```sql
CREATE DATABASE opencart;
EXIT;
```

### 4. Complete Installation via Browser

Open your browser and navigate to:

```
http://localhost/opencart/
```

Follow the GUI installer to finish setting up the store.

---

##  Status

OpenCart installed successfully and ready for testing inside the Ubuntu VM.



