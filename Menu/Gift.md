# GetBrand Menu Service Documentation

## Gift

- ##### GET /api/gift/ - получение всего списка подарков.
###### Логика работы - N/A
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - N/A
###### Тело ответа - 
```js
[
    {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "count": 0,
      "product": {
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
      },
      "components": [
        {
          "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
          "product": {
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
        }
      ],
      "modificators": [
        {
          "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
          "productModificator": {
            "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
            "name": "string",
            "group": "string",
            "description": "string",
            "price": 0
          }
        }
      ],
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
      "promocode": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "customName": "string",
        "code": "string",
        "type": "string",
        "targetComponent": "string",
        "count": 0,
        "expire": "string",
        "createdAt": "string",
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
        "active": true,
        "unlimited": true
      }
    }
]
```
###### Исключения - 
###### ***InternalErrorException***
---
- ##### GET /api/gift/{giftId} - получение подарка по ID.
###### Логика работы - находит в базе данных подарок в соответствиии с переданным ID с помощью ***giftId***.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***giftId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "count": 0,
    "product": {
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
    },
    "components": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "product": {
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
      }
    ],
    "modificators": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "productModificator": {
          "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
          "name": "string",
          "group": "string",
          "description": "string",
          "price": 0
        }
      }
    ],
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
    "promocode": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "name": "string",
      "customName": "string",
      "code": "string",
      "type": "string",
      "targetComponent": "string",
      "count": 0,
      "expire": "string",
      "createdAt": "string",
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
      "active": true,
      "unlimited": true
    }
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### POST /api/gift/ - создание подарка.
###### Логика работы - создает подарок в соответствии с телом запроса и сохраняет его.
###### Тело запроса -
```js
{
  "productId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "userId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "companyId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "count": 0
}
```
###### Параметры запроса - N/A
###### PATH параметры - N/A
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "count": 0,
    "product": {
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
    },
    "components": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "product": {
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
      }
    ],
    "modificators": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "productModificator": {
          "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
          "name": "string",
          "group": "string",
          "description": "string",
          "price": 0
        }
      }
    ],
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
    "promocode": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "name": "string",
      "customName": "string",
      "code": "string",
      "type": "string",
      "targetComponent": "string",
      "count": 0,
      "expire": "string",
      "createdAt": "string",
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
      "active": true,
      "unlimited": true
    }
  }
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### DELETE /api/gift/{giftId}/{count} - удаление подарка.
###### Логика работы - находит в базе данных подарок в соответствиии с переданным ID с помощью ***giftId*** и удаляет его. Если ***count*** больше, чем количество, указанное в подарке, то подарок удалится полностью, если нет - отнимется указанное количество от подарка.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***giftId - UUID***
###### ***count - int***
###### Тело ответа - 
```js
boolean
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***