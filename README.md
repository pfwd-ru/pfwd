# pfwd

Возможности:
- HTTPs
- Ограничение скорости (`--rate-limit=100`)
- [CORS](#cors)
- Проверка IP адресов (`--allowed-ips`)
- Установка вебхука для Телеграм бота (`--tg`)

Для запуска:
- Скачать [pfwd](https://github.com/pfwd-ru/pfwd/releases)
- Выполнить `chmod +x pfwd`
- Выполнить `pfwd --to=google.com`

## CORS

Опции для добавления CORS:
- `--cors` - список разрешенных origins
- `--cors-creds` - добавляет `Access-Control-Allow-Credentials`
- `--cors-pn` - добавляет private network access
