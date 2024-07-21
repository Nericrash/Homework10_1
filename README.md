# Homework10_1
## Описание:
Проект домашней работы на Python, в котором поэтапно добавляются те или иные функции для тренировки своих навыков программирования. 
В данный момент в наличии функции сортировки словарей по значению ключа state, функция сортировки словарей по дате, 
функции маскировки номера счета и карты, функция работы с датой. Реализованы генераторы для обработки массивов транзакций
Эти генераторы должны позволять финансовым аналитикам быстро и удобно находить нужную информацию о транзакциях и проводить анализ данных.
Дополнительно содержит декоратор для логирования вызова функции и записи ее результата в файл или консоль.
Добавлены функции обрабатывающие транзакции. Есть соответствующие логгеры для файлов: msks.py и utils.py
Реализованы функции чтения csv и xlsx файлов и тесты для них
## Установка:
1. Клонируйте репозиторий
```
git clone https://github.com/Nericrash/Homework10_1.git
```
2. Установите зависимости
```
pip instal -r requirements.txt
```
## Тестирование:
Необходимо установить pytest
poerty add --group dev pytest
poetry add --group dev pytest-cov

Запуск тестирования:
-Откройте окно Edit Configurations
-Выберите pytest
-Укажите директорию с тестами и директорию проекта в целом.

## Авторы:
Яков Исикеев под наставничеством команды онлайн школы SkyPro
