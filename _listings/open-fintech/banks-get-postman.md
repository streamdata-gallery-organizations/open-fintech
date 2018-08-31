{
  "info": {
    "name": "Open FinTech List of banks",
    "_postman_id": "50b8a132-f562-47ef-8c7e-12033f7cdf52",
    "description": "Returns list of banks. Each object contains general information about bank such as name and status, also information about bank details and related link to main organization.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Banks",
      "item": [
        {
          "id": "f0390c0e-345f-4992-b4bb-5e6ad18ffbeb",
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
              "id": "11ae57c7-6b01-4ae0-ab38-84465f0e8c7c"
            }
          ]
        }
      ]
    }
  ]
}