<h1 align="center">FunPay Vertex</h1>
<h4 align="center">Простой и эффективный бот для автоматизации FunPay</h4>

<h1 align="center">
    <img src="https://i.ibb.co/Sc5mL1G/Screenshot-141.png">
</h>

<h2 align="center">Перед началом настоятельно рекомендую залететь в наш <a href="https://t.me/funpayplace">Telegram чат</a> и <a href="https://dsc.gg/funpay">Discord сервер</a>. Тут и поможем чем сможем и посидеть можно.</h2>

## :clipboard: **Содержание**

- [Возможности](#robot-возможности)
  - [FunPay](#shopping_cart-funpay)
  - [Уведомления и ПУ в Telegram](#left_speech_bubble-уведомления-и-пу-в-telegram)
  - [Дополнительные возможности](#gear-дополнительные-возможности)

- [Преимущества](#1st_place_medal-преимущества)
  - [Для пользователей](#grinning-для-пользователей)
  - [Для разработчиков](#computer-для-разработчиков)

- [Установка](#arrow_down-установка)
  - [Windows](#large_blue_diamond-windows)
  - [Linux (Ubuntu)](#hotsprings-linux-ubuntu)
- [Настройка конфигов](#hammer_and_wrench-настройка-конфигов)
- [Мне нужна помощь](#question-мне-нужна-помощь)
- [Понравилось приложение?](#tada-Понравилось-приложение)


## :robot: **Возможности**

### :shopping_cart: **FunPay**

- Автовыдача товаров.
- Автоподнятие лотов.
- Автоответ на заготовленные команды.
- Автовосстановление лотов после продажи.
- Автодеактивация лотов, если товары закончились.
- Вечный онлайн.
- Уведомления в телеграм.
- Полноценная ПУ в Telegram.

### :left_speech_bubble: **Уведомления и ПУ в Telegram**

- Возможность установки нескольких чатов для уведомлений.
- Уведомления о поднятии лотов.
- Уведомления о новых заказах.
- Уведомления о выдаче товара.
- Уведомления о новых сообщениях
- Возможность отвечать на сообщения прямо из Telegram.
- Возможность полностью настраивать автовыдачу / автоответчик и все остальные модули.
- Возможность добавлять автовыдачу для лотов, получая лоты пряма с FunPay.

### :gear: **Дополнительные возможности**

- Использование переменных в тексте для автоответа / автовыдачи.

## :1st_place_medal: **Преимущества**

### :grinning: **Для пользователей**

- **Больше**, чем наличие самого нужного функционала.
- **Оптимизация**. _20 МБ свободного места на диске, до 50 МБ ОЗУ, доступ в интернет_ - все что нужно для работы.
- Возможность установить на **любую платформу**, которую поддерживает _Python: Windows, Linux, IOS, Android_ и т.д.
- Гибкие и при этом простые конфиги, написанные в INI-формате.
- Постоянные обновления, быстрое реагирования на баги / предложения о новом функционале.
- Полное управление через Telegram.

### :computer: **Для разработчиков**

- Выбран самый простой и при этом один из самых мощных языков для такого рода приложений - _Python_.
- Полная документация кода. Все классы / методы / функции имеют док-строки, type-хинты.
- Широкое использование ООП. Почти каждый эвент / сообщение / заказ и т.д. представляют собой экземпляр соответствующего класса, а не просто набор данных в JSON.
- Сконфигурированный логгер. Никаких принтов!
- Собственный Python-пакет FunPayAPI, который никак не привязан к FunPay Vertex.

## :arrow_down: Установка

### :large_blue_diamond: Windows

1. Скачайте и установите [Python](https://www.python.org/ftp/python/3.11.0/python-3.11.0-amd64.exe).
   1. При установке поставьте галочку у `Add python.exe to PATH` на первом экране установки.
2. Скачайте FunPay Vertex.
3. Перенести папку `FunPayVertex-main` в нужное вам место.
4. Перейдите в папку `FunPayVertex-main`.
5. В адресной строке введите `cmd` и нажмите `Enter`.
6. В открывшейся командной строке введите `python setup.py`. Дождитесь окончания загрузки пакетов.
7. Закройте командную строку, настройте конфиги и запустите файл `Start.bat`.

### :hotsprings: Linux (Ubuntu)

1. Выполните команду:
`wget https://raw.githubusercontent.com/NightStrang6r/FunPayVertex/main/linux-install.sh -nc && bash linux-install.sh`
2. Следуйте инструкциям установщика.

Данный скрипт автоматически установит всё необходимое и запустит бота как фоновый процесс.

## :hammer_and_wrench: Настройка конфигов

1. Все конфиги находятся в папке `configs`
2. Все инструкции по настройке конфигов находятся внутри самих конфигов.
3. Основной конфиг со всеми переключателями: `configs/_main.cfg`
4. Конфиг автоответчика: `configs/auto_response.cfg`
5. Конфиг автовыдачи: `configs/auto_delivery.cfg`

## :question: Мне нужна помощь
Если у вас остались какие-либо вопросы, мы с радостью ответим на них в нашем [Discord канале](https://dsc.gg/funpay).

## :tada: Понравилось приложение?

Оцените данный репозиторий, поставив звёздчку в верхнем правом углу страницы на GitHub (нужно быть авторизованным в свой аккаунт). Это даёт мне мотивацию развивать данный проект.

![](https://i.ibb.co/x3hFFvf/2022-08-18-132617815.png)

Вы также можете поддержать разработчика материально, чтобы ускорить выход будущих обновлений:

- [Monobank](https://send.monobank.ua/jar/7fiVkcrWYv)
- [DonationAlerts](https://www.donationalerts.com/r/nightstranger)
- [ЮMoney](https://yoomoney.ru/to/4100115656349483)
"# PO" 
"# re" 
"# re" 
