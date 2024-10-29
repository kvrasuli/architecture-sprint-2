# pymongo-api

## Как запустить

Запускаем mongodb и приложение

```shell
docker compose up -d
```

Конфигурируем шардинг и репликацию, наполняем mongodb данными

```shell
./mongo-init.sh
```