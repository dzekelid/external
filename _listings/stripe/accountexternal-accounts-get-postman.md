{
  "info": {
    "name": "Stripe Get Account External Accounts",
    "_postman_id": "360ea530-8230-4d5a-8c6b-42cd5b1d8a68",
    "description": "Get Account, External, Accounts",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Account",
      "item": [
        {
          "id": "bfbabdb4-7e70-4013-8668-8c17feaed1a5",
          "name": "getAccountExternalAccounts",
          "request": {
            "url": "http://api.stripe.com/v1/account/external_accounts?ending_before=%7B%7D&expand=%7B%7D&limit=%7B%7D&starting_after=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Account, External, Accounts"
          },
          "response": [
            {
              "code": 200,
              "name": "Response_200",
              "id": "88f279c9-9edb-4103-94f2-c014680dfbe7"
            }
          ]
        }
      ]
    }
  ]
}