# GetBrand Promo Service Documentation

## Promo

- ##### GET /api/promo/ - получение всего списка акций.
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
      "type": "string",
      "percent": 0,
      "summ": 0,
      "timeSpending": "string",
      "showOnMainScreen": true,
      "files": [
        {
          "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
          "name": "string",
          "url": "string",
          "createdAt": "string",
          "updatedAt": "string"
        }
      ],
      "company": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "inn": 0,
        "phone": "string",
        "email": "string",
        "balance": 0,
        "vk": "string",
        "ig": "string",
        "fb": "string",
        "youtube": "string",
        "privacy": "string",
        "pushChannel": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "url": "string",
        "description": "string",
        "users": [
          "3fa85f64-5717-4562-b3fc-2c963f66afa6"
        ],
        "addresses": [
          {
            "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
            "name": "string",
            "description": "string",
            "minOrderSumForDelivery": 0,
            "address": "string",
            "workModes": [
              "string"
            ],
            "company": "string"
          }
        ],
        "companyIntegration": {
          "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
          "integrationId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
          "integrationType": "POSTER"
        },
        "status": {
          "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
          "changeAt": "string",
          "status": {
            "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
            "name": "string",
            "from": [
              "string"
            ],
            "to": "string",
            "auto": true
          }
        },
        "tarifs": [
          {
            "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
            "name": "string",
            "systemName": "string",
            "description": "string",
            "picture": "string",
            "value": 0,
            "activationPrice": 0
          }
        ],
        "integration": {
          "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
          "integrationId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
          "integrationType": "POSTER"
        }
      },
      "banner": true,
      "allow": true
    }
]
```
###### Исключения - 
###### ***InternalErrorException***
---
- ##### GET /api/promo/{promoId} - получение акции по ID.
###### Логика работы - находит в базе данных акцию в соответствиии с переданным ID с помощью ***promoId***.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***promoId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "description": "string",
    "type": "string",
    "percent": 0,
    "summ": 0,
    "timeSpending": "string",
    "showOnMainScreen": true,
    "files": [
    {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "url": "string",
        "createdAt": "string",
        "updatedAt": "string"
    }
    ],
    "company": {
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "inn": 0,
    "phone": "string",
    "email": "string",
    "balance": 0,
    "vk": "string",
    "ig": "string",
    "fb": "string",
    "youtube": "string",
    "privacy": "string",
    "pushChannel": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "url": "string",
    "description": "string",
    "users": [
        "3fa85f64-5717-4562-b3fc-2c963f66afa6"
    ],
    "addresses": [
        {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "description": "string",
        "minOrderSumForDelivery": 0,
        "address": "string",
        "workModes": [
            "string"
        ],
        "company": "string"
        }
    ],
    "companyIntegration": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "integrationId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "integrationType": "POSTER"
    },
    "status": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "changeAt": "string",
        "status": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "from": [
            "string"
        ],
        "to": "string",
        "auto": true
        }
    },
    "tarifs": [
        {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "systemName": "string",
        "description": "string",
        "picture": "string",
        "value": 0,
        "activationPrice": 0
        }
    ],
    "integration": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "integrationId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "integrationType": "POSTER"
    }
    },
    "banner": true,
    "allow": true
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### POST /api/promo/ - создание акции.
###### Логика работы - создает акцию в соответствии с телом запроса и сохраняет ее. При наличии ***posterId*** просто сохранит акцию (используется для синхронизации). Так как ***Poster*** не имеет возможности создания акции, создать ее для компании типа ***POSTER*** не есть возможным. 
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
    "type": "string",
    "percent": 0,
    "summ": 0,
    "timeSpending": "string",
    "showOnMainScreen": true,
    "files": [
    {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "url": "string",
        "createdAt": "string",
        "updatedAt": "string"
    }
    ],
    "company": {
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "inn": 0,
    "phone": "string",
    "email": "string",
    "balance": 0,
    "vk": "string",
    "ig": "string",
    "fb": "string",
    "youtube": "string",
    "privacy": "string",
    "pushChannel": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "url": "string",
    "description": "string",
    "users": [
        "3fa85f64-5717-4562-b3fc-2c963f66afa6"
    ],
    "addresses": [
        {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "description": "string",
        "minOrderSumForDelivery": 0,
        "address": "string",
        "workModes": [
            "string"
        ],
        "company": "string"
        }
    ],
    "companyIntegration": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "integrationId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "integrationType": "POSTER"
    },
    "status": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "changeAt": "string",
        "status": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "from": [
            "string"
        ],
        "to": "string",
        "auto": true
        }
    },
    "tarifs": [
        {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "systemName": "string",
        "description": "string",
        "picture": "string",
        "value": 0,
        "activationPrice": 0
        }
    ],
    "integration": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "integrationId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "integrationType": "POSTER"
    }
    },
    "banner": true,
    "allow": true
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/promo/{promoId} - обновление акции.
###### Логика работы - находит акцию в соответствии с ID переданным через ***promoId***, обновляет ее в соответствии с телом запроса и сохраняет.
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
###### ***promoId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "description": "string",
    "type": "string",
    "percent": 0,
    "summ": 0,
    "timeSpending": "string",
    "showOnMainScreen": true,
    "files": [
    {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "url": "string",
        "createdAt": "string",
        "updatedAt": "string"
    }
    ],
    "company": {
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "inn": 0,
    "phone": "string",
    "email": "string",
    "balance": 0,
    "vk": "string",
    "ig": "string",
    "fb": "string",
    "youtube": "string",
    "privacy": "string",
    "pushChannel": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "url": "string",
    "description": "string",
    "users": [
        "3fa85f64-5717-4562-b3fc-2c963f66afa6"
    ],
    "addresses": [
        {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "description": "string",
        "minOrderSumForDelivery": 0,
        "address": "string",
        "workModes": [
            "string"
        ],
        "company": "string"
        }
    ],
    "companyIntegration": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "integrationId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "integrationType": "POSTER"
    },
    "status": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "changeAt": "string",
        "status": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "from": [
            "string"
        ],
        "to": "string",
        "auto": true
        }
    },
    "tarifs": [
        {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "systemName": "string",
        "description": "string",
        "picture": "string",
        "value": 0,
        "activationPrice": 0
        }
    ],
    "integration": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "integrationId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "integrationType": "POSTER"
    }
    },
    "banner": true,
    "allow": true
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### DELETE /api/promo/{promoId}/files - удаление файла из акции.
###### Логика работы - находит акцию в соответствии с ID переданным через ***promoId***, удаляет из нее файл в соответствии с телом запроса и сохраняет.
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
###### ***promoId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "description": "string",
    "type": "string",
    "percent": 0,
    "summ": 0,
    "timeSpending": "string",
    "showOnMainScreen": true,
    "files": [
    {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "url": "string",
        "createdAt": "string",
        "updatedAt": "string"
    }
    ],
    "company": {
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "inn": 0,
    "phone": "string",
    "email": "string",
    "balance": 0,
    "vk": "string",
    "ig": "string",
    "fb": "string",
    "youtube": "string",
    "privacy": "string",
    "pushChannel": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "url": "string",
    "description": "string",
    "users": [
        "3fa85f64-5717-4562-b3fc-2c963f66afa6"
    ],
    "addresses": [
        {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "description": "string",
        "minOrderSumForDelivery": 0,
        "address": "string",
        "workModes": [
            "string"
        ],
        "company": "string"
        }
    ],
    "companyIntegration": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "integrationId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "integrationType": "POSTER"
    },
    "status": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "changeAt": "string",
        "status": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "from": [
            "string"
        ],
        "to": "string",
        "auto": true
        }
    },
    "tarifs": [
        {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "systemName": "string",
        "description": "string",
        "picture": "string",
        "value": 0,
        "activationPrice": 0
        }
    ],
    "integration": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "integrationId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "integrationType": "POSTER"
    }
    },
    "banner": true,
    "allow": true
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/promo/{promoId}/files - прикрепление файла к акции.
###### Логика работы - находит акцию в соответствии с ID переданным через ***promoId***, прикрепляет ей файл в соответствии с телом запроса и сохраняет.
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
###### ***promoId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "description": "string",
    "type": "string",
    "percent": 0,
    "summ": 0,
    "timeSpending": "string",
    "showOnMainScreen": true,
    "files": [
    {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "url": "string",
        "createdAt": "string",
        "updatedAt": "string"
    }
    ],
    "company": {
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "inn": 0,
    "phone": "string",
    "email": "string",
    "balance": 0,
    "vk": "string",
    "ig": "string",
    "fb": "string",
    "youtube": "string",
    "privacy": "string",
    "pushChannel": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "url": "string",
    "description": "string",
    "users": [
        "3fa85f64-5717-4562-b3fc-2c963f66afa6"
    ],
    "addresses": [
        {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "description": "string",
        "minOrderSumForDelivery": 0,
        "address": "string",
        "workModes": [
            "string"
        ],
        "company": "string"
        }
    ],
    "companyIntegration": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "integrationId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "integrationType": "POSTER"
    },
    "status": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "changeAt": "string",
        "status": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "from": [
            "string"
        ],
        "to": "string",
        "auto": true
        }
    },
    "tarifs": [
        {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "systemName": "string",
        "description": "string",
        "picture": "string",
        "value": 0,
        "activationPrice": 0
        }
    ],
    "integration": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "integrationId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "integrationType": "POSTER"
    }
    },
    "banner": true,
    "allow": true
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### DELETE /api/promo/{promoId} - удаление акции.
###### Логика работы - находит в базе данных акцию в соответствиии с переданным ID с помощью ***promoId*** и удаляет ее.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***promoId - UUID***
###### Тело ответа - 
```js
boolean
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***