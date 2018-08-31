{
  "info": {
    "name": "Open FinTech Bank by ID",
    "_postman_id": "078efe0b-45b4-4d42-90eb-372cde5f1bee",
    "description": "Returns bank with specific ID.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Banks",
      "item": [
        {
          "id": "37882a92-3f91-4087-aef6-96f1b4ce99b1",
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
              "id": "694a7b8a-d6c0-4a14-9352-40648bb3713b"
            }
          ]
        },
        {
          "id": "9f93a860-0412-406b-8f82-056f34cf929d",
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
              "id": "ffcba739-958b-4103-b0ef-6fd3a09eb9fb"
            }
          ]
        }
      ]
    }
  ]
}