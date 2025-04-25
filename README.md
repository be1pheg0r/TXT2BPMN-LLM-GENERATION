# TXT2BPMN-LLM-GENERATION

Бэк модуль LLM генерации BPMN 2.0 диаграмм из текстового запроса.

Как это работает?

Сообщение между агентами реализовано через библиотеку ```langgraph```.
Структура графа выглядит следующим образом:
 
![img](https://sun9-35.userapi.com/s/v1/ig2/WLUONpDKpLWXYAJ_ozp-0UQv_tqWYK9WKdMf5fsfYYO7IoqvM72SLuzq1JHy60YxhDIxRy0HtN30qb73yVPWE8Xo.jpg?quality=95&as=32x41,48x62,72x92,108x139,160x206,240x308,360x462,432x555&from=bu&u=9I2G-lamzBMZ-fT1zjbNKB2zha0qsquJGRuqpW_F2Sw&cs=432x555)

Для инференса **рекомендуется** использовать `mistral-small`, можно доделать до инпута
с изображениями. Также поддерживает локальный инференс через `sentence-transformers` (в коде пример для AWQ LLM)

В данном репозитории просто код, если соберетесь использовать код, то зависимости собирайте сами)