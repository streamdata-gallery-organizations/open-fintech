{
  "info": {
    "name": "Open FinTech List of currencies",
    "_postman_id": "25bce0d9-1066-4a0a-8878-4f3ea2600fd3",
    "description": "Returns all available currencies.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Currencies",
      "item": [
        {
          "id": "29c5609d-33e1-4ccf-b904-58a3b2b1c79f",
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
              "id": "9d639f2e-5a69-45e2-9927-535629c25a40"
            }
          ]
        }
      ]
    }
  ]
}