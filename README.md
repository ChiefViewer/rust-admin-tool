# RustAT

RustAT - панель администратора для серверов Rust. Делал её для себя: надоело
держать открытыми кучу окон - консоль, игроки, чат, плагины - всё собрал в
одном месте.

Работает на Windows 10/11, распространяется одним exe-файлом, устанавливать
ничего не нужно.

## Что умеет

- Несколько серверов одновременно: добавляете слоты и переключаетесь между
  ними в один клик.
- Режим сетки (F12): все подключённые серверы в одном окне ячейками, в каждой
  половине ячейки - чат, консоль, список игроков или информация о сервере
  (кадры, память, аптайм, сущности). Быстрые сообщения и команды, есть
  кнопка «Управление всеми» - одна команда сразу на все серверы.
- Консоль RCON с сохранённой историей, шаблонами команд и набором быстрых
  кнопок.
- Игроки онлайн в реальном времени: кто зашёл, кто вышел, страна по IP,
  быстрые действия со списком.
- Чат сервера - виден сразу, отправлять сообщения можно прямо отсюда.
- Справа всегда видно состояние сервера: версия, Oxide или Carbon, сколько
  плагинов загружено и какие из них упали (список ошибок копируется в буфер
  одним нажатием).
- Уведомления о событиях: всплывающие окна, звуки, тосты Windows - состав
  настраивается под себя.
- Вкладка «Файлы»: работа с файлами сервера по FTP прямо в панели, загрузка
  обычным перетаскиванием.
- Для своего сервера есть отдельный менеджер: запуск и остановка, расписание
  рестартов и вайпов с предупреждением игроков, бэкапы, обновление модов и
  плагинов, права и группы, редактирование server.cfg.
- Несколько тем оформления, интерфейс на русском и английском.
- REST API на localhost для автоматизации и поддержка прокси.

## Скачивание

Свежая версия лежит в телеграм-канале, ссылка на файл - в закрепе:

https://t.me/rustadmintool

Внутри программы есть встроенная проверка обновлений, так что внимательно
следить за каналом не обязательно - программа сама скажет, что вышла новая
версия.

## Как начать

1. Скачайте RustAT.exe из канала и просто запустите.
2. Меню «Файл → Добавить сервер»: адрес, RCON-порт (обычно 28016) и
   RCON-пароль.
3. Нажмите «Подключить» - дальше всё будет в одном окне.

На сервере должен быть включён RCON (в командной строке стоят
`+rcon.web 1`, `+rcon.port` и `+rcon.password`). Если сервер свой, проще
всего завести его через мастер установки - он настроит всё сам.

## Телеграм

Канал - https://t.me/rustadmintool: новости, релизы, ссылка на скачивание.

---

# RustAT

RustAT is an admin panel for Rust servers. I made it for myself: I got tired
of keeping a dozen windows open - console, players, chat, plugins - so I put
everything in one place.

Runs on Windows 10/11, ships as a single exe file, nothing to install.

## Features

- Several servers at once: add slots and switch between them in one click.
- Grid mode (F12): all connected servers in one window as cells, each cell
  half showing chat, console, player list or server info (FPS, RAM, uptime,
  entities). Quick messages and commands, plus a "Manage All" button to send
  one command to every server at once.
- RCON console with saved history, command templates and quick-action buttons.
- Live player list: who joined, who left, country by IP, quick actions on the
  list.
- Server chat right there - you can read it and send messages from the same
  window.
- The pane on the right always shows server state: version, Oxide or Carbon,
  how many plugins are loaded and which ones failed (the error list copies to
  clipboard in one click).
- Event notifications: popups, sounds, Windows toasts - the set is
  configurable.
- Files tab: work with server files over FTP right in the panel, upload by
  simple drag and drop.
- For your own server there is a separate manager: start and stop, restart
  and wipe schedule with player warnings, backups, mod and plugin updates,
  permissions and groups, server.cfg editing.
- Several themes, interface in Russian and English.
- REST API on localhost for automation and proxy support.

## Download

The latest version lives in the Telegram channel, the link to the file is in
the pinned post:

https://t.me/rustadmintool

The app has a built-in update check, so you don't have to watch the channel
closely - it will tell you itself when a new version is out.

## Getting started

1. Download RustAT.exe from the channel and just run it.
2. Menu "File → Add Server": address, RCON port (usually 28016) and RCON
   password.
3. Click "Connect" - everything else happens in one window.

RCON must be enabled on the server (`+rcon.web 1`, `+rcon.port` and
`+rcon.password` in the command line). If the server is yours, the easiest
way is to create it with the install wizard - it configures everything
itself.

## Telegram

Channel - https://t.me/rustadmintool: news, releases, download link.
