# Настройка VSCode для разработки Django

```
git clone ...
```

Устанавливаем `virtualenv`:

```
pip install virtualenv
```

Создаём и активируем виртаульное окружение:

```
virtualenv venv
source venv/Scripts/activate
```

Заходим в VSCode и выбираем интерпретатор: `CTRL+SHIFT+P > Select interpreter > Python 3.9 ('venv')`

Устанавливаем библиотеки:

```
pip install -r requirements.txt
```

Теперь у вас будут подсказки к методам/классам Django и autopep.
