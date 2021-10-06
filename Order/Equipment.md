# GetBrand Order Service Documentation

## Equipment

- ##### GET /api/equipment/ - получение всего списка эквипмента.
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
      "volume": 0,
      "inventoryCode": "string",
      "minReserv": 0,
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
      }
    }
]
```
###### Исключения - 
###### ***InternalErrorException***
---
- ##### GET /api/equipment/{equipmentId} - получение эквипмента по ID.
###### Логика работы - находит в базе данных эквипмент в соответствиии с переданным ID с помощью ***equipmentId***.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***equipmentId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "description": "string",
    "volume": 0,
    "inventoryCode": "string",
    "minReserv": 0,
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
    }
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### POST /api/equipment/ - создание эквипмента.
###### Логика работы - создает эквипмент в соответствии с телом запроса и сохраняет его. Создание при типе компании ***POSTER*** невозможно в связи с их API. Поле ***poster_id*** используется исключительно для синхронизации.
###### Тело запроса -
```js
{
  "name": "string",
  "description": "string",
  "volume": 0,
  "inventoryCode": "string",
  "minReserv": 0,
  "poster_id": 0,
  "companyId": "3fa85f64-5717-4562-b3fc-2c963f66afa6"
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
    "volume": 0,
    "inventoryCode": "string",
    "minReserv": 0,
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
    }
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/equipment/{equipmentId} - обновление эквипмента.
###### Логика работы - находит эквипмент в соответствии с ID переданным через ***equipmentId***, обновляет его в соответствии с телом запроса и сохраняет.
###### Тело запроса -
```js
{
  "name": "string",
  "description": "string",
  "volume": 0,
  "inventoryCode": "string",
  "minReserv": 0,
  "poster_id": 0,
  "companyId": "3fa85f64-5717-4562-b3fc-2c963f66afa6"
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***equipmentId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "description": "string",
    "volume": 0,
    "inventoryCode": "string",
    "minReserv": 0,
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
    }
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### DELETE /api/equipment/{equipmentId} - удаление эквипмента.
###### Логика работы - находит в базе данных эквипмент в соответствиии с переданным ID с помощью ***equipmentId*** и удаляет его.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***equipmentId - UUID***
###### Тело ответа - 
```js
boolean
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***