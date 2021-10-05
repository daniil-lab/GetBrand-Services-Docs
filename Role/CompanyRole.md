# GetBrand Role Service Documentation

## Company Role

- ##### GET /api/company-role/ - получение всего списка ролей компаний.
###### Логика работы - N/A
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - N/A
###### Тело ответа - 
```js
[
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "role": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "rolesForUser": "string",
        "addAutomaticly": true
      },
      "user": [
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
      }
    }
  ]
]
```
###### Исключения - 
###### ***InternalErrorException***
---
- ##### GET /api/company-role/{companyRoleId} - получение роли компании по ID.
###### Логика работы - находит в базе данных роль компании в соответствии с полученным ID через ***companyRoleId*** и возвращает ее.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***companyRoleId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "role": {
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "rolesForUser": "string",
    "addAutomaticly": true
    },
    "user": [
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
    }
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/company-role/ - создание роли компании.
###### Логика работы - создает роль компании и сохраняет ее.
###### Тело запроса -
```js
{
  "roleId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "companyId": "3fa85f64-5717-4562-b3fc-2c963f66afa6"
}
```
###### Параметры запроса - N/A
###### PATH параметры - N/A
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "role": {
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "rolesForUser": "string",
    "addAutomaticly": true
    },
    "user": [
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
    }
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/company-role/{companyRoleId} - обновление роли компании.
###### Логика работы - находит в базе данных роль компании в соответствии с полученным ID через ***companyRoleId***, обновляет в соответствии с телом запроса и возвращает ее.
###### Тело запроса -
```js
{
  "roleId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "companyId": "3fa85f64-5717-4562-b3fc-2c963f66afa6"
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***companyRoleId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "role": {
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "name": "string",
    "rolesForUser": "string",
    "addAutomaticly": true
    },
    "user": [
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
    }
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### DELETE /api/company-role/{companyRoleId} - удаление роли компании.
###### Логика работы - находит в базе данных роль компании в соответствии с полученным ID через ***companyRoleId*** и удаляет ее.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***companyRoleId - UUID***
###### Тело ответа - 
```js
boolean
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
