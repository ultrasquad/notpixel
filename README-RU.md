[![Static Badge](https://img.shields.io/badge/Telegram-Channel-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/hidden_coding)

[![Static Badge](https://img.shields.io/badge/Telegram-Chat-yes?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/hidden_codding_chat)

[![Static Badge](https://img.shields.io/badge/Telegram-Bot%20Link-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/notpixel/app?startapp=f355876562)

# 🎨 АВТО ФАРМ ДЛЯ NOTPIXEL 🎨

> [!WARNING]
> В качестве оплаты за этот скрипт я беру часть ваших рефералов, чтобы убрать это поведение или уменьшить процент рефералов, вы можете настроить эту переменную PERCENT_OF_REFERRALS_FOR_CREATORS_OF_THE_SOFT.


> [!WARNING]
> Я не несу ответственности за ваш аккаунт. Пожалуйста, учитывайте потенциальные риски перед использованием этого бота.

### Форк с другого репозитория [github](https://github.com/vadymfedorets/notpixel) 🎨
### Спасибо [Вадиму](https://github.com/vadymfedorets) за исходники 🚀
### Подписывайтесь на его гитхаб и ставьте звезды на его ботов 🔥

## МОИ ДРУГИЕ БОТЫ

### 💩 [Boinkers](https://github.com/YarmolenkoD/boinkers)
### 🚀 [Moonbix](https://github.com/YarmolenkoD/moonbix)

## Рекомендация перед использованием

# 🔥🔥 Используйте PYTHON версии 3.10 🔥🔥

> 🇪🇳 README in english available [here](README-EN)

## Функционал  
|                  Функционал                   | Поддерживается |
|:---------------------------------------------:|:--------------:|
|                Многопоточность                |       ✅        | 
|           Привязка прокси к сессии            |       ✅        | 
|          Поддержка pyrogram .session          |       ✅        |
| Авто-регистрация аккаунта по вашему реф. коду |       ✅        |
|             Получение X3 Поинтов              |       ✅        |
|                  Авто таски                   |       ✅        |
|                Авто рисование                 |       ✅        |
|                 Авто апгрейд                  |       ✅        |
|               Авто клейм наград               |       ✅        |


## [Настройки](https://github.com/YarmolenkoD/notpixel/blob/main/.env-example/)
|                     Настройки                     |                                                          Описание                                                           |
|:-------------------------------------------------:|:---------------------------------------------------------------------------------------------------------------------------:|
|               **API_ID / API_HASH**               |                     Данные платформы, с которой будет запущена сессия Telegram (по умолчанию - android)                     |
|            **USE_RANDOM_DELAY_IN_RUN**            |                                                     Имя говорит за себя                                                     |
|              **RANDOM_DELAY_IN_RUN**              |                                Рандомная задержка в секундах для ^^^ (по умолчанию - [5, 30]                                |
|             **SLEEP_TIME_IN_MINUTES**             |                        Рандомная задержка в минутах между цыклами (по умолчанию - [20, 40, 60, 80])                         |
|                    **USE_REF**                    |                      Регистрировать ваши аккаунты по вашей реф. ссылке или нет (по умолчанию - False)                       |
|                    **REF_ID**                     |                           Ваш реферальный аргумент (идет после app/startapp? в вашей реф. ссылке)                           |
| **PERCENT_OF_REFERRALS_FOR_CREATORS_OF_THE_SOFT** |                        Процент рефов который будет дан разработчикам этого софта (по умолчанию - 15)                        |
|              **USE_PROXY_FROM_FILE**              |                           Использовать ли прокси из файла `bot/config/proxies.txt` (True / False)                           |
|               **ENABLE_AUTO_TASKS**               |                                 Включить ли автоматическое выполнение тасков (True / False)                                 |
|               **ENABLE_AUTO_DRAW**                |                                  Включить ли автоматическое выполнение игр (True / False)                                   |
|        **UNSAFE_ENABLE_JOIN_TG_CHANNELS**         |          [ИСПОЛЬЗОВАНИЕ СВОЙСТВА НЕ БЕЗОАПАСНО] Включить ли автоматическое подключение к тг каналам (True / False)          |
|              **ENABLE_CLAIM_REWARD**              |                                   Включить ли автоматический збор ревардов (True / False)                                   |
|              **ENABLE_AUTO_UPGRADE**              |                                     Включить ли автоматический апгрейд  (True / False)                                      |
|                  **ENABLE_SSL**                   | Включить проверку ssl сертификатов (думаю может помочь с решением SSL: CERTIFICATE_VERIFY_FAILED ошибки)  (default - False) |
|       **ENABLE_AUTO_JOIN_TO_SQUAD_CHANNEL**       |                              Автоматическое подключение в канал сквада (по умолчанию - False)                               |
|           **ENABLE_AUTO_JOIN_TO_SQUAD**           |                                  Автоматическое подключение в сквад (по умолчанию - True)                                   |
|                  **SQUAD_SLUG**                   |                            Сквад slug [название канала сквада] (по умолчанию - notpixel_raiders)                            |
|               **DISABLE_IN_NIGHT**                |                                      Отсанавливать скрипт ночью (по умолчанию - False)                                      |
|                  **NIGHT_TIME**                   |                       Ночное время в какое скрипт будет остановлен  [от, до] (по умолчанию - [23, 6])                       |

## Быстрый старт 📚

Для быстрой установки и последующего запуска - запустите файл run.bat на Windows или run.sh на Линукс

## Предварительные условия
Прежде чем начать, убедитесь, что у вас установлено следующее:
- [Python](https://www.python.org/downloads/) **версии 3.10**

## Получение API ключей
1. Перейдите на сайт [my.telegram.org](https://my.telegram.org) и войдите в систему, используя свой номер телефона.
2. Выберите **"API development tools"** и заполните форму для регистрации нового приложения.
3. Запишите `API_ID` и `API_HASH` в файле `.env`, предоставленные после регистрации вашего приложения.

## Установка
Вы можете скачать [**Репозиторий**](https://github.com/YarmolenkoD/notpixel) клонированием на вашу систему и установкой необходимых зависимостей:
```shell
git clone https://github.com/YarmolenkoD/notpixel.git
cd notpixel
```

Затем для автоматической установки введите:

Windows:
```shell
run.bat
```

Linux:
```shell
run.sh
```

# Linux ручная установка
```shell
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
cp .env-example .env
nano .env  # Здесь вы обязательно должны указать ваши API_ID и API_HASH , остальное берется по умолчанию
python3 main.py
```

Также для быстрого запуска вы можете использовать аргументы, например:
```shell
~/notpixel >>> python3 main.py --action (1/2)
# Or
~/notpixel >>> python3 main.py -a (1/2)

# 1 - Запускает кликер
# 2 - Создает сессию
```


# Windows ручная установка
```shell
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
copy .env-example .env
# Указываете ваши API_ID и API_HASH, остальное берется по умолчанию
python main.py
```

Также для быстрого запуска вы можете использовать аргументы, например:
```shell
~/notpixel >>> python main.py --action (1/2)
# Или
~/notpixel >>> python main.py -a (1/2)

# 1 - Запускает кликер
# 2 - Создает сессию
```
