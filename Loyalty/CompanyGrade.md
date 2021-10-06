# GetBrand Loyalty Service Documentation

## Company Grade

- ##### GET /api/company-grade/ - получение всего списка грейдов.
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
      "layer": 0,
      "value": 0,
      "companyLoyality": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "description": "string",
        "loyality": {
          "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
          "name": "string"
        },
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
    }
]
```
###### Исключения - 
###### ***InternalErrorException***
---
- ##### GET /api/company-grade/{gradeId} - получение грейда по ID.
###### Логика работы - находит в базе данных грейд в соответствиии с переданным ID с помощью ***gradeId***.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***gradeId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "layer": 0,
    "value": 0,
    "companyLoyality": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "name": "string",
      "description": "string",
      "loyality": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string"
      },
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
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### POST /api/company-grade/ - создание грейда.
###### Логика работы - создает грейд в соответствии с телом запроса и сохраняет его.
###### Тело запроса -
```js
{
  "name": "string",
  "layer": 0,
  "value": 0,
  "companyLoyalityId": "3fa85f64-5717-4562-b3fc-2c963f66afa6"
}
```
###### Параметры запроса - N/A
###### PATH параметры - N/A
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "layer": 0,
    "value": 0,
    "companyLoyality": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "name": "string",
      "description": "string",
      "loyality": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string"
      },
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
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/company-grade/{gradeId} - обновление грейда.
###### Логика работы - находит грейд в соответствии с ID переданным через ***gradeId***, обновляет его в соответствии с телом запроса и сохраняет.
###### Тело запроса -
```js
{
  "name": "string",
  "layer": 0,
  "value": 0,
  "companyLoyalityId": "3fa85f64-5717-4562-b3fc-2c963f66afa6"
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***gradeId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "layer": 0,
    "value": 0,
    "companyLoyality": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "name": "string",
      "description": "string",
      "loyality": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string"
      },
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
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### DELETE /api/company-grade/{gradeId} - удаление грейда.
###### Логика работы - находит в базе данных грейд в соответствиии с переданным ID с помощью ***gradeId*** и удаляет его.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***gradeId - UUID***
###### Тело ответа - 
```js
boolean
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***