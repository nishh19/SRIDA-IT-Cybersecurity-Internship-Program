# 🛍️ OpenCart Installation Guide

## Version: OpenCart 4.x  
## Stack: LAMP (Linux + Apache + MySQL + PHP)

### Steps:
1. Install LAMP stack:
   ```bash
   sudo apt install apache2 mysql-server php php-mysql php-curl php-zip php-xml php-mbstring
   ```

2. Download OpenCart:
   ```bash
   wget https://github.com/opencart/opencart/releases/download/4.x.x.x/opencart.zip
   unzip opencart.zip -d /var/www/html/opencart
   ```

3. Set permissions and configure DB:
   ```bash
   sudo chown -R www-data:www-data /var/www/html/opencart
   sudo mysql
   > CREATE DATABASE opencart;
   ```

4. Access via browser at `http://localhost/opencart/` to complete installation.

✅ **Status:** OpenCart setup ready
