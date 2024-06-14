# Tools-discord-bot

## Создание бота на discord-сервер

1. Создать приложение:
    1. Перейти по ссылке: https://discord.com/developers/applications
    1. В правом верхнем углу нажать кнопку "New Application"
    1. Во всплывшем окошке ввести желаемое название приложения
1. Создать бота:
    1. Перейти в приложение, выбрав его из списка: https://discord.com/developers/applications
    1. Слева нажать на вкладку "Bot", затем нажать кнопку "Add bot"
    1. Сгенерировать токен, нажав кнопку "Regenerate token". Этот токен нужно указать в конфиг-файле [example.env](example.env).
    1. На той же странице, в разделе "Bot Permissions", отметить нужные привелегии, например "Administrator". Изменения необходимо сохранить.

## Установка бота

Создайте виртуальное окружение:

```shell
python -m venv env && . ./env/bin/activate
```

Установите зависимости:

```shell
pip install -r requirements
```

## Добавление бота на discord-сервер

В разделе "Oauth2" нужно выбрать чекбокс "bot", после чего появится ещё один блок чекбоксов, в котором нужно выбрать "Administrator".
Перейдите по появившейся ссылке и выберите сервер для добавления.

## Ссылки

- Документация модуля discord.py:
    https://discordpy.readthedocs.io/en/latest/index.html
- Документация для разработчиков:
    https://discord.com/developers/docs/intro
