{
  "info": {
    "name": "Open FinTech List of countries",
    "_postman_id": "9340c29a-3189-4a57-b3c3-ca9ee8d96913",
    "description": "Returns all available countries.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Countries",
      "item": [
        {
          "id": "c6372525-7b9b-41f8-b4e5-8ef51d807a26",
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
              "id": "c2bc4201-ab99-456d-9859-c24160e785af"
            }
          ]
        }
      ]
    }
  ]
}