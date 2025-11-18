Установка PostgreSQL

# Обновление пакетов
sudo apt update

sudo apt upgrade -y

# Установка PostgreSQL
sudo apt install -y postgresql postgresql-contrib

# Запуск и включение PostgreSQL
sudo systemctl start postgresql

sudo systemctl enable postgresql

Установка  Zabbix

# Установка необходимых пакетов
sudo apt install -y wget curl gnupg2

wget https://repo.zabbix.com/zabbix/6.4/debian/pool/main/z/zabbix-release/zabbix-release_6.4-1+debian11_all.deb

sudo dpkg -i zabbix-release_6.4-1+debian11_all.deb

sudo apt update


# Проверка статуса всех служб

sudo systemctl status zabbix-server

sudo systemctl status zabbix-agent

sudo systemctl status apache2

sudo systemctl status postgresql

После выполнения всех команд откркрываем в браузере: http://192.168.85.149/zabbix


<img width="763" height="320" alt="image" src="https://github.com/user-attachments/assets/f96cdc33-77a6-4c4d-b680-47445d75a0b3" />
<img width="748" height="518" alt="image" src="https://github.com/user-attachments/assets/6df3c43a-1ca7-4d31-8920-4c6a97141873" />
<img width="760" height="177" alt="image" src="https://github.com/user-attachments/assets/83458d98-be82-47b9-8389-8e2c67b7341a" />



<img width="754" height="432" alt="image" src="https://github.com/user-attachments/assets/6b28f10d-c8b0-4e8a-b00e-52326e67bb17" />
<img width="751" height="399" alt="image" src="https://github.com/user-attachments/assets/d1933754-cd11-4d4c-b35d-e6ac76be9f29" />
<img width="756" height="400" alt="image" src="https://github.com/user-attachments/assets/85d67ebe-e5eb-4477-bd45-52231bbdaac5" />
