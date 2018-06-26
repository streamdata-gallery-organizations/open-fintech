{
  "info": {
    "name": "Open FinTech List of exchangers",
    "_postman_id": "bfd36b96-0f10-4a86-b66a-0dd8fa0d6cd1",
    "description": "Returns list of exchange markets. Each object contains general information about exchanger such as name and status, also information about rates export and related link to main organization.<br>\nRates export standards is represented by:\n* [estandards](http://estandards.info)\n* [jsons](http://jsons.info)\n* ratex - our internal standard",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Banks",
      "item": [
        {
          "id": "571ffc48-fab6-45ae-b97e-3e9716a2b63f",
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
              "id": "fa8aa57a-97b3-43c8-b25b-fce33c1f6380"
            }
          ]
        },
        {
          "id": "fb40e383-979c-4c51-9dde-c4f60e0b39c7",
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
              "id": "0a3ad00c-9bd7-4f65-ab72-f0580391c873"
            }
          ]
        }
      ]
    },
    {
      "name": "Countries",
      "item": [
        {
          "id": "b35713d6-4f4f-48a0-8f07-bf59eb31dc13",
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
              "id": "7628a818-6ef8-4cf8-9b3b-c10d65f27736"
            }
          ]
        },
        {
          "id": "3cd25e7c-de0c-4259-b6b0-5d9c32ffbcd2",
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
              "id": "3465d8e0-83a2-421c-b585-fdf067f8c42d"
            }
          ]
        }
      ]
    },
    {
      "name": "Currencies",
      "item": [
        {
          "id": "4071b2b3-1768-460f-918f-c59807922dee",
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
              "id": "7f9173bc-7c58-49ae-a8cf-9e6565f96670"
            }
          ]
        },
        {
          "id": "4d192f47-1a3c-421b-9d53-3134a03a3769",
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
              "id": "8851da61-c82e-4974-b163-6d360ccdf109"
            }
          ]
        }
      ]
    },
    {
      "name": "Exchangers",
      "item": [
        {
          "id": "34173788-18a6-43bc-bccb-cb0f6d29a6af",
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
              "id": "294b50e1-c75a-40d3-9f56-4568ebe3e884"
            }
          ]
        }
      ]
    }
  ]
}