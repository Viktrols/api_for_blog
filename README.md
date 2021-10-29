h1>API для блога</h1>
<h2>Краткое описание</h2>
<li>Аутентификация по JWT-токену</li>
<li>Работа со спискомвсех публикаций блога и отдельными постами по id</li>
<li>Работа со списоком всех комментариев и комментариев для публикации по id </li>
<li>Работа с подпичиками</li>
<li>Работа с группами</li>

## Установка проекта

### Клонируйте данный репозиторий
```git clone https://github.com/Viktrols/blog-yatube-yandex-praktikum.git```
### Создайте и активируйте виртуальное окружение
```
python -m venv venv<br>
source ./venv/Scripts/activate  #для Windows
source ./venv/bin/activate      #для Linux и macOS
```
### Установите требуемые зависимости
```
pip install -r requirements.txt
```
### Примените миграции
```
python manage.py migrate
```
### Запустите django-сервер
```
python manage.py runserver
```

### Приложение будет доступно по адресу: http://127.0.0.1:8000/
### Документация API: http://127.0.0.1:8000/redoc/
