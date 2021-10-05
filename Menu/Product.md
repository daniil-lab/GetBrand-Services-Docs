# GetBrand Menu Service Documentation

## Product

- ##### GET /api/product/ - получение всего списка продуктов.
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
      "type": "string",
      "description": "string",
      "price": 0,
      "createdAt": "string",
      "updatedAt": "string",
      "categoryId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "companyId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "modificators": [
        {
          "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
          "name": "string",
          "group": "string",
          "description": "string",
          "price": 0
        }
      ],
      "files": [
        {
          "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
          "name": "string",
          "url": "string",
          "createdAt": "string",
          "updatedAt": "string"
        }
      ],
      "showForClient": true
    }
]
```
###### Исключения - 
###### ***InternalErrorException***
---
- ##### GET /api/product/{productId} - получение продукта по ID.
###### Логика работы - находит в базе данных продукт в соответствиии с переданным ID с помощью ***productId***.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***productId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "type": "string",
    "description": "string",
    "price": 0,
    "createdAt": "string",
    "updatedAt": "string",
    "categoryId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "companyId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "modificators": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "group": "string",
        "description": "string",
        "price": 0
      }
    ],
    "files": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "url": "string",
        "createdAt": "string",
        "updatedAt": "string"
      }
    ],
    "showForClient": true
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### POST /api/product/ - создание продукта.
###### Логика работы - создает продукт в соответствии с телом запроса и сохраняет ее. При наличии ***posterId*** просто сохранит продукт (используется для синхронизации). При наличии ***posterId*** и при типе компании ***POSTER*** система так же создаст продукт внутри системы ***Poster***.  
###### Тело запроса -
```js
{
  "name": "string",
  "description": "string",
  "type": "string",
  "percent": 0,
  "summ": 0,
  "timeSpending": "string",
  "companyId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "showOnMainScreen": true,
  "posterId": 0,
  "banner": true,
  "allow": true
}
```
###### Параметры запроса - N/A
###### PATH параметры - N/A
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "type": "string",
    "description": "string",
    "price": 0,
    "createdAt": "string",
    "updatedAt": "string",
    "categoryId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "companyId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "modificators": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "group": "string",
        "description": "string",
        "price": 0
      }
    ],
    "files": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "url": "string",
        "createdAt": "string",
        "updatedAt": "string"
      }
    ],
    "showForClient": true
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/product/{productId} - обновление продукта.
###### Логика работы - находит продукт в соответствии с ID переданным через ***productId***, обновляет его в соответствии с телом запроса и сохраняет.
###### Тело запроса -
```js
{
  "name": "string",
  "description": "string",
  "type": "string",
  "percent": 0,
  "summ": 0,
  "timeSpending": "string",
  "companyId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "showOnMainScreen": true,
  "posterId": 0,
  "banner": true,
  "allow": true
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***productId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "type": "string",
    "description": "string",
    "price": 0,
    "createdAt": "string",
    "updatedAt": "string",
    "categoryId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "companyId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "modificators": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "group": "string",
        "description": "string",
        "price": 0
      }
    ],
    "files": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "url": "string",
        "createdAt": "string",
        "updatedAt": "string"
      }
    ],
    "showForClient": true
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### DELETE /api/product/{productId}/files - удаление файла из продукта.
###### Логика работы - находит продукт в соответствии с ID переданным через ***productId***, удаляет из него файл в соответствии с телом запроса и сохраняет.
###### Тело запроса -
```js
[
  {
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6"
  }
]
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***productId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "type": "string",
    "description": "string",
    "price": 0,
    "createdAt": "string",
    "updatedAt": "string",
    "categoryId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "companyId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "modificators": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "group": "string",
        "description": "string",
        "price": 0
      }
    ],
    "files": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "url": "string",
        "createdAt": "string",
        "updatedAt": "string"
      }
    ],
    "showForClient": true
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/product/{productId}/files - прикрепление файла к продукту.
###### Логика работы - находит продукт в соответствии с ID переданным через ***productId***, прикрепляет ему файл в соответствии с телом запроса и сохраняет.
###### Тело запроса -
```js
[
  {
    "name": "string",
    "url": "string"
  }
]
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***productId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "type": "string",
    "description": "string",
    "price": 0,
    "createdAt": "string",
    "updatedAt": "string",
    "categoryId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "companyId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "modificators": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "group": "string",
        "description": "string",
        "price": 0
      }
    ],
    "files": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "url": "string",
        "createdAt": "string",
        "updatedAt": "string"
      }
    ],
    "showForClient": true
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/product/modificators/add/{productId} - прикрепление модификаторов к продукту.
###### Логика работы - находит продукт в соответствии с ID переданным через ***productId***, прикрепляет ему модификаторы в соответствии с телом запроса и сохраняет.
###### Тело запроса -
```js
[
  {
    "name": "string",
    "group": "string",
    "description": "string",
    "price": 0,
    "productId": "string"
  }
]
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***productId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "type": "string",
    "description": "string",
    "price": 0,
    "createdAt": "string",
    "updatedAt": "string",
    "categoryId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "companyId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "modificators": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "group": "string",
        "description": "string",
        "price": 0
      }
    ],
    "files": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "url": "string",
        "createdAt": "string",
        "updatedAt": "string"
      }
    ],
    "showForClient": true
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/product/modificators/delete/{productId} - удаление модификаторов у продукта.
###### Логика работы - находит продукт в соответствии с ID переданным через ***productId***, удаляет ему модификаторы в соответствии с телом запроса и сохраняет.
###### Тело запроса -
```js
{
  "modificatorIds": [
    "string"
  ]
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***productId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "type": "string",
    "description": "string",
    "price": 0,
    "createdAt": "string",
    "updatedAt": "string",
    "categoryId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "companyId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "modificators": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "group": "string",
        "description": "string",
        "price": 0
      }
    ],
    "files": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "url": "string",
        "createdAt": "string",
        "updatedAt": "string"
      }
    ],
    "showForClient": true
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### DELETE /api/product/{productId} - удаление продукта.
###### Логика работы - находит в базе данных продукт в соответствиии с переданным ID с помощью ***productId*** и удаляет его.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***productId - UUID***
###### Тело ответа - 
```js
boolean
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***