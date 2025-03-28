![Main Kittygram workflow](https://github.com/KlyuevAleksandr/kittygram_final/actions/workflows/main.yml/badge.svg)


# Контейнеры и CI/CD для Kittygram


## <summary>Описание</summary>
Kittygram — проект для обмена фотографиями любимых CATs.


## <summary>Установка</summary>
Чтобы развернуть проект на локальной машине, необходимо выполнить следующие действия:


Проект находится по ссылке:  https://github.com/KlyuevAleksandr/kittygram_final.git

Клонировать проект:
```green
   git clone git@github.com:KlyuevAleksandr/kittygram_final.git
```

Перейти в директорию проекта: 
```green
   cd kittygram_final
```


Создать виртуальное окружение: 
```green
   python -m venv venv
```

Активировать виртуальное окружение: 
```green
   source venv/Scripts/activate
```

Обновить пакетный менеджер: 
```green
   python -m pip install --upgrade pip
```

Установить зависимости: 
```green
   pip install -r requirements.txt
```

Выполнить миграции пректа: 
```green
   python manage.py migrate
```

Запустить проект: 
```green
   python manage.py runserver
```



Проект расположен на сервере и работает 24/7.

Для просмотра проекта необходимо перейти по адресу: https://aleksandr89.ddns.net/


## <summary>CTEK технологии(requirements.txt)</summary>
- Django==3.2.3
- djangorestframework==3.12.4
- djoser==2.1.0
- webcolors==1.11.1
- psycopg2-binary==2.9.3
- Pillow==9.0.0
- pytest==6.2.4
- pytest-django==4.4.0
- pytest-pythonpath==0.7.3
- PyYAML==6.0
- python-dotenv==1.0.1

Также:
- Python == 3.10.12
- Gunicorn == 20.1.0
- Nginx
- Docker
- PostgreSQL


## <summary>Автор</summary>
https://github.com/KlyuevAleksandr 
