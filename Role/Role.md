# GetBrand Role Service Documentation

## Role

- ##### GET /api/role/ - получение всего списка ролей.
###### Логика работы - N/A
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - N/A
###### Тело ответа - 
```js
[
    {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "name": "string",
      "rolesForUser": "string",
      "addAutomaticly": true
    }
]
```
###### Исключения - 
###### ***InternalErrorException***
---
- ##### GET /api/role/{roleId} - получение роли по ID.
###### Логика работы - находит в базе данных роль в соответствиии с переданным ID с помощью ***roleId***.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***roleId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "rolesForUser": "string",
    "addAutomaticly": true
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### POST /api/role/ - создание роли.
###### Логика работы - создает роль в соответствии с телом запроса и сохраняет ее.
###### Тело запроса -
```js
{
  "name": "string",
  "rolesForUser": "string",
  "addAutomaticly": true
}
```
###### Параметры запроса - N/A
###### PATH параметры - N/A
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "rolesForUser": "string",
    "addAutomaticly": true
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### POST /api/role/{roleId} - обновление роли роли.
###### Логика работы - находит роль в соответствии с ID переданным через ***roleId***, обновляет ее в соответствии с телом запроса и сохраняет.
###### Тело запроса -
```js
{
  "name": "string",
  "rolesForUser": "string",
  "addAutomaticly": true
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***roleId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "rolesForUser": "string",
    "addAutomaticly": true
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### DELETE /api/role/{roleId} - удаление роли.
###### Логика работы - находит в базе данных роль в соответствиии с переданным ID с помощью ***roleId*** и удаляет ее.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***roleId - UUID***
###### Тело ответа - 
```js
boolean
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***