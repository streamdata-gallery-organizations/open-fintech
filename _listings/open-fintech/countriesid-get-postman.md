{
  "info": {
    "name": "Open FinTech Country by ID",
    "_postman_id": "def99468-3fa2-466f-a893-db1f37e23817",
    "description": "Returns country with specific ID.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Countries",
      "item": [
        {
          "id": "9444e013-7cde-4d26-bec9-1d42e1bb2ac5",
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
              "id": "8cbd3205-86f0-4b7d-acb1-91cf6f25fa0f"
            }
          ]
        },
        {
          "id": "01bc45c9-6c0d-4c0a-bd18-3f8bd0af8050",
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
              "id": "579c9cb4-9f87-42d0-b6a3-10fa35c4bbe7"
            }
          ]
        }
      ]
    }
  ]
}