## Для получения ключа авторизации по регистрационным данным необходимо выполнить https запрос:

1. method: 
	    POST
2. URL: 
	    https://autoprice.online/auth/api/rest
3. headers:
	    Content-Type: application/json
4. body
	    {
		"login": (e-mail прирегистрации),
		"password": (пароль прирегистрации)
	    }