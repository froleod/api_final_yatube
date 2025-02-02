# Описание
Платформа для публикации личных блогов.

# Установка и запуск

Клонировать репозиторий:
```
git clone <https or SSH URL>
```

Перейти в папку проекта:
```
cd api_final_yatube
```

Создать и активировать виртуальное окружение:
```
python -m venv venv
source venv/bin/activate
```

Обновить pip:
```
python -m pip install --upgrade pip
```

Установить зависимости:
```
pip install -r requirements.txt
```

Выполнить миграции:
```
python api_yatube/manage.py migrate
```

Запустить сервер:
```
python api_yatube/manage.py runserver
```