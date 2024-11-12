**Установка и базовая настройка Debian**

1.  **Устанавливаем Debian 12.x Bookworm**
    1.  Добавляем репозитории:  
        deb http://deb.debian.org/debian/ bookworm main contrib non-free-firmware non-free deb-src http://deb.debian.org/debian/ bookworm main contrib non-free-firmware non-free
    2.  Устанавливаем дату/время Europe/Moscow и locale ru_RU.UTF-8
        1.  dpkg-reconfigure
        2.  tzdata dpkg-reconfigure locale
    3.   Прописываем сервера точного времени: NTP=10.72.1.2
    4.  Устанавливаем размер системного журнала: SystemMaxUse=100M