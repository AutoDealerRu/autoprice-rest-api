### Для получения ключа авторизации по регистрационным данным необходимо выполнить https запрос:
```bash
curl -H "Content-Type: application/json" \
     -X POST -d '{"login": "<e_mail_прирегистрации>", "password": "<пароль_прирегистрации>"}' \
     https://autoprice.online/auth/api/rest
```
