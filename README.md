# get-to-the-balcony
Игра на Flask под названием "get to the balcony"

Задание: Проект в игровой форме предполагает некую локацию с несколькими комнатами. 
Пользователь может перемещаться в разные стороны: на север, восток, юг или запад. 
Для примера, в начале персонаж может находиться в грязном душном подземелье и и его задача выбраться на балкон.


### Технологии:
![Flask](https://img.shields.io/badge/Flask-2.2.1-green)
![Jinja2](https://img.shields.io/badge/Jinja2-3.1.1-green)

Инструкция по запуску:

1. Клонируем репозиторий.

2. Создаем виртуальное окружение.

3. Активируем виртуальное окружение.

```shell
venv\Scripts\activate
```

4. Устанавливаем все зависимотси из requrements.txt.

```shell
pip install -r requrements.txt
```

5. Запускаем проект, пишем в терминале.

```
cd project/
```

```
set FLASK_APP=app.py  Для Windows
```
ИЛИ
```
export FLASK_APP=app.py  Для Unix-систем

```shell
flask run
```

6. Переходим по ссылке.

```shell
http://127.0.0.1:5000
```