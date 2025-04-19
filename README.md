Установите зависимости: pip install django psycopg2.
Настройте базу данных в settings.py.
Выполните миграции: python manage.py makemigrations и python manage.py migrate.
Запустите сервер: python manage.py runserver.
Перейдите в браузере по адресу http://127.0.0.1:8000/transactions/.
Это базовая структура приложения. Дальше можно добавлять фильтры, валидацию, а также интерфейс с использованием Bootstrap и JavaScript.