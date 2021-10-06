# GetBrand Order Service Documentation

## Order

- ##### GET /api/order/ - получение всего списка заказов.
###### Логика работы - N/A
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - N/A
###### Тело ответа - 
```js
[
    {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "orderNumber": "string",
      "executeStart": "string",
      "executeEnd": "string",
      "type": "string",
      "address": "string",
      "employeeComment": "string",
      "customerComment": "string",
      "createAt": "string",
      "updateAt": "string",
      "volume": 0,
      "includeLoyalityTypes": "string",
      "totalPrice": 0,
      "promo": {
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
      },
      "freePrices": [
        {
          "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
          "name": "string",
          "value": 0
        }
      ],
      "equipments": [
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
      "manager": {
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
      "orderProducts": [
        {
          "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
          "name": "string",
          "count": 0,
          "price": 0,
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
            "string"
          ],
          "modificators": [
            {
              "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
              "name": "string",
              "group": "string",
              "description": "string",
              "price": 0
            }
          ]
        }
      ],
      "state": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "from": [
          "string"
        ],
        "to": "string",
        "auto": true,
        "changeAllow": true,
        "deleteAllow": true
      },
      "bonuses": [
        {
          "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
          "value": 0,
          "userLoyaltys": {
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
        }
      ],
      "review": {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "rating": 0,
        "comment": "string"
      },
      "price": 0,
      "priceWithPromo": 0
    }
]
```
###### Исключения - 
###### ***InternalErrorException***
---
- ##### GET /api/order/{orderId} - получение заказа по ID.
###### Логика работы - находит в базе данных заказ в соответствиии с переданным ID с помощью ***orderId***.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***orderId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "orderNumber": "string",
    "executeStart": "string",
    "executeEnd": "string",
    "type": "string",
    "address": "string",
    "employeeComment": "string",
    "customerComment": "string",
    "createAt": "string",
    "updateAt": "string",
    "volume": 0,
    "includeLoyalityTypes": "string",
    "totalPrice": 0,
    "promo": {
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
    },
    "freePrices": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "value": 0
      }
    ],
    "equipments": [
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
    "manager": {
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
    "orderProducts": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "count": 0,
        "price": 0,
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
          "string"
        ],
        "modificators": [
          {
            "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
            "name": "string",
            "group": "string",
            "description": "string",
            "price": 0
          }
        ]
      }
    ],
    "state": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "name": "string",
      "from": [
        "string"
      ],
      "to": "string",
      "auto": true,
      "changeAllow": true,
      "deleteAllow": true
    },
    "bonuses": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "value": 0,
        "userLoyaltys": {
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
      }
    ],
    "review": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "rating": 0,
      "comment": "string"
    },
    "price": 0,
    "priceWithPromo": 0
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### POST /api/order/ - создание заказа.
###### Логика работы - создает заказ в соответствии с телом запроса и сохраняет его.
###### Тело запроса -
```js
{
  "executeStart": "string",
  "executeEnd": "string",
  "type": "string",
  "volume": 0,
  "stateName": "string",
  "includeLoyalityTypes": "string",
  "address": "string",
  "companyId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "userId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "managerId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "customerComment": "string",
  "employeeComment": "string",
  "companyAddressId": "3fa85f64-5717-4562-b3fc-2c963f66afa6"
}
```
###### Параметры запроса - N/A
###### PATH параметры - N/A
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "orderNumber": "string",
    "executeStart": "string",
    "executeEnd": "string",
    "type": "string",
    "address": "string",
    "employeeComment": "string",
    "customerComment": "string",
    "createAt": "string",
    "updateAt": "string",
    "volume": 0,
    "includeLoyalityTypes": "string",
    "totalPrice": 0,
    "promo": {
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
    },
    "freePrices": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "value": 0
      }
    ],
    "equipments": [
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
    "manager": {
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
    "orderProducts": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "count": 0,
        "price": 0,
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
          "string"
        ],
        "modificators": [
          {
            "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
            "name": "string",
            "group": "string",
            "description": "string",
            "price": 0
          }
        ]
      }
    ],
    "state": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "name": "string",
      "from": [
        "string"
      ],
      "to": "string",
      "auto": true,
      "changeAllow": true,
      "deleteAllow": true
    },
    "bonuses": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "value": 0,
        "userLoyaltys": {
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
      }
    ],
    "review": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "rating": 0,
      "comment": "string"
    },
    "price": 0,
    "priceWithPromo": 0
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### DELETE /api/order/{orderId} - удаление заказа.
###### Логика работы - находит в базе данных заказ в соответствиии с переданным ID с помощью ***orderId*** и удаляет его.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***orderId - UUID***
###### Тело ответа - 
```js
boolean
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/order/user/{orderId} - прикрепление пользователя к заказу.
###### Логика работы - находит в базе данных заказ в соответствиии с переданным ID с помощью ***orderId*** и прикрепляет к нему пользователя из тела запроса.
###### Тело запроса - 
```js
{
  "userId": "3fa85f64-5717-4562-b3fc-2c963f66afa6"
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***orderId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "orderNumber": "string",
    "executeStart": "string",
    "executeEnd": "string",
    "type": "string",
    "address": "string",
    "employeeComment": "string",
    "customerComment": "string",
    "createAt": "string",
    "updateAt": "string",
    "volume": 0,
    "includeLoyalityTypes": "string",
    "totalPrice": 0,
    "promo": {
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
    },
    "freePrices": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "value": 0
      }
    ],
    "equipments": [
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
    "manager": {
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
    "orderProducts": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "count": 0,
        "price": 0,
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
          "string"
        ],
        "modificators": [
          {
            "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
            "name": "string",
            "group": "string",
            "description": "string",
            "price": 0
          }
        ]
      }
    ],
    "state": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "name": "string",
      "from": [
        "string"
      ],
      "to": "string",
      "auto": true,
      "changeAllow": true,
      "deleteAllow": true
    },
    "bonuses": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "value": 0,
        "userLoyaltys": {
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
      }
    ],
    "review": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "rating": 0,
      "comment": "string"
    },
    "price": 0,
    "priceWithPromo": 0
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/order/manager/{orderId} - прикрепление менеджеру к заказу.
###### Логика работы - находит в базе данных заказ в соответствиии с переданным ID с помощью ***orderId*** и прикрепляет к нему менеджера из тела запроса.
###### Тело запроса - 
```js
{
  "userId": "3fa85f64-5717-4562-b3fc-2c963f66afa6"
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***orderId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "orderNumber": "string",
    "executeStart": "string",
    "executeEnd": "string",
    "type": "string",
    "address": "string",
    "employeeComment": "string",
    "customerComment": "string",
    "createAt": "string",
    "updateAt": "string",
    "volume": 0,
    "includeLoyalityTypes": "string",
    "totalPrice": 0,
    "promo": {
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
    },
    "freePrices": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "value": 0
      }
    ],
    "equipments": [
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
    "manager": {
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
    "orderProducts": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "count": 0,
        "price": 0,
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
          "string"
        ],
        "modificators": [
          {
            "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
            "name": "string",
            "group": "string",
            "description": "string",
            "price": 0
          }
        ]
      }
    ],
    "state": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "name": "string",
      "from": [
        "string"
      ],
      "to": "string",
      "auto": true,
      "changeAllow": true,
      "deleteAllow": true
    },
    "bonuses": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "value": 0,
        "userLoyaltys": {
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
      }
    ],
    "review": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "rating": 0,
      "comment": "string"
    },
    "price": 0,
    "priceWithPromo": 0
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/order/state/{orderId} - обновление статуса заказа.
###### Логика работы - находит в базе данных заказ в соответствиии с переданным ID с помощью ***orderId*** и прикрепляет к нему статус из тела запроса.
###### Тело запроса - 
```js
{
  "stateName": "string"
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***orderId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "orderNumber": "string",
    "executeStart": "string",
    "executeEnd": "string",
    "type": "string",
    "address": "string",
    "employeeComment": "string",
    "customerComment": "string",
    "createAt": "string",
    "updateAt": "string",
    "volume": 0,
    "includeLoyalityTypes": "string",
    "totalPrice": 0,
    "promo": {
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
    },
    "freePrices": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "value": 0
      }
    ],
    "equipments": [
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
    "manager": {
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
    "orderProducts": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "count": 0,
        "price": 0,
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
          "string"
        ],
        "modificators": [
          {
            "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
            "name": "string",
            "group": "string",
            "description": "string",
            "price": 0
          }
        ]
      }
    ],
    "state": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "name": "string",
      "from": [
        "string"
      ],
      "to": "string",
      "auto": true,
      "changeAllow": true,
      "deleteAllow": true
    },
    "bonuses": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "value": 0,
        "userLoyaltys": {
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
      }
    ],
    "review": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "rating": 0,
      "comment": "string"
    },
    "price": 0,
    "priceWithPromo": 0
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/order/review/{orderId} - прикрепление рецензии к заказу.
###### Логика работы - находит в базе данных заказ в соответствиии с переданным ID с помощью ***orderId*** и прикрепляет к нему рецензию из тела запроса.
###### Тело запроса - 
```js
{
  "rating": 0,
  "comment": "string"
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***orderId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "orderNumber": "string",
    "executeStart": "string",
    "executeEnd": "string",
    "type": "string",
    "address": "string",
    "employeeComment": "string",
    "customerComment": "string",
    "createAt": "string",
    "updateAt": "string",
    "volume": 0,
    "includeLoyalityTypes": "string",
    "totalPrice": 0,
    "promo": {
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
    },
    "freePrices": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "value": 0
      }
    ],
    "equipments": [
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
    "manager": {
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
    "orderProducts": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "count": 0,
        "price": 0,
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
          "string"
        ],
        "modificators": [
          {
            "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
            "name": "string",
            "group": "string",
            "description": "string",
            "price": 0
          }
        ]
      }
    ],
    "state": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "name": "string",
      "from": [
        "string"
      ],
      "to": "string",
      "auto": true,
      "changeAllow": true,
      "deleteAllow": true
    },
    "bonuses": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "value": 0,
        "userLoyaltys": {
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
      }
    ],
    "review": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "rating": 0,
      "comment": "string"
    },
    "price": 0,
    "priceWithPromo": 0
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### DELETE /api/order/review/{orderId} - удаление рецензии заказа.
###### Логика работы - находит в базе данных заказ в соответствиии с переданным ID с помощью ***orderId*** и удаляет рецензию.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***orderId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "orderNumber": "string",
    "executeStart": "string",
    "executeEnd": "string",
    "type": "string",
    "address": "string",
    "employeeComment": "string",
    "customerComment": "string",
    "createAt": "string",
    "updateAt": "string",
    "volume": 0,
    "includeLoyalityTypes": "string",
    "totalPrice": 0,
    "promo": {
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
    },
    "freePrices": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "value": 0
      }
    ],
    "equipments": [
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
    "manager": {
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
    "orderProducts": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "count": 0,
        "price": 0,
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
          "string"
        ],
        "modificators": [
          {
            "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
            "name": "string",
            "group": "string",
            "description": "string",
            "price": 0
          }
        ]
      }
    ],
    "state": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "name": "string",
      "from": [
        "string"
      ],
      "to": "string",
      "auto": true,
      "changeAllow": true,
      "deleteAllow": true
    },
    "bonuses": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "value": 0,
        "userLoyaltys": {
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
      }
    ],
    "review": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "rating": 0,
      "comment": "string"
    },
    "price": 0,
    "priceWithPromo": 0
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/order/promo/delete/{orderId} - открепление акции от заказа.
###### Логика работы - находит в базе данных заказ в соответствиии с переданным ID с помощью ***orderId*** и открепляет от него акцию.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***orderId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "orderNumber": "string",
    "executeStart": "string",
    "executeEnd": "string",
    "type": "string",
    "address": "string",
    "employeeComment": "string",
    "customerComment": "string",
    "createAt": "string",
    "updateAt": "string",
    "volume": 0,
    "includeLoyalityTypes": "string",
    "totalPrice": 0,
    "promo": {
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
    },
    "freePrices": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "value": 0
      }
    ],
    "equipments": [
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
    "manager": {
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
    "orderProducts": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "count": 0,
        "price": 0,
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
          "string"
        ],
        "modificators": [
          {
            "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
            "name": "string",
            "group": "string",
            "description": "string",
            "price": 0
          }
        ]
      }
    ],
    "state": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "name": "string",
      "from": [
        "string"
      ],
      "to": "string",
      "auto": true,
      "changeAllow": true,
      "deleteAllow": true
    },
    "bonuses": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "value": 0,
        "userLoyaltys": {
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
      }
    ],
    "review": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "rating": 0,
      "comment": "string"
    },
    "price": 0,
    "priceWithPromo": 0
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/order/promo/add/{orderId}/{promoId} - прикрепление акции к заказу.
###### Логика работы - находит в базе данных заказ в соответствиии с переданным ID с помощью ***orderId*** и прикрепляет к нему акцию из строки запроса.
###### Тело запроса - N/A
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***orderId - UUID***
###### ***promoId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "orderNumber": "string",
    "executeStart": "string",
    "executeEnd": "string",
    "type": "string",
    "address": "string",
    "employeeComment": "string",
    "customerComment": "string",
    "createAt": "string",
    "updateAt": "string",
    "volume": 0,
    "includeLoyalityTypes": "string",
    "totalPrice": 0,
    "promo": {
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
    },
    "freePrices": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "value": 0
      }
    ],
    "equipments": [
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
    "manager": {
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
    "orderProducts": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "count": 0,
        "price": 0,
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
          "string"
        ],
        "modificators": [
          {
            "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
            "name": "string",
            "group": "string",
            "description": "string",
            "price": 0
          }
        ]
      }
    ],
    "state": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "name": "string",
      "from": [
        "string"
      ],
      "to": "string",
      "auto": true,
      "changeAllow": true,
      "deleteAllow": true
    },
    "bonuses": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "value": 0,
        "userLoyaltys": {
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
      }
    ],
    "review": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "rating": 0,
      "comment": "string"
    },
    "price": 0,
    "priceWithPromo": 0
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/order/product/delete/{orderId} - открепление продуктов от заказа.
###### Логика работы - находит в базе данных заказ в соответствиии с переданным ID с помощью ***orderId*** и открепляет от него продукты из тела запроса.
###### Тело запроса - 
```js
{
  "orderProductIds": [
    "3fa85f64-5717-4562-b3fc-2c963f66afa6"
  ]
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***orderId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "orderNumber": "string",
    "executeStart": "string",
    "executeEnd": "string",
    "type": "string",
    "address": "string",
    "employeeComment": "string",
    "customerComment": "string",
    "createAt": "string",
    "updateAt": "string",
    "volume": 0,
    "includeLoyalityTypes": "string",
    "totalPrice": 0,
    "promo": {
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
    },
    "freePrices": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "value": 0
      }
    ],
    "equipments": [
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
    "manager": {
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
    "orderProducts": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "count": 0,
        "price": 0,
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
          "string"
        ],
        "modificators": [
          {
            "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
            "name": "string",
            "group": "string",
            "description": "string",
            "price": 0
          }
        ]
      }
    ],
    "state": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "name": "string",
      "from": [
        "string"
      ],
      "to": "string",
      "auto": true,
      "changeAllow": true,
      "deleteAllow": true
    },
    "bonuses": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "value": 0,
        "userLoyaltys": {
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
      }
    ],
    "review": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "rating": 0,
      "comment": "string"
    },
    "price": 0,
    "priceWithPromo": 0
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/order/product/add/{orderId} - прикрепление продукта к заказу.
###### Логика работы - находит в базе данных заказ в соответствиии с переданным ID с помощью ***orderId*** и прикрепляет к нему продукт из тела запроса.
###### Тело запроса - 
```js
{
  "productId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "count": 0,
  "components": [
    "string"
  ],
  "modificators": [
    "string"
  ]
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***orderId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "orderNumber": "string",
    "executeStart": "string",
    "executeEnd": "string",
    "type": "string",
    "address": "string",
    "employeeComment": "string",
    "customerComment": "string",
    "createAt": "string",
    "updateAt": "string",
    "volume": 0,
    "includeLoyalityTypes": "string",
    "totalPrice": 0,
    "promo": {
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
    },
    "freePrices": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "value": 0
      }
    ],
    "equipments": [
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
    "manager": {
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
    "orderProducts": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "count": 0,
        "price": 0,
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
          "string"
        ],
        "modificators": [
          {
            "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
            "name": "string",
            "group": "string",
            "description": "string",
            "price": 0
          }
        ]
      }
    ],
    "state": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "name": "string",
      "from": [
        "string"
      ],
      "to": "string",
      "auto": true,
      "changeAllow": true,
      "deleteAllow": true
    },
    "bonuses": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "value": 0,
        "userLoyaltys": {
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
      }
    ],
    "review": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "rating": 0,
      "comment": "string"
    },
    "price": 0,
    "priceWithPromo": 0
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/order/product/add-many/{orderId} - прикрепление продуктов к заказу.
###### Логика работы - находит в базе данных заказ в соответствиии с переданным ID с помощью ***orderId*** и прикрепляет к нему продукты из тела запроса.
###### Тело запроса - 
```js
[
    {
    "productId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "count": 0,
    "components": [
        "string"
    ],
    "modificators": [
        "string"
    ]
    }
]
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***orderId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "orderNumber": "string",
    "executeStart": "string",
    "executeEnd": "string",
    "type": "string",
    "address": "string",
    "employeeComment": "string",
    "customerComment": "string",
    "createAt": "string",
    "updateAt": "string",
    "volume": 0,
    "includeLoyalityTypes": "string",
    "totalPrice": 0,
    "promo": {
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
    },
    "freePrices": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "value": 0
      }
    ],
    "equipments": [
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
    "manager": {
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
    "orderProducts": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "count": 0,
        "price": 0,
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
          "string"
        ],
        "modificators": [
          {
            "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
            "name": "string",
            "group": "string",
            "description": "string",
            "price": 0
          }
        ]
      }
    ],
    "state": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "name": "string",
      "from": [
        "string"
      ],
      "to": "string",
      "auto": true,
      "changeAllow": true,
      "deleteAllow": true
    },
    "bonuses": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "value": 0,
        "userLoyaltys": {
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
      }
    ],
    "review": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "rating": 0,
      "comment": "string"
    },
    "price": 0,
    "priceWithPromo": 0
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/order/price/add/{orderId} - прикрепление свободной позиции к заказу.
###### Логика работы - находит в базе данных заказ в соответствиии с переданным ID с помощью ***orderId*** и прикрепляет к нему свободную позицию из тела запроса.
###### Тело запроса - 
```js
{
  "name": "string",
  "value": 0
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***orderId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "orderNumber": "string",
    "executeStart": "string",
    "executeEnd": "string",
    "type": "string",
    "address": "string",
    "employeeComment": "string",
    "customerComment": "string",
    "createAt": "string",
    "updateAt": "string",
    "volume": 0,
    "includeLoyalityTypes": "string",
    "totalPrice": 0,
    "promo": {
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
    },
    "freePrices": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "value": 0
      }
    ],
    "equipments": [
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
    "manager": {
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
    "orderProducts": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "count": 0,
        "price": 0,
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
          "string"
        ],
        "modificators": [
          {
            "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
            "name": "string",
            "group": "string",
            "description": "string",
            "price": 0
          }
        ]
      }
    ],
    "state": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "name": "string",
      "from": [
        "string"
      ],
      "to": "string",
      "auto": true,
      "changeAllow": true,
      "deleteAllow": true
    },
    "bonuses": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "value": 0,
        "userLoyaltys": {
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
      }
    ],
    "review": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "rating": 0,
      "comment": "string"
    },
    "price": 0,
    "priceWithPromo": 0
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/order/price/delete/{orderId}/{priceId} - открепление свободной позиции к заказу.
###### Логика работы - находит в базе данных заказ в соответствиии с переданным ID с помощью ***orderId*** и открепляет от него свободную позицию из тела запроса.
###### Тело запроса - 
```js
{
  "name": "string",
  "value": 0
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***orderId - UUID***
###### ***priceId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "orderNumber": "string",
    "executeStart": "string",
    "executeEnd": "string",
    "type": "string",
    "address": "string",
    "employeeComment": "string",
    "customerComment": "string",
    "createAt": "string",
    "updateAt": "string",
    "volume": 0,
    "includeLoyalityTypes": "string",
    "totalPrice": 0,
    "promo": {
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
    },
    "freePrices": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "value": 0
      }
    ],
    "equipments": [
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
    "manager": {
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
    "orderProducts": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "count": 0,
        "price": 0,
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
          "string"
        ],
        "modificators": [
          {
            "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
            "name": "string",
            "group": "string",
            "description": "string",
            "price": 0
          }
        ]
      }
    ],
    "state": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "name": "string",
      "from": [
        "string"
      ],
      "to": "string",
      "auto": true,
      "changeAllow": true,
      "deleteAllow": true
    },
    "bonuses": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "value": 0,
        "userLoyaltys": {
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
      }
    ],
    "review": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "rating": 0,
      "comment": "string"
    },
    "price": 0,
    "priceWithPromo": 0
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/order/gift/{orderId} - прикрепление подарка к заказу.
###### Логика работы - находит в базе данных заказ в соответствиии с переданным ID с помощью ***orderId*** и прикрепляет к нему подарок из тела запроса.
###### Тело запроса - 
```js
{
  "giftId": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "count": 0
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***orderId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "orderNumber": "string",
    "executeStart": "string",
    "executeEnd": "string",
    "type": "string",
    "address": "string",
    "employeeComment": "string",
    "customerComment": "string",
    "createAt": "string",
    "updateAt": "string",
    "volume": 0,
    "includeLoyalityTypes": "string",
    "totalPrice": 0,
    "promo": {
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
    },
    "freePrices": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "value": 0
      }
    ],
    "equipments": [
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
    "manager": {
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
    "orderProducts": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "count": 0,
        "price": 0,
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
          "string"
        ],
        "modificators": [
          {
            "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
            "name": "string",
            "group": "string",
            "description": "string",
            "price": 0
          }
        ]
      }
    ],
    "state": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "name": "string",
      "from": [
        "string"
      ],
      "to": "string",
      "auto": true,
      "changeAllow": true,
      "deleteAllow": true
    },
    "bonuses": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "value": 0,
        "userLoyaltys": {
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
      }
    ],
    "review": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "rating": 0,
      "comment": "string"
    },
    "price": 0,
    "priceWithPromo": 0
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/order/equipments/add/{orderId} - прикрепление эквипмента к заказу.
###### Логика работы - находит в базе данных заказ в соответствиии с переданным ID с помощью ***orderId*** и прикрепляет к нему эквипмент из тела запроса.
###### Тело запроса - 
```js
{
  "equipmentIds": [
    "string"
  ]
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***orderId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "orderNumber": "string",
    "executeStart": "string",
    "executeEnd": "string",
    "type": "string",
    "address": "string",
    "employeeComment": "string",
    "customerComment": "string",
    "createAt": "string",
    "updateAt": "string",
    "volume": 0,
    "includeLoyalityTypes": "string",
    "totalPrice": 0,
    "promo": {
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
    },
    "freePrices": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "value": 0
      }
    ],
    "equipments": [
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
    "manager": {
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
    "orderProducts": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "count": 0,
        "price": 0,
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
          "string"
        ],
        "modificators": [
          {
            "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
            "name": "string",
            "group": "string",
            "description": "string",
            "price": 0
          }
        ]
      }
    ],
    "state": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "name": "string",
      "from": [
        "string"
      ],
      "to": "string",
      "auto": true,
      "changeAllow": true,
      "deleteAllow": true
    },
    "bonuses": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "value": 0,
        "userLoyaltys": {
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
      }
    ],
    "review": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "rating": 0,
      "comment": "string"
    },
    "price": 0,
    "priceWithPromo": 0
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/order/equipments/delete/{orderId} - открепление эквипмента к заказу.
###### Логика работы - находит в базе данных заказ в соответствиии с переданным ID с помощью ***orderId*** и открепляет от него эквипмент из тела запроса.
###### Тело запроса - 
```js
{
  "equipmentIds": [
    "string"
  ]
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***orderId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "orderNumber": "string",
    "executeStart": "string",
    "executeEnd": "string",
    "type": "string",
    "address": "string",
    "employeeComment": "string",
    "customerComment": "string",
    "createAt": "string",
    "updateAt": "string",
    "volume": 0,
    "includeLoyalityTypes": "string",
    "totalPrice": 0,
    "promo": {
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
    },
    "freePrices": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "value": 0
      }
    ],
    "equipments": [
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
    "manager": {
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
    "orderProducts": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "count": 0,
        "price": 0,
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
          "string"
        ],
        "modificators": [
          {
            "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
            "name": "string",
            "group": "string",
            "description": "string",
            "price": 0
          }
        ]
      }
    ],
    "state": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "name": "string",
      "from": [
        "string"
      ],
      "to": "string",
      "auto": true,
      "changeAllow": true,
      "deleteAllow": true
    },
    "bonuses": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "value": 0,
        "userLoyaltys": {
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
      }
    ],
    "review": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "rating": 0,
      "comment": "string"
    },
    "price": 0,
    "priceWithPromo": 0
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/order/employee-comment/{orderId} - прикрепление комментария к заказу.
###### Логика работы - находит в базе данных заказ в соответствиии с переданным ID с помощью ***orderId*** и прикрепляет к нему комментарий из тела запроса.
###### Тело запроса - 
```js
{
  "employeeComment": "string"
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***orderId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "orderNumber": "string",
    "executeStart": "string",
    "executeEnd": "string",
    "type": "string",
    "address": "string",
    "employeeComment": "string",
    "customerComment": "string",
    "createAt": "string",
    "updateAt": "string",
    "volume": 0,
    "includeLoyalityTypes": "string",
    "totalPrice": 0,
    "promo": {
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
    },
    "freePrices": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "value": 0
      }
    ],
    "equipments": [
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
    "manager": {
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
    "orderProducts": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "count": 0,
        "price": 0,
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
          "string"
        ],
        "modificators": [
          {
            "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
            "name": "string",
            "group": "string",
            "description": "string",
            "price": 0
          }
        ]
      }
    ],
    "state": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "name": "string",
      "from": [
        "string"
      ],
      "to": "string",
      "auto": true,
      "changeAllow": true,
      "deleteAllow": true
    },
    "bonuses": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "value": 0,
        "userLoyaltys": {
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
      }
    ],
    "review": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "rating": 0,
      "comment": "string"
    },
    "price": 0,
    "priceWithPromo": 0
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/order/bonuses/add/{orderId} - прикрепление бонуса к заказу.
###### Логика работы - находит в базе данных заказ в соответствиии с переданным ID с помощью ***orderId*** и прикрепляет к нему бонус из тела запроса.
###### Тело запроса - 
```js
{
  "value": 0,
  "userLoyalityId": "3fa85f64-5717-4562-b3fc-2c963f66afa6"
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***orderId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "orderNumber": "string",
    "executeStart": "string",
    "executeEnd": "string",
    "type": "string",
    "address": "string",
    "employeeComment": "string",
    "customerComment": "string",
    "createAt": "string",
    "updateAt": "string",
    "volume": 0,
    "includeLoyalityTypes": "string",
    "totalPrice": 0,
    "promo": {
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
    },
    "freePrices": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "value": 0
      }
    ],
    "equipments": [
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
    "manager": {
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
    "orderProducts": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "count": 0,
        "price": 0,
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
          "string"
        ],
        "modificators": [
          {
            "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
            "name": "string",
            "group": "string",
            "description": "string",
            "price": 0
          }
        ]
      }
    ],
    "state": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "name": "string",
      "from": [
        "string"
      ],
      "to": "string",
      "auto": true,
      "changeAllow": true,
      "deleteAllow": true
    },
    "bonuses": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "value": 0,
        "userLoyaltys": {
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
      }
    ],
    "review": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "rating": 0,
      "comment": "string"
    },
    "price": 0,
    "priceWithPromo": 0
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***
---
- ##### PATCH /api/order/bonuses/delete/{orderId} - открепление бонуса к заказу.
###### Логика работы - находит в базе данных заказ в соответствиии с переданным ID с помощью ***orderId*** и открепляет от него бонус из тела запроса.
###### Тело запроса - 
```js
{
  "bonusIds": [
    "3fa85f64-5717-4562-b3fc-2c963f66afa6"
  ]
}
```
###### Параметры запроса - N/A
###### PATH параметры - 
###### ***orderId - UUID***
###### Тело ответа - 
```js
{
    "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
    "orderNumber": "string",
    "executeStart": "string",
    "executeEnd": "string",
    "type": "string",
    "address": "string",
    "employeeComment": "string",
    "customerComment": "string",
    "createAt": "string",
    "updateAt": "string",
    "volume": 0,
    "includeLoyalityTypes": "string",
    "totalPrice": 0,
    "promo": {
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
    },
    "freePrices": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "value": 0
      }
    ],
    "equipments": [
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
    "manager": {
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
    "orderProducts": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "name": "string",
        "count": 0,
        "price": 0,
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
          "string"
        ],
        "modificators": [
          {
            "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
            "name": "string",
            "group": "string",
            "description": "string",
            "price": 0
          }
        ]
      }
    ],
    "state": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "name": "string",
      "from": [
        "string"
      ],
      "to": "string",
      "auto": true,
      "changeAllow": true,
      "deleteAllow": true
    },
    "bonuses": [
      {
        "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
        "value": 0,
        "userLoyaltys": {
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
      }
    ],
    "review": {
      "id": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
      "rating": 0,
      "comment": "string"
    },
    "price": 0,
    "priceWithPromo": 0
}
```
###### Исключения - 
###### ***InternalErrorException***
###### ***NotFoundException***
###### ***InvalidDataException***