{
  "info": {
    "name": "Open FinTech Currency by ID",
    "_postman_id": "a414bf88-7594-46f3-9dd4-82466e9258da",
    "description": "Returns currency with specific ID.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Currencies",
      "item": [
        {
          "id": "7f8d63a5-a26d-402d-95e0-e0d99223abac",
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
              "id": "8a523d48-5eb6-426f-9b35-a6b805b03afe"
            }
          ]
        },
        {
          "id": "bc67739c-512d-4e51-9349-49682fb5c38b",
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
              "id": "987d97c3-e1f1-4700-a6d5-9f84cca787fe"
            }
          ]
        }
      ]
    }
  ]
}