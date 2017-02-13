### Для получения ключа авторизации по регистрационным данным необходимо выполнить https запрос:
```bash
curl -H "Content-Type: application/json" \
     -X POST -d '{"login": "<e_mail_при_регистрации>", "password": "<пароль_при_регистрации>"}' \
     https://autoprice.online/auth/api/rest
```
