# Блогикум - платформа для публикации постов (часть 1)

Проект является начальным этапом разработки сайта Блогикум. 

## Функции проекта

* доступны: лента записей с публикациями пользователей, страницы с информацией 
о проекте и правилами платформы. Также можно открыть отдельную страницу с 
постом, страницу определённой категории.
* подключение к базе данных отсутствует, на главной странице отображаются 
заранее подготовленные посты.

## Стек технологий
* [Python](https://www.python.org/)
* [Django](https://www.djangoproject.com/)
* [HTML](https://developer.mozilla.org/ru/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/ru/docs/Web/CSS)
* [Bootstrap](https://getbootstrap.com/)

## Как развернуть проект
1. Клонируйте репозиторий и перейдите в директорию django_sprint1
```bash
git clone git@github.com:igorKolomitseff/django_sprint1.git
cd django_sprint1
```

2. Создайте виртуальное окружение и активируйте его:
```bash
python3 -m venv venv
source venv/bin/activate  # Для Linux и macOS
source venv/Scripts/activate  # Для Windows
```

3. Обновите pip и установите зависимости проекта:
```bash
python3 -m pip install --upgrade pip
pip install -r requirements.txt
```

4. Перейдите в директорию blogicum и запустите проект:
```bash
cd blogicum/
python3 manage.py runserver
```

Откройте браузер и перейдите по адресу 
[http://127.0.0.1:8000/](http://127.0.0.1:8000/) для доступа главной странице 
проекта


### Автор

[Игорь Коломыцев](https://github.com/igorKolomitseff)