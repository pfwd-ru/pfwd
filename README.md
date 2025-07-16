# pfwd

Возможности:
- HTTPs
- Ограничение скорости (`--rate-limit=100`)
- [CORS](#cors)

Для запуска:
- Скачать [pfwd](./pfwd) - сборка под arm
- Выполнить `chmod +x pfwd`
- Выполнить `pfwd --to=google.com`

## CORS

Опции для добавления CORS:
- `--cors` - список разрешенных origins
- `--cors-creds` - добавляет `Access-Control-Allow-Credentials`
- `--cors-pn` - добавляет private network access
