# GetBrand Role Service Documentation

## Permission

- ##### GET /api/permission/ - получение всего списка разрешений.
###### Логика работы - N/A
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - N/A
###### Тело ответа - 
```js
[
    {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "resource": "string",
      "action": "string",
      "attributes": "string",
      "role": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "rolesForUser": "string",
        "addAutomaticly": true
      }
    }
]
```
###### Исключения - 
###### ***InternalErrorException***
---
- ##### GET /api/permission/{permissionId} - получение разрешения по ID.
###### Логика работы - находит в базе данных разрешение в соответствиии с переданным ID с помощью ***permissionId***.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***permissionId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "resource": "string",
    "action": "string",
    "attributes": "string",
    "role": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "rolesForUser": "string",
        "addAutomaticly": true
    }
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### POST /api/permission/ - создание разрешения.
###### Логика работы - создает разрешение в соответствии с телом запроса и сохраняет ее.
###### Тело запроса -
```js
{
  "roleId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "resource": "string",
  "action": "string",
  "attributes": "string"
}
```
###### Параметры запроса - N/A
###### PATH параметры - N/A
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "resource": "string",
    "action": "string",
    "attributes": "string",
    "role": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "rolesForUser": "string",
        "addAutomaticly": true
    }
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/permission/{permissionId} - обновление разрешения.
###### Логика работы - находит разрешение в соответствии с ID переданным через ***permissionId***, обновляет его в соответствии с телом запроса и сохраняет.
###### Тело запроса -
```js
{
  "roleId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "resource": "string",
  "action": "string",
  "attributes": "string"
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***permissionId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "resource": "string",
    "action": "string",
    "attributes": "string",
    "role": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "rolesForUser": "string",
        "addAutomaticly": true
    }
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### DELETE /api/permission/{permissionId} - удаление разрешения.
###### Логика работы - находит в базе данных разрешение в соответствиии с переданным ID с помощью ***permissionId*** и удаляет его.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***permissionId - UUID***
###### Тело ответа - 
```js
boolean
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***