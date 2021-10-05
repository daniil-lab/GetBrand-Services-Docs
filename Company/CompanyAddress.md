# GetBrand Company Service Documentation

## Company Address

- ##### GET /api/company-address/ - получение всего списка адресов компаний.
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
      "minOrderSumForDelivery": 0,
      "address": "string",
      "workModes": [
        "string"
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
          "string"
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
- ##### GET /api/company-address/{companyAddressId} - получение адреса компании по ID.
###### Логика работы - Находит внутри базы данных адрес с переданным в ***companyAddressId*** ID и возвращает его.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры -
###### ***companyAddressId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "description": "string",
    "minOrderSumForDelivery": 0,
    "address": "string",
    "workModes": [
    "string"
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
        "string"
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
###### ***InvalidDataException***
###### ***NotFoundException***
---
- ##### POST /api/company-address/ - создание адреса компании.
###### Логика работы - Создает новый экземпляр адреса компании, прикрепляя его к указанной, сохраняет сущность и возвращает в виде ответа. При наличии поля ***posterId*** создает как объект адреса, синхронизированного с ***Poster*** (используется при синхронизации адресов). Для создания обычного адреса компании, ***posterId*** должен отсутствовать.
###### Тело запроса - 
```js
{
  "name": "string",
  "description": "string",
  "address": "string",
  "minOrderSumForDelivery": 0,
  "companyId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "posterId": 0
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
    "minOrderSumForDelivery": 0,
    "address": "string",
    "workModes": [
    "string"
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
        "string"
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
###### ***InvalidDataException***
###### ***NotFoundException***
---
- ##### DELETE /api/company-address/{companyAddressId} - удаление адреса компании по ID.
###### Логика работы - Находит внутри базы данных адрес с переданным в ***companyAddressId*** ID и удаляет его.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры -
###### ***companyAddressId - UUID***
###### Тело ответа - 
```js
boolean
```
###### Исключения - 
###### ***InternalErrorException***
###### ***InvalidDataException***
###### ***NotFoundException***
---
- ##### PATCH /api/company-address/{companyAddressId} - обновление адреса компании по ID.
###### Логика работы - Находит внутри базы данных адрес с переданным в ***companyAddressId*** ID и в соответствии с телом запроса обновляет его. При обновлении поле ***posterId*** должно отсутствовать.
###### Тело запроса - 
```js
{
  "name": "string",
  "description": "string",
  "address": "string",
  "minOrderSumForDelivery": 0,
  "companyId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "posterId": 0
}
```
###### Параметры запроса - N/A
###### PATH параметры -
###### ***companyAddressId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "description": "string",
    "minOrderSumForDelivery": 0,
    "address": "string",
    "workModes": [
    "string"
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
        "string"
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
###### ***InvalidDataException***
###### ***NotFoundException***