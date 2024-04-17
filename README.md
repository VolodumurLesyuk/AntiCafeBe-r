# Початок роботи 
Щоб запустити даний продукт потрібно мати усновлений python3.11+ на персональному комп'ютері.
# Запуск проекту
    + Linux
        + python3 -m venv venv
        + source venv/bin/activate
        + pip install -r requirements.txt
        + python manage.py migrate
        + python manage.py runserver
        І заходимо у браузер на порт http://127.0.0.1:8000/

    + Windows
        + python -m venv venv
        + venv\Scripts\activate.bat
        + pip install -r requirements.txt
        + python manage.py migrate
        + python manage.py runserver
        І заходимо у браузер на порт http://127.0.0.1:8000/

### Додаткові налаштування 
1) Щоб створити супер користувача потрібно запустити термінал з увімкненим віртуальним середовищем тобто
щоб у терміналі було надпис віртуалтного середовища
+ (venv) dima@dima-Lenovo-V15-G3-IAP:~/PycharmProjects/AntiCafeBeær$ 
Після чого виконати команди
+ python manage.py createsuperuser
Далі задаємо логін емейл та пароль
Таким чином ми створюємо супер користувача тобіш адміна

