# GetBrand Company Service Documentation

- ##### GET /api/company/ - получение всего списка компаний.
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
  ]
```
###### Исключения - 
###### ***InternalErrorException***
---
- ##### GET /api/company/{companyId} - получение компании по ID.
###### Логика работы - находит компанию в базе данных по полученному ***companyId*** и возвращает результат.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***companyId - UUID***
###### Тело ответа - 
```js
    {
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
```
###### Исключения - 
###### ***InvalidDataException***
###### ***NotFountException***
###### ***InternalErrorException***
---
- ##### GET /api/company/findBy - поиск компании.
###### Логика работы - находит компанию в базе данных по полученным данным из параметров запроса.
###### Тело запроса - N/A
###### Параметры запроса -
###### ***name - String***
###### ***inn - int***
###### ***address - String***
###### ***phone - String***
###### ***email - String***
###### PATH параметры - N/A
###### Тело ответа - 
```js
    {
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
```
###### Исключения - 
###### ***InvalidDataException***
###### ***NotFountException***
###### ***InternalErrorException***
---
- ##### POST /api/company/ - создание объекта компании.
###### Логика работы - Создается объект компании и сохраняется в базу данных для хранения. При ***integrationType = GETBRAND*** создается стандартная компания. При передаче ***integrationType = POSTER***, создается компания-интеграция POSTER, в таком случае, требуется передать в ***integrationCred*** API токен для интеграции.
###### Тело запроса - 
```js
{
  "name": "string",
  "inn": 0,
  "phone": "string",
  "email": "string",
  "vk": "string",
  "ig": "string",
  "fb": "string",
  "youtube": "string",
  "privacy": "string",
  "url": "string",
  "description": "string",
  "integrationType": "POSTER",
  "integrationCred": "string"
}
```
###### Параметры запроса - N/A
###### PATH параметры - N/A
###### Тело ответа - 
```js
    {
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
```
###### Исключения - 
###### ***InvalidDataException***
###### ***NotFountException***
###### ***InternalErrorException***
---
- ##### DELETE /api/company/{companyId} - удаляет объекта компании.
###### Логика работы - находит внутри базы данных компанию с переданным в ***companyId*** ID и удаляет ее.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***companyId - UUID***
###### Тело ответа - 
```js
    boolean
```
###### Исключения - 
###### ***InvalidDataException***
###### ***NotFountException***
###### ***InternalErrorException***
---
- ##### PATCH /api/company/{companyId} - обновляет объекта компании.
###### Логика работы - находит внутри базы данных компанию с переданным в ***companyId*** ID и обновляет ее при помощи указанных данных в теле запроса.
###### Тело запроса -
```js
{
  "name": "string",
  "inn": 0,
  "statusId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "phone": "string",
  "email": "string",
  "vk": "string",
  "fb": "string",
  "ig": "string",
  "youtube": "string",
  "privacy": "string",
  "url": "string",
  "balance": 0,
  "description": "string"
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***companyId - UUID***
###### Тело ответа - 
```js
    {
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
```
###### Исключения - 
###### ***InvalidDataException***
###### ***NotFountException***
###### ***InternalErrorException***
---
- ##### PATCH /api/company/{companyId}/tarif/{tariffId} - прикрепляет к компании тарифф.
###### Логика работы - находит внутри базы данных компанию с переданным в ***companyId*** ID, после чего находит в системе тарифф с идентичным ID из ***tariffId*** и добавляет его к компании.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***companyId - UUID***
###### ***tariffId - UUID***
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
###### ***InvalidDataException***
###### ***NotFountException***
###### ***InternalErrorException***
---
- ##### DELETE /api/company/{companyId}/tarif/{tariffId} - открепляет тарифф от компании.
###### Логика работы - находит внутри базы данных компанию с переданным в ***companyId*** ID, после чего находит внутри компании тарифф, с ID идентичным ***tariffId*** и удаляет его из компании.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***companyId - UUID***
###### ***tariffId - UUID***
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
###### ***InvalidDataException***
###### ***NotFountException***
###### ***InternalErrorException***
---
- ##### GET /api/company/{companyId}/config/ - возвращает конфиг компании.
###### Логика работы - находит внутри базы данных компанию с переданным в ***companyId*** ID, после чего находит с помощью полученной компании ее конфиг и возвращает его.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***companyId - UUID***
###### Тело ответа - 
```js
  {
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "currentOrderNumber": 0,
    "defOfPay": 0,
    "lotteryAddValue": 0,
    "lotterySubValue": 0,
    "lotteryOrderSumLimit": 0,
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
    "advertShow": true,
    "lotteryOnOrderChangeStateAllow": true
  }
```
###### Исключения - 
###### ***InvalidDataException***
###### ***NotFountException***
###### ***InternalErrorException***
---
- ##### PATCH /api/company/{companyId}/config/ - обновляет конфиг компании.
###### Логика работы - находит внутри базы данных компанию с переданным в ***companyId*** ID, после чего находит с помощью полученной компании ее конфиг и обновляет в нем данные, в соответствии с указанными в теле запроса.
###### Тело запроса -
```js
{
  "currentOrderNumber": 0,
  "defOfPay": 0,
  "isAdvertShow": true,
  "isLotteryOnOrderChangeStateAllow": true,
  "lotteryAddValue": 0,
  "lotterySubValue": 0,
  "lotteryOrderSumLimit": 0,
  "advertShow": true,
  "lotteryOnOrderChangeStateAllow": true
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***companyId - UUID***
###### Тело ответа - 
```js
  {
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "currentOrderNumber": 0,
    "defOfPay": 0,
    "lotteryAddValue": 0,
    "lotterySubValue": 0,
    "lotteryOrderSumLimit": 0,
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
    "advertShow": true,
    "lotteryOnOrderChangeStateAllow": true
  }
```
###### Исключения - 
###### ***InvalidDataException***
###### ***NotFountException***
###### ***InternalErrorException***
---
- ##### PATCH /api/company/{companyId}/balance/ - обновляет баланс компании.
###### Логика работы - находит внутри базы данных компанию с переданным в ***companyId*** ID и в соответствии с телом запроса производит операцию над балансом компании. ***operation = add*** - добавить к балансу.
###### Тело запроса -
```js
{
  "balance": 0,
  "operation": "string"
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***companyId - UUID***
###### Тело ответа - 
```js
  {
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
```
###### Исключения - 
###### ***InvalidDataException***
###### ***NotFountException***
###### ***InternalErrorException***