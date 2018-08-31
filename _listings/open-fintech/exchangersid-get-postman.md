{
  "info": {
    "name": "Open FinTech Exchanger by ID",
    "_postman_id": "63fc283d-9e1c-4232-a082-08acc66958bb",
    "description": "Returns exchanger with specific ID.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Banks",
      "item": [
        {
          "id": "2ae264ce-46db-4bf9-b2f7-609e1e1396b1",
          "name": "banks.get",
          "request": {
            "url": "http://api.openfintech.io/v1/banks?filter[sort_code]=%7B%7D&filter[status]=%7B%7D&No Name=%7B%7D&sort=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns list of banks. Each object contains general information about bank such as name and status, also information about bank details and related link to main organization."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "93bfda4e-f650-458c-a446-0d20f71c885c"
            }
          ]
        },
        {
          "id": "3a6be24a-b9fa-49e1-926a-6ea949963e02",
          "name": "banks.id.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.openfintech.io",
              "path": [
                "v1",
                "banks/:id"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns bank with specific ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bbeea6bd-338e-47f9-bcb9-c3d00c2d8368"
            }
          ]
        }
      ]
    },
    {
      "name": "Countries",
      "item": [
        {
          "id": "8542601e-1598-46cc-a667-bb0afd38eacf",
          "name": "countries.get",
          "request": {
            "url": "http://api.openfintech.io/v1/countries?filter[region]=%7B%7D&filter[sub_region]=%7B%7D&No Name=%7B%7D&sort=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns all available countries."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8a79af6f-ddcf-4673-9030-c5f13efb1f0e"
            }
          ]
        },
        {
          "id": "684b4537-7a8b-47ca-8a87-2e71e6aff67c",
          "name": "countries.id.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.openfintech.io",
              "path": [
                "v1",
                "countries/:id"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns country with specific ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3ff339a3-5750-4be8-8de3-bbf21b05eaa9"
            }
          ]
        }
      ]
    },
    {
      "name": "Currencies",
      "item": [
        {
          "id": "b03e0efb-476d-45ea-a0c4-f6fff355dd9f",
          "name": "currencies.get",
          "request": {
            "url": "http://api.openfintech.io/v1/currencies?filter[category]=%7B%7D&filter[code_estandards_alpha]=%7B%7D&filter[code_iso_alpha3]=%7B%7D&filter[code_iso_numeric3]=%7B%7D&filter[currency_type]=%7B%7D&filter[search]=%7B%7D&No Name=%7B%7D&sort=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns all available currencies."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3d05f2a7-b8b0-4df5-aa82-3507b8d84e0e"
            }
          ]
        },
        {
          "id": "a012ed7d-5f31-4a21-8611-f27e736a553a",
          "name": "currencies.id.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.openfintech.io",
              "path": [
                "v1",
                "currencies/:id"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns currency with specific ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "114230db-6524-4615-a320-df09b05cb5c4"
            }
          ]
        }
      ]
    },
    {
      "name": "Exchangers",
      "item": [
        {
          "id": "0a5d14f1-13ff-4462-baa9-b9b9cbef1c9a",
          "name": "exchangers.get",
          "request": {
            "url": "http://api.openfintech.io/v1/exchangers?No Name=%7B%7D&sort=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns list of exchange markets. Each object contains general information about exchanger such as name and status, also information about rates export and related link to main organization.<br>\nRates export standards is represented by:\n* [estandards](http://estandards.info)\n* [jsons](http://jsons.info)\n* ratex - our internal standard"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d36ecc4c-0488-4cee-8085-2b16080693a7"
            }
          ]
        },
        {
          "id": "b0b80616-ef1f-4691-bf20-eb85c940185c",
          "name": "exchangers.id.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.openfintech.io",
              "path": [
                "v1",
                "exchangers/:id"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns exchanger with specific ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c0147980-5e4e-4eeb-b993-ddefc3d68dfa"
            }
          ]
        }
      ]
    }
  ]
}