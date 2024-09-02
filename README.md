# reverse.lol
reverse.lol позволяет одной командой опубликовать ваш локальный веб-сервер в мир, без настройки DNS и без статического IP

## Использование
1. Установите reverse.lol глобально, используя NodeJS. Могут потребоваться права администратора. \
```npm install reverselol -g```
2. Запустите туннель. Не забудьте указать порт локального сервера. Например, `3000`. \
```rlol --port 3000```
3. Вы получите случайный URL, который будет работать все время, пока активен туннель. Можете поделиться им или открыть его на телефоне.
```
user@mypc# rlol --port 3000
your url is: https://neat-crabs-care.reverse.lol
```

### Подробная информация доступна на [сайте](https://setup.reverse.lol)

Основано на localtunnel. \
Hosted by [DpkgSoft International Limited](https://dpkgsoft.com)