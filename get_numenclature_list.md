### Для получения данных по придложениям поставщика, необходимо:

1. Получить ключ авторизации (описано в в get_auth_token.md)
2. Выполнить https запрос (пример запроса):
```bash
curl -H "Content-Type: application/json"  \
     -X GET -d '{"Authorization": "<auth_token>"}' \
     'https://autoprice.online/api/rest/numenclatures'
```
