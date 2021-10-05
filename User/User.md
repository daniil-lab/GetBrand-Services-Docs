# GetBrand User Service Documentation

## User

- ##### GET /api/user/ - получение всего списка пользователей.
###### Логика работы - N/A
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - N/A
###### Тело ответа - 
```js
[
    {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "login": "string",
      "password": "string",
      "name": "string",
      "birthday": "string",
      "email": "string",
      "phone": "string",
      "managerPercent": 0,
      "balance": 0,
      "companies": [
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
      ],
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
      }
    }
]
```
###### Исключения - 
###### ***InternalErrorException***
---
- ##### GET /api/user/{userId} - получение пользователя по ID.
###### Логика работы - находит в базе данных пользователя в соответствиии с переданным ID с помощью ***userId***.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***userId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "login": "string",
    "password": "string",
    "name": "string",
    "birthday": "string",
    "email": "string",
    "phone": "string",
    "managerPercent": 0,
    "balance": 0,
    "companies": [
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
    ],
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
    }
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### GET /api/user/findBy - поиск пользователя.
###### Логика работы - находит в базе данных пользователя в соответствиии с заданными параметрами запроса.
###### Тело запроса - N/A
###### Параметры запроса - 
###### login - String
###### name - String
###### birthday - String
###### email - String
###### phone - String
###### PATH параметры - N/A
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "login": "string",
    "password": "string",
    "name": "string",
    "birthday": "string",
    "email": "string",
    "phone": "string",
    "managerPercent": 0,
    "balance": 0,
    "companies": [
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
    ],
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
    }
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### POST /api/user/ - создание пользователя.
###### Логика работы - создает пользователя в соответствии с телом запроса и сохраняет его.
###### Тело запроса -
```js
{
  "login": "string",
  "name": "string",
  "birthday": "string",
  "password": "string",
  "email": "string",
  "managerPercent": 0,
  "phone": "string",
  "status": "string"
}
```
###### Параметры запроса - N/A
###### PATH параметры - N/A
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "login": "string",
    "password": "string",
    "name": "string",
    "birthday": "string",
    "email": "string",
    "phone": "string",
    "managerPercent": 0,
    "balance": 0,
    "companies": [
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
    ],
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
    }
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### POST /api/user/sms - создание пользователя.
###### Логика работы - создает пользователя в соответствии с телом запроса (учитывая ***SmsAuthDto***) и сохраняет его.
###### Тело запроса -
```js
{
  "login": "string",
  "name": "string",
  "birthday": "string",
  "password": "string",
  "email": "string",
  "managerPercent": 0,
  "phone": "string",
  "status": "string",
  "smsAuthDto": {
    "sid": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "smsCode": 0,
    "phone": "string"
  }
}
```
###### Параметры запроса - N/A
###### PATH параметры - N/A
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "login": "string",
    "password": "string",
    "name": "string",
    "birthday": "string",
    "email": "string",
    "phone": "string",
    "managerPercent": 0,
    "balance": 0,
    "companies": [
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
    ],
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
    }
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/user/{userId} - обновление пользователя.
###### Логика работы - находит пользователя в соответствии с ID переданным через ***userId***, обновляет его в соответствии с телом запроса и сохраняет.
###### Тело запроса -
```js
{
  "login": "string",
  "name": "string",
  "birthday": "string",
  "password": "string",
  "email": "string",
  "managerPercent": 0,
  "phone": "string",
  "status": "string"
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***userId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "login": "string",
    "password": "string",
    "name": "string",
    "birthday": "string",
    "email": "string",
    "phone": "string",
    "managerPercent": 0,
    "balance": 0,
    "companies": [
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
    ],
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
    }
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### DELETE /api/user/{userId} - удаление пользователя.
###### Логика работы - находит в базе данных пользователя в соответствиии с переданным ID с помощью ***userId*** и удаляет его.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***userId - UUID***
###### Тело ответа - 
```js
boolean
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/user/{userId}/password - обновление пароля пользователя.
###### Логика работы - находит пользователя в соответствии с ID переданным через ***userId***, обновляет его пароль в соответствии с телом запроса и сохраняет.
###### Тело запроса -
```js
{
  "password": "string"
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***userId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "login": "string",
    "password": "string",
    "name": "string",
    "birthday": "string",
    "email": "string",
    "phone": "string",
    "managerPercent": 0,
    "balance": 0,
    "companies": [
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
    ],
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
    }
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/user/{userId}/password/sms - обновление пароля пользователя.
###### Логика работы - находит пользователя в соответствии с ID переданным через ***userId***, обновляет его пароль (учитывая ***SmsAuthDto***) в соответствии с телом запроса и сохраняет.
###### Тело запроса -
```js
{
  "password": "string",
  "smsAuthDto": {
    "sid": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "smsCode": 0,
    "phone": "string"
  }
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***userId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "login": "string",
    "password": "string",
    "name": "string",
    "birthday": "string",
    "email": "string",
    "phone": "string",
    "managerPercent": 0,
    "balance": 0,
    "companies": [
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
    ],
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
    }
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/user/status/{userId} - обновление статуса пользователя.
###### Логика работы - находит пользователя в соответствии с ID переданным через ***userId***, обновляет его статус в соответствии с телом запроса и сохраняет.
###### Тело запроса -
```js
{
  "status": "string"
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***userId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "login": "string",
    "password": "string",
    "name": "string",
    "birthday": "string",
    "email": "string",
    "phone": "string",
    "managerPercent": 0,
    "balance": 0,
    "companies": [
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
    ],
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
    }
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/user/role/{userId} - обновление роли пользователя.
###### Логика работы - находит пользователя в соответствии с ID переданным через ***userId***, обновляет его статус в соответствии с телом запроса и сохраняет. ***operation = add*** добавляет пользователю заданную роль в ***companyRoleId***.
###### Тело запроса -
```js
{
  "companyRoleId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "operation": "string"
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***userId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "login": "string",
    "password": "string",
    "name": "string",
    "birthday": "string",
    "email": "string",
    "phone": "string",
    "managerPercent": 0,
    "balance": 0,
    "companies": [
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
    ],
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
    }
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/user/company/{userId} - обновление компании пользователя.
###### Логика работы - находит пользователя в соответствии с ID переданным через ***userId***, обновляет его компанию в соответствии с телом запроса и сохраняет. ***operation = add*** добавляет пользователю заданную компанию в ***companyId***.
###### Тело запроса -
```js
{
  "companyId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "operation": "string"
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***userId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "login": "string",
    "password": "string",
    "name": "string",
    "birthday": "string",
    "email": "string",
    "phone": "string",
    "managerPercent": 0,
    "balance": 0,
    "companies": [
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
    ],
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
    }
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***