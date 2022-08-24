# Users and Posts APIs

## Spring Boot with REST

#### [Notes](NOTES.md)

### APIs

#### GET /healthStatus

- Health Check API
- Returns String response: `status:OK`


#### GET /healthStatusBean
- Health Check API
- Returns JSON response:

```
{"status":"OK"}
```


#### GET /users

- Returns all users.
- Returns JSON response:

```
[
 {"id":1,"name":"Jackson","birthDate":"2022-08-05T18:19:27.767+00:00"},
 {"id":2,"name":"Johnson","birthDate":"2022-08-05T18:19:27.767+00:00"},
 {"id":3,"name":"McDonald","birthDate":"2022-08-05T18:19:27.767+00:00"}]
```

#### GET /users/{id}

- Returns data of single users, else null.
- Returns JSON response:

```
{"id":1,"name":"Jackson","birthDate":"2022-08-06T07:42:11.033+00:00"}
```





