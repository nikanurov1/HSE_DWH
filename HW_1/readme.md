## Домашнее задание №1
Как запустить файл: выполнить в терминал команду `sh docker-init.sh`  
Для подключения к основной бд нужно указать порт 5432, название бд postgres, логин postgres и пароль postgres  
Для подключения к реплике бд нужно указать порт 5433, название бд postgres, логин postgres и пароль postgres  

Во время выполнения скрипта выполняется создание БД, как было указано на картинки в задании, и выполняется подсчет GMV в разрезе магазинов (store_id) и товарных категорий (category_id) путем создания view  
Затем выполняется реплика основной БД  
