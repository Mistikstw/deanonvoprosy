
# 👤❓ DeanonVoprosy

-> [На коцапській мові](README_UA.md)

📜 Простенький скрипт, шо дозволяє деанонімізувати людину,
яка вам написала анонімне повідомленя до таких ботів як:
- [@anonimnye_voprosy_bot](https://t.me/anonimnye_voprosy_bot)
- [@anonka_ru_bot](https://t.me/anonka_ru_bot)
- [@questianonbot](https://t.me/questianonbot)

---

[![Як це працює?](https://img.shields.io/badge/%23-Як_це_працює%3F%0A-blue?style=for-the-badge)](#як-це-працює)

[![Замітка](https://img.shields.io/badge/%23-Замітка-blue?style=for-the-badge)](#замітка)

[![Встановлення (Windows)](https://img.shields.io/badge/%23-Встановлення_(Windows)-black?style=for-the-badge)](#встановлення-windows)

[![Встановлення (Linux)](https://img.shields.io/badge/%23-Встановлення_(Linux)-black?style=for-the-badge)](#встановлення-windows)

[![Встановлення (Android)](https://img.shields.io/badge/%23-Встановлення_(Android_%2F_Termux)-black?style=for-the-badge)](#встановлення-android--termux)

[![Устанвка (Android)](https://img.shields.io/badge/%23-Meta_Hacker-red?style=for-the-badge)](#meta-hacker)

---

## Як це працює?

Скриншоти роботи скрипту:

<img src="https://github.com/metah4cker/deanonvoprosy/blob/main/screenshots/Screenshot_1.png?raw=true" width="600">

<img src="https://github.com/metah4cker/deanonvoprosy/blob/main/screenshots/Screenshot_2.png?raw=true" width="600">

<img src="https://github.com/metah4cker/deanonvoprosy/blob/main/screenshots/Screenshot_3.png?raw=true" width="600">

❔ Бот передає 🆔ID користувача, який є у кожного
користувача телеграмму, всередені прихованих даних кнопки
"📩 Ответить". Це дозволяє дізнатися 👤 інформацію о
цьому користувачі.

❗️ **Є одна умова:** для того, щоб скрипт дізнався
даних користувача по 🆔ID, він повинен бути в ваших
контактах.

☢️ Такий аб'юз можливий з багатьма подібними ботами,
потрібно знати лише невеличку особливість внутрішнього
пристрою бота. Також ви маєте змогу ☢️**підробити 🆔ID**
користувача, на чиє повідомлення ви, нібито, відповідаєте.
Таким чином, надіслав повідомлення цілковито іншій
людині, котра о вас, напевно, і не знає. Без
участі її 🔗"посилання".

## Замітка

❕ При першому запуску, скрипт потребує облікові дані.
🔐**API ID** та 🔐**API HASH**. Дотримуйтесь наступної
інструкції, щоб отримати ці значення:
- Переходимо по цьому посиланню: https://my.telegram.org. Це
офіційний сайт телеграмму, де вы маєте змогу видалити свій
аккаунт або отримати 🔐**API ID** та 🔐**API HASH** для
запуску телеграмм додатків.
- 🔏 Авторизовуємося.
- ➡️ Переходимо до вкладки **Apps**.
- ✏️ Створюємо додаток. Абсолютно не важливо як ви його назвете
і так далі.
- 🏁 Готово.

📃 Отримані значення ви повинні ввести за інструкціями
скрипта.

📲 Виконайте інструкцію по встановленню 📜скрипту. Далі, скрипт попросить
вас авторизуватися у ваш обліковий запис в телеграммі.

## Встановлення (Windows)

- 🐍 Встановіть [**Python 3**](https://www.python.org/).
⚠️ **При встановленні не забудьте відзначити галочку**
**Add to PATH**. Це дуже важливо.
- 🗄 Далі, завантажуємо репозиторій [по цьому посиланню](https://github.com/metah4cker/deanonvoprosy/archive/refs/heads/master.zip).
- 📦 Розпаковуємо архів куди вам завгодно.
- 📁Заходимо до директорії.
- 🕹 Запускаємо install.bat
- 🕔 Чекаємо на повідомлення **Done!**. У разі будь-яких помилок,
ви можете звернутися за допомогою [тут](https://github.com/metah4cker/deanonvoprosy/issues)
- 📜 Для роботи скрипту, запустіть run.bat

## Встановлення (Linux)

Ви повинні знати, як це робити вручну.

- 🐍 Установіть [**Python 3**](https://www.python.org/).
- 🗄 Встановіть **git** та **curl**.
- 📋 Введіть ці команди:
- - 💲 ``git clone https://github.com/metah4cker/deanonvoprosy.git``
- - 💲 ``cd deanonvoprosy``
- - 💲 ``./install.sh``
- 📜 Запустити скрипт можна командою: 💲 ``./run.sh``.

## Встановлення (Android / Termux)

- 📲 Для початку встановіть [**Termux**](https://f-droid.org/ua/packages/com.termux/).
- 📱 Запустіть **Termux**.
- 📋 Введіть наступні команди:
- - 💲 ``pkg update && pkg upgrade``
- - 💲 ``pkg install git python``
- - 💲 ``git clone https://github.com/metah4cker/deanonvoprosy.git``
- - 💲 ``cd deanonvoprosy``
- - 💲 ``./install.sh``
- 📜 Запустити скрипт можна командою: 💲 ``./run.sh``.

<img align="left" width="180" src="https://images.weserv.nl/?url=https://github.com/metah4cker/metah4cker/raw/main/logo.jpg&fit=cover&mask=circle&maxage=7d" />
<h1><strong>META HACKER</strong></h1>

Написано спеціально для телеграм каналу по кібербезпеці **Meta Hacker**.
Підписуйся та вивчай кібербезпеску разом з нами!

(c) *Ведучий каналу* **s0meart**

-> https://t.me/metah4cker

# 🇺🇦 Слава Україні!
