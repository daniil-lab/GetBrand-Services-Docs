# GetBrand Company Service Documentation

## Company Tarif

- ##### GET /api/tarif/ - получение всего списка тарифов.
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
      "systemName": "string",
      "description": "string",
      "picture": "string",
      "value": 0,
      "activationPrice": 0
    }
]
```
###### Исключения - 
###### ***InternalErrorException***
---
- ##### GET /api/tarif/{tariffId} - получение тарифа по ID.
###### Логика работы - находит тариф внутри базы данных в соответствии с полученным ID с помощью ***tariffId***.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
##### ***tariffId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "systemName": "string",
    "description": "string",
    "picture": "string",
    "value": 0,
    "activationPrice": 0
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
---
- ##### POST /api/tarif/ - создание тарифа.
###### Логика работы - создает тариф в соответствии с телом запроса и сохраняет его в базу данных.
###### Тело запроса - 
```js
{
  "name": "string",
  "systemName": "string",
  "description": "string",
  "picture": "string",
  "activationPrice": 0,
  "value": 0
}
```
###### Параметры запроса - N/A
###### PATH параметры - N/A
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "systemName": "string",
    "description": "string",
    "picture": "string",
    "value": 0,
    "activationPrice": 0
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***InvalidDataException***
---
- ##### PATCH /api/tarif/{tariffId} - обновление тарифа.
###### Логика работы - обновляет тариф в соответствии с телом запроса и сохраняет его в базу данных.
###### Тело запроса - 
```js
{
  "name": "string",
  "systemName": "string",
  "description": "string",
  "picture": "string",
  "activationPrice": 0,
  "value": 0
}
```
###### Параметры запроса - N/A
###### PATH параметры -
##### ***tariffId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "systemName": "string",
    "description": "string",
    "picture": "string",
    "value": 0,
    "activationPrice": 0
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### DELETE /api/tarif/{tariffId} - удаление тарифа.
###### Логика работы - удаляет тариф из базы данных.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры -
##### ***tariffId - UUID***
###### Тело ответа - 
```js
boolean
```
###### Исключения - 
###### ***InternalErrorException***
###### ***InvalidDataException***
###### ***NotFoundException***
---