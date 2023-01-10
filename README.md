## Описание проекта
Приложение для Благотворительного фонда поддержки котиков QRKot.
Фонд собирает пожертвования на различные целевые проекты: на медицинское обслуживание нуждающихся хвостатых, на обустройство кошачьей колонии в подвале, на корм оставшимся без попечения кошкам — на любые цели, связанные с поддержкой кошачьей популяции.

## Заполнение .env файла

Пример заполнения **.env** файла находится в файле **.env.example**

## Запуск проекта
1. Клонировать репозиторий:

2. Создать и активировать виртуальное окружение:
```bash
python3 -m venv venv

bash/zsh
source venv/bin/activate

Windows:
venv\Scripts\activate.bat
```

3. Обновить pip и установить зависимости из ```requirements.txt```
```bash
python3 -m pip install --upgrade pip

pip install -r requirements.txt
```

4. Создать и заполнить файл **.env**:

```bash
touch .env
```

5. Выполнить миграции:
```bash
alembic upgrade head
```

6. Запустить проект:
```bash
uvicorn app.main:app
```

После запуска проект будет доступен по адресу: http://127.0.0.1:8000

Документация к API досупна по адресам:
- Swagger: http://127.0.0.1:8000/docs
- Redoc: http://127.0.0.1:8000/redoc


## Используемые технологии
:snake: Python 3.9, :incoming_envelope: FastAPI 0.78.0, :busts_in_silhouette: FastAPI-Users 10.0.4, :recycle: Pydantic 1.9.1, :package: SQLAlchemy 1.4.36, :notebook: aiosqlite 0.17.0, :memo: Alembic 1.7.7, :white_check_mark: Flake8 4.0.1

### Автор
PAvel Filipovich
### Email
pf1860525@gmail.com
