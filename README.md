Поисковой бот канала *Рекомендации подкастов*
========

Бот для поиска русскоязычных подкастов по ключевым словам. 
Искать можно в Apple Podcasts и Google Podcasts.
Бот выдает до 5 первых результатов ссылкой. 

Installing
----------

Создайте виртуальное окужение:
```
pip install -r requirements.txt
```

И запустите его.

Settings
--------
Создайте файл settings.py и добавьте туда следующие настройки:
```
API_KEY = "API_ключ_от_BotFather"

PROXY = "Данные_прокси"

KEY = "API_ключ_для_СПП"

CSE = "Идентификатор поисковой системы"
```

Подробнее о создании СПП и получении ключа [здесь]
(https://developers.google.com/custom-search/v1/overview)

Launch
------
Для запуска бота в созданном окружении выполнить:
```
python bot.py
```
    
