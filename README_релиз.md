# Gummy Froggy — релиз v0.40.6

Папка готова к выкладке: index.html + assets (только то, что использует игра).

## 1. GitHub Pages (5 минут, один раз)
1. Зайди на github.com → «New repository». Имя: `gummy-froggy`, Public, без README.
2. На странице пустого репозитория: «uploading an existing file» → перетащи ВСЁ содержимое этой папки (index.html, папку assets, .nojekyll) → «Commit changes».
3. Settings → Pages → Source: «Deploy from a branch», Branch: `main`, папка `/ (root)` → Save.
4. Через 1–2 минуты игра будет по адресу `https://ТВОЙ-ЛОГИН.github.io/gummy-froggy/`. Открой его на компьютере и телефоне.

Обновление: в репозитории «Add file → Upload files» → перетащить новые файлы с заменой.

## 2. Telegram (Mini App)
1. В Telegram открой @BotFather → `/newbot` → имя «Gummy Froggy», логин бота, например `GummyFroggyBot`.
2. `/newapp` → выбери бота → название, описание, картинка 640×360 → ссылка: адрес из шага 1.4 → короткое имя, например `play`.
3. Ссылка на игру для друзей: `https://t.me/ЛОГИН_БОТА/play`.
4. По желанию: `/mybots` → бот → Bot Settings → Menu Button → та же ссылка — кнопка «Играть» в чате с ботом.

Токен бота никому не присылай (в том числе мне) — для Mini App он не нужен.

## Что где хранится
Прогресс (монеты, альбом, рекорд, громкость) — в памяти браузера/Telegram на устройстве игрока. Теряется при очистке данных браузера или на другом устройстве.
