# GetBrand Order Service Documentation

## Order State

- ##### GET /api/order-state/ - получение всего списка статусов заказа.
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
      "from": [
        "string"
      ],
      "to": "string",
      "auto": true,
      "changeAllow": true,
      "deleteAllow": true
    }
]
```
###### Исключения - 
###### ***InternalErrorException***
---
- ##### GET /api/order-state/{orderStateId} - получение статуса заказа по ID.
###### Логика работы - находит в базе данных статус заказа в соответствиии с переданным ID с помощью ***orderStateId***.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***orderStateId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "from": [
      "string"
    ],
    "to": "string",
    "auto": true,
    "changeAllow": true,
    "deleteAllow": true
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### POST /api/order-state/ - создание статуса заказа.
###### Логика работы - создает статус заказа в соответствии с телом запроса и сохраняет его.
###### Тело запроса -
```js
{
  "name": "string",
  "from": "string",
  "to": "string",
  "auto": true,
  "changeAllow": true,
  "deleteAllow": true
}
```
###### Параметры запроса - N/A
###### PATH параметры - N/A
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "from": [
      "string"
    ],
    "to": "string",
    "auto": true,
    "changeAllow": true,
    "deleteAllow": true
  }
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/order-state/{orderStateId} - обновление статуса заказа.
###### Логика работы - находит лояльность в соответствии с ID переданным через ***orderStateId***, обновляет его в соответствии с телом запроса и сохраняет.
###### Тело запроса -
```js
{
  "name": "string",
  "from": "string",
  "to": "string",
  "auto": true,
  "changeAllow": true,
  "deleteAllow": true
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***orderStateId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "from": [
      "string"
    ],
    "to": "string",
    "auto": true,
    "changeAllow": true,
    "deleteAllow": true
  }
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### DELETE /api/order-state/{orderStateId} - удаление стаутса заказа.
###### Логика работы - находит в базе данных лояльность в соответствиии с переданным ID с помощью ***orderStateId*** и удаляет его.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***orderStateId - UUID***
###### Тело ответа - 
```js
boolean
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***