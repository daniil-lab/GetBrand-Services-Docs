# GetBrand Loyalty Service Documentation

## Loyalty

- ##### GET /api/loyality/ - получение всего списка лояльностей.
###### Логика работы - N/A
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - N/A
###### Тело ответа - 
```js
[
    {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "name": "string"
    }
]
```
###### Исключения - 
###### ***InternalErrorException***
---
- ##### GET /api/loyality/{loyaltyId} - получение лояльности по ID.
###### Логика работы - находит в базе данных лояльность в соответствиии с переданным ID с помощью ***loyaltyId***.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***loyaltyId - UUID***
###### Тело ответа - 
```js
{
  "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "name": "string"
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### POST /api/loyality/ - создание лояльности.
###### Логика работы - создает лояльность в соответствии с телом запроса и сохраняет ее.
###### Тело запроса -
```js
{
  "name": "string"
}
```
###### Параметры запроса - N/A
###### PATH параметры - N/A
###### Тело ответа - 
```js
{
  "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "name": "string"
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/loyality/{loyaltyId} - обновление лояльности.
###### Логика работы - находит лояльность в соответствии с ID переданным через ***loyaltyId***, обновляет ее в соответствии с телом запроса и сохраняет.
###### Тело запроса -
```js
{
  "name": "string"
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***loyaltyId - UUID***
###### Тело ответа - 
```js
{
  "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "name": "string"
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### DELETE /api/loyality/{loyaltyId} - удаление лояльности.
###### Логика работы - находит в базе данных лояльность в соответствиии с переданным ID с помощью ***loyaltyId*** и удаляет ее.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***loyaltyId - UUID***
###### Тело ответа - 
```js
boolean
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***