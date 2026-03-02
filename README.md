# User API Specification

## API Endpoint

### 🔹 Create User
Endpoint : POST /api/users 

Request Body :

```json
{
  "nama" : "Aiskha",
  "usia" : 21
}
```

Response Body (success) :

```json
{
  "status": "success",
  "data": {
    "age": 21,
    "id": "random string",
    "name": "Aiskha"
  }
}
```

![img.png](img.png)


### 🔹 Get All Users
Endpoint : GET /api/users

Response Body (success) :

```json
{
  "status": "success",
  "data": [
    {
      "age": 21,
      "id": "random string",
      "name": "Aiskha Zahwa"
    }
  ]
}
```

![img_3.png](img_3.png)

### 🔹 Update User
Endpoint : PUT /api/users/{id}

Request Body :

``` json
{
  "nama" : "Aiskha Zahwa",
  "usia" : 21
}

```

Response Body (success) :

```json
{
    "status": "success",
    "data": {
    "age": 21,
    "id": "random string",
    "name": "Aiskha Zahwa"
  }
}
```

![img_1.png](img_1.png)

### 🔹 Delete User
Endpoint : DELETE /api/users/{id}

Response Body (success) :

```json
{
"message": "Successfully delete user with id (random string)"
}
```

![img_2.png](img_2.png)

## Dokumentasi API

![img_4.png](img_4.png)
![img_5.png](img_5.png)
![img_6.png](img_6.png)
![img_7.png](img_7.png)
![img_8.png](img_8.png)
