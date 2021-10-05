# GetBrand Loyalty Service Documentation

## User Loyalty

- ##### GET /api/user-loyality/ - получение всего списка лояльностей пользователей.
###### Логика работы - N/A
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - N/A
###### Тело ответа - 
```js
[
    [
    {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "value": 0,
      "summ": 0,
      "loyalityCount": 0,
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
      },
      "user": {
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
      },
      "grade": {
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
    }
  ]
]
```
###### Исключения - 
###### ***InternalErrorException***
---
- ##### GET /api/user-loyality/{loyaltyId} - получение лояльности пользователя по ID.
###### Логика работы - находит в базе данных роль в соответствиии с переданным ID с помощью ***loyaltyId***.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***loyaltyId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "value": 0,
    "summ": 0,
    "loyalityCount": 0,
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
    },
    "user": {
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
    },
    "grade": {
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
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### POST /api/user-loyality/ - создание лояльности пользователя.
###### Логика работы - создает лояльность пользователя в соответствии с телом запроса и сохраняет ее.
###### Тело запроса -
```js
{
  "user": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "companyLoyalty": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "grade": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "value": 0
}
```
###### Параметры запроса - N/A
###### PATH параметры - N/A
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "value": 0,
    "summ": 0,
    "loyalityCount": 0,
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
    },
    "user": {
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
    },
    "grade": {
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
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/user-loyality/{loyaltyId} - обновление лояльности пользователя.
###### Логика работы - находит лояльность пользователя в соответствии с ID переданным через ***loyaltyId***, обновляет ее в соответствии с телом запроса и сохраняет.
###### Тело запроса -
```js
{
  "user": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "companyLoyalty": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "grade": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "value": 0
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***loyaltyId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "value": 0,
    "summ": 0,
    "loyalityCount": 0,
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
    },
    "user": {
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
    },
    "grade": {
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
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### DELETE /api/user-loyality/{loyaltyId} - удаление лояльности пользователя.
###### Логика работы - находит в базе данных лояльность пользоваетля в соответствиии с переданным ID с помощью ***loyaltyId*** и удаляет ее.
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