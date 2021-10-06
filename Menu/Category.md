# GetBrand Menu Service Documentation

## Product Category

- ##### GET /api/product-category/ - получение всего списка категорий.
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
      "description": "string",
      "createdAt": "string",
      "updatedAt": "string",
      "companyId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "files": [
        {
          "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
          "name": "string",
          "url": "string",
          "createdAt": "string",
          "updatedAt": "string"
        }
      ],
      "products": [
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
      ],
      "components": [
        "string"
      ],
      "showForClient": true
    }
]
```
###### Исключения - 
###### ***InternalErrorException***
---
- ##### GET /api/product-category/{categoryId} - получение категории по ID.
###### Логика работы - находит в базе данных категорию в соответствиии с переданным ID с помощью ***categoryId***.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***categoryId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "description": "string",
    "createdAt": "string",
    "updatedAt": "string",
    "companyId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "files": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "url": "string",
        "createdAt": "string",
        "updatedAt": "string"
      }
    ],
    "products": [
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
    ],
    "components": [
      "string"
    ],
    "showForClient": true
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### POST /api/product-category/ - создание категории.
###### Логика работы - создает категорию в соответствии с телом запроса и сохраняет ее. При наличии ***posterId*** просто сохранит категорию (используется для синхронизации). При наличии ***posterId*** и при типе компании ***POSTER*** система так же создаст категорию внутри системы ***Poster***.  
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
    "description": "string",
    "createdAt": "string",
    "updatedAt": "string",
    "companyId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "files": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "url": "string",
        "createdAt": "string",
        "updatedAt": "string"
      }
    ],
    "products": [
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
    ],
    "components": [
      "string"
    ],
    "showForClient": true
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/product/{categoryId} - обновление продукта.
###### Логика работы - находит продукт в соответствии с ID переданным через ***categoryId***, обновляет его в соответствии с телом запроса и сохраняет.
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
###### ***categoryId - UUID***
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
- ##### DELETE /api/product-category/{categoryId}/files - удаление файла из категории.
###### Логика работы - находит категорию в соответствии с ID переданным через ***categoryId***, удаляет из нее файл в соответствии с телом запроса и сохраняет.
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
###### ***categoryId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "description": "string",
    "createdAt": "string",
    "updatedAt": "string",
    "companyId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "files": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "url": "string",
        "createdAt": "string",
        "updatedAt": "string"
      }
    ],
    "products": [
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
    ],
    "components": [
      "string"
    ],
    "showForClient": true
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/product-category/{categoryId}/files - прикрепление файла к категории.
###### Логика работы - находит категорию в соответствии с ID переданным через ***categoryId***, прикрепляет ей файл в соответствии с телом запроса и сохраняет.
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
###### ***categoryId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "description": "string",
    "createdAt": "string",
    "updatedAt": "string",
    "companyId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "files": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "url": "string",
        "createdAt": "string",
        "updatedAt": "string"
      }
    ],
    "products": [
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
    ],
    "components": [
      "string"
    ],
    "showForClient": true
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### DELETE /api/product-category/{categoryId} - удаление продукта.
###### Логика работы - находит в базе данных категорию в соответствиии с переданным ID с помощью ***categoryId*** и удаляет ее.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***categoryId - UUID***
###### Тело ответа - 
```js
boolean
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***