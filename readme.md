#User-profiles-and-oauth-authorization

Добавить к прошлому проекту #D4.11 создание пользователей в качестве моделей, для которых нужно использовать встроенные модели Django (django.contrib.auth.models.User), а их профили должны либо создаваться отдельной (самодельной) формой, либо при помощи allauth с авторизацией через github. В любом случае, объекты профилей должны быть экземплярами SocialAccount (allauth). Любая дополнительная информация должна сохраняться в виде словаря (JSON) в поле extra_data.

Требования к проекту указаны в файле "requirements.txt"

Для запуска использовать в консоли команду: "python manage.py runserver"

После запуска сервера, проект будет доступен по адресу http://127.0.0.1:8000/

Панель админа доступна по следующему адресу: http://127.0.0.1:8000/admin

логин длч входа в панель:   1
пароль для входа в панель:  1

Add to the previous project # D4.11 creating users as models for which you need to use the built-in Django models (django.contrib.auth.models.User), and their profiles should either be created in a separate (homemade) form, or using allauth with authorization via github. In any case, the profile objects must be instances of SocialAccount (allauth). Any additional information should be stored as a dictionary (JSON) in the extra_data field.

Project requirements are specified in the "requirements.txt" file

To run, use the command in the console: "python manage.py runserver"

After starting the server, the project will be available at http://127.0.0.1:8000/

The admin panel is available at the following address: http://127.0.0.1:8000/admin

login for entering the panel: 1
password for entering the panel: 1
