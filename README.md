
# 👤❓ DeanonVoprosy

-> 🇺🇦 [На українській мові](README_UA.md)

📜 Простенький скрипт, позволяющий деанонимизировать человека,
который вам написал анонимное сообщение в таких ботах:
- [@anonimnye_voprosy_bot](https://t.me/anonimnye_voprosy_bot)
- [@anonka_ru_bot](https://t.me/anonka_ru_bot)
- [@questianonbot](https://t.me/questianonbot)

---

[![Как это работает?](https://img.shields.io/badge/%23-Как_это_работает%3F%0A-blue?style=for-the-badge)](#как-это-работает)

[![Предисловие](https://img.shields.io/badge/%23-Предисловие-blue?style=for-the-badge)](#предисловие)

[![Устанвка (Windows)](https://img.shields.io/badge/%23-Установка_(Windows)-black?style=for-the-badge)](#установка-windows)

[![Устанвка (Linux)](https://img.shields.io/badge/%23-Установка_(Linux)-black?style=for-the-badge)](#установка-windows)

[![Устанвка (Android)](https://img.shields.io/badge/%23-Установка_(Android_%2F_Termux)-black?style=for-the-badge)](#установка-android--termux)

[![Устанвка (Android)](https://img.shields.io/badge/%23-Meta_Hacker-red?style=for-the-badge)](#meta-hacker)

---

## Как это работает?

Скриншоты работы скрипта:

<img src="https://github.com/metah4cker/deanonvoprosy/blob/main/screenshots/Screenshot_1.png?raw=true" width="600">

<img src="https://github.com/metah4cker/deanonvoprosy/blob/main/screenshots/Screenshot_2.png?raw=true" width="600">

<img src="https://github.com/metah4cker/deanonvoprosy/blob/main/screenshots/Screenshot_3.png?raw=true" width="600">

❔ Бот передаёт 🆔ID пользователя, который есть у каждого
пользователя телеграмм, внутри скрытых данных кнопки
"📩 Ответить". Это позволяет получить 👤 информацию об этом
пользователе.

❗️ **Есть одно условие:** для того, чтобы скрипт узнал
данные пользователя по 🆔ID, он должен находится в ваших
контактах.

☢️ Такой абьюз возможен с многими подобными ботами,
нужно лишь знать небольшую загвоздку внутреннего
устройства бота. Также вы можете ☢️**подделать 🆔ID**
пользователя, на чъё сообщение вы, якобы, отвечаете.
Таким образом, прислав сообщение совершенно другому
человеку, который о вас, возможно, и не знает. Без
участия его 🔗"ссылки".

## Предисловие

❕ При первом запуске, скрипт попросит вас учётные данные.
🔐**API ID** и 🔐**API HASH**. Следуйте следующей инстркуции,
чтобы получить эти значения:
- Переходим по этой ссылке: https://my.telegram.org. Это
официальный сайт телеграмма где вы можете удалить аккаунт и
получить 🔐**API ID** и 🔐**API HASH** для запуска телеграмм
приложений.
- 🔏 Авторизуемся.
- ➡️ Переходим во вкладку **Apps**.
- ✏️ Создаём приложение. Абсолютно не важно как вы его назовёте
и так далее.
- 🏁 Готово.

📃 Полученные значения вы должны будете ввести по инструкциям
скрипта.

📲 Следуйте инструкциям как установить 📜скрипт. Далее скрипт попросит
вас авторизоваться в ваш телеграмм аккаунт.

## Установка (Windows)

- 🐍 Установите [**Python 3**](https://www.python.org/).
⚠️ **При установке не забудьте отметить галочку**
**Add to PATH**. Это очень важно.
- 🗄 Далее, скачиваем репозиторию [по данной ссылке](https://github.com/metah4cker/deanonvoprosy/archive/refs/heads/master.zip).
- 📦 Распаковываем архив куда вам угодно.
- 📁 Заходим в директорию.
- 🕹 Запускаем install.bat
- 🕔 Дожидаемся сообщения **Done!**. В случае каких либо ошибок,
вы можете обратиться за помощью [здесь](https://github.com/metah4cker/deanonvoprosy/issues)
- 📜 Для работы скрипта, запустите run.bat

## Установка (Linux)

Вы и так должны знать как это делать вручную...

- 🐍 Установите [**Python 3**](https://www.python.org/).
- 🗄 Установите **git** и **curl**.
- 📋 Введите эти команды:
- - 💲 ``git clone https://github.com/metah4cker/deanonvoprosy.git``
- - 💲 ``cd deanonvoprosy``
- - 💲 ``./install.sh``
- 📜 Запустить скрипт можно командой: 💲 ``./run.sh``.

## Установка (Android / Termux)

- 📲 Для начала установите [**Termux**](https://f-droid.org/ru/packages/com.termux/).
- 📱 Запустите **Termux**.
- 📋 Введите следующие команды:
- - 💲 ``pkg update && pkg upgrade``
- - 💲 ``pkg install git python``
- - 💲 ``git clone https://github.com/metah4cker/deanonvoprosy.git``
- - 💲 ``cd deanonvoprosy``
- - 💲 ``./install.sh``
- 📜 Запустить скрипт можно командой: 💲 ``./run.sh``.

<img align="left" width="180" src="https://images.weserv.nl/?url=https://github.com/metah4cker/metah4cker/raw/main/logo.jpg&fit=cover&mask=circle&maxage=7d" />
<h1><strong>META HACKER</strong></h1>

Написано специально для телеграм канала по кибербезопасности **Meta Hacker**.
Подписывайся и изучай кибербезопасность вместе с нами!

(c) *Ведущий канала* **s0meart**

-> https://t.me/metah4cker

# 🇺🇦 Слава Україні!
