### Для получения данных по предложениям поставщика, необходимо:

1. Получить ключ авторизации (инструкция в get_auth_token.md)
2. Выполнить https запрос (пример запроса):
```bash
curl -H "Content-Type: application/json"  \
     -X GET -d '{"Authorization": "<auth_token>"}' \
     'https://autoprice.online/shop/api/rest/numenclatures'
```
