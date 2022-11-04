# tubes-pengkom-1
Tugas Besar Pengenalan Komputasi 1: Algoritma dan Pemrograman

Penggunaan teknik-teknik *computational thinking* (*decomposition, abstraction, pattern recognition,* dan *algorithm design*) pada aplikasi *chatbot* [chatbiz.id](https://www.chatbiz.id/en/)

## Command Line Interface
```
python cli.py
```

![cl-interface](https://raw.githubusercontent.com/faizath/tubes-pengkom-1/master/cl-interface.gif)

## Telegram Bot & Analytics Dashboard
### Overview
Telegram Bot

![telegram-bot](https://raw.githubusercontent.com/faizath/tubes-pengkom-1/master/telegram-bot.png)

Analytics Dashboard

![analytics-dashboard](https://raw.githubusercontent.com/faizath/tubes-pengkom-1/master/analytics-dashboard.png)

### Installation
Deployment through caprover
```
git clone https://github.com/faizath/tubes-pengkom-1.git
cd tubes-pengkom-1
caprover deploy -b master
```

Manual deployment
```
git clone https://github.com/faizath/tubes-pengkom-1.git
cd tubes-pengkom-1
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```