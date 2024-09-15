# myasterisk
Пробуем собрать полнофункциональную станцию
ubuntu 24.04.1 server

https://docs.asterisk.org/Getting-Started/Installing-Asterisk/Installing-Asterisk-From-Source/What-to-Download/

wget https://downloads.asterisk.org/pub/telephony/asterisk/asterisk-20-current.tar.gz  
tar xzvf asterisk-20-current.tar.gz

Библиотека libpri позволяет Asterisk взаимодействовать с ISDN-соединениями. Вам это понадобится только в том случае,
если вы собираетесь использовать DAHDI с оборудованием интерфейса ISDN (например, карты T1/E1/J1/BRI).  
wget https://downloads.asterisk.org/pub/telephony/libpri/libpri-1-current.tar.gz  
tar xzvf libpri-1-current.tar.gz  
wget https://downloads.asterisk.org/pub/telephony/libpri/libpri-1-current-patch.tar.gz  
tar xzvf libpri-1-current-patch.tar.gz  

Вам потребуется установить DAHDI только в том случае, если вы собираетесь использовать
совместимые с DAHDI аналоговые или цифровые телефонные интерфейсные платы.  
wget https://downloads.asterisk.org/pub/telephony/dahdi-linux/dahdi-linux-current.tar.gz  
tar xzvf dahdi-linux-current.tar.gz  
wget https://downloads.asterisk.org/pub/telephony/dahdi-tools/dahdi-tools-current.tar.gz  
tar xzvf dahdi-tools-current.tar.gz  
wget https://downloads.asterisk.org/pub/telephony/dahdi-linux-complete/dahdi-linux-complete-current.tar.gz  
tar xzvf dahdi-linux-complete-current.tar.gz  
