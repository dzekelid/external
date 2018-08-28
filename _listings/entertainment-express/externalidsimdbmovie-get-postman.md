{
  "info": {
    "name": "Entertainment Express Returns list of all MovieId, IMDB Id pairs.",
    "_postman_id": "d8f3f9f0-84d3-480b-bdd4-7278fe1e668d",
    "description": "Ingest this ID map to create connections between the objects in your existing database with an IMDB ID to the IVA Movie objects.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Analytics",
      "item": [
        {
          "id": "f2c424fc-d066-436c-8682-be16efa2b951",
          "name": "GetAnalyticsViewersByCity",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/City/?DateValue=%7B%7D&End=%7B%7D&Limit=%7B%7D&ReportTag=%7B%7D&Start=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "No required parameters, DateValue defaults to Today.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "21f005c0-3d65-4b06-a3f1-6778b7ae556a"
            }
          ]
        },
        {
          "id": "ef901b19-3d8f-42ec-8ac8-2e022b3c8b88",
          "name": "GetAnalyticsViewersByCountry",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/Country/?DateValue=%7B%7D&End=%7B%7D&Limit=%7B%7D&ReportTag=%7B%7D&Start=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "No required parameters, DateValue defaults to Today."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "858d67dc-7c94-464b-8e4b-b3387a752e69"
            }
          ]
        },
        {
          "id": "f3267f16-bd8d-4d1c-a005-454541619c5b",
          "name": "GetAnalyticEngagementActions",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/EngagementActions/?DateValue=%7B%7D&End=%7B%7D&Limit=%7B%7D&ReportTag=%7B%7D&Start=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "No required parameters, DateValue defaults to Today."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a8462315-c7dc-4931-b53e-3010f64f9eee"
            }
          ]
        },
        {
          "id": "1dd6c1eb-232d-4cd1-82d2-1456ce98153e",
          "name": "GetAnalyticsEngagementTimes",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/EngagementTimes/?DateValue=%7B%7D&End=%7B%7D&Limit=%7B%7D&ReportTag=%7B%7D&Start=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "No required parameters, DateValue defaults to Today."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5f5a798b-11a4-4948-a78d-71d951948af1"
            }
          ]
        },
        {
          "id": "f25f38a1-3cda-4a9f-b541-1e602411fcf9",
          "name": "GetAnalyticsGBUsage",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/GBUsage/?Month=%7B%7D&ReportTag=%7B%7D&Year=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Requires a valid Customer ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fd339003-cbb7-4d29-bd5a-b494ff3b6ab7"
            }
          ]
        },
        {
          "id": "76bd871c-3237-4a4c-8b07-694e760823f5",
          "name": "GetAnalyticsMostActive",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/MostActive/?DateValue=%7B%7D&Limit=%7B%7D&ReportTag=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "No required parameters, DateValue defaults to Today."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2728e985-7043-48ab-9417-a2e51ec75177"
            }
          ]
        },
        {
          "id": "77b03310-9f7c-4189-adc6-cf40714c418b",
          "name": "GetAnalyticsViewersByPlatformHardware",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/PlatformHardware/?DateValue=%7B%7D&End=%7B%7D&Limit=%7B%7D&ReportTag=%7B%7D&Start=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "No required parameters, DateValue defaults to Today."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0191f50a-43f7-4bb1-9f0d-253bbb999bbc"
            }
          ]
        },
        {
          "id": "1b7ceaa5-0a3e-40ae-b442-2e2a4bb636c6",
          "name": "GetAnalyticsViewersByPlatformOS",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/PlatformOS/?DateValue=%7B%7D&End=%7B%7D&Limit=%7B%7D&ReportTag=%7B%7D&Start=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "No required parameters, DateValue defaults to Today."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eb57794b-81ce-41f3-aa40-e4889c6888cb"
            }
          ]
        },
        {
          "id": "eec275fb-c724-4932-b102-d0ee105877a3",
          "name": "GetAnalyticsRecentVisitors",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/RecentVisitors/?Limit=%7B%7D&ReportTag=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "No required parameters, DateValue defaults to Today."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0c53fd6c-9819-41b4-b271-ce3c06004f20"
            }
          ]
        },
        {
          "id": "a5762c04-d80f-41f7-90b2-4bda6f0ccae8",
          "name": "GetAnalyticsSummary",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/Summary/?DateValue=%7B%7D&ReportTag=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Requires a valid Customer ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "225898b6-4e88-42ca-8fd6-3609004db9ca"
            }
          ]
        },
        {
          "id": "655001ee-b331-428d-92fd-9639bbdff0a7",
          "name": "GetAnalyticsTitleReport",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/TitleReport/?End=%7B%7D&PublishedId=%7B%7D&Start=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Requires a valid published ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "907e6f3f-1c06-4d25-8e20-0edfc93c1afd"
            }
          ]
        },
        {
          "id": "5cd9489f-77cf-4e17-a390-31039f350320",
          "name": "GetAnalyticsViewsByVideoLog",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/VideoLog/?DateValue=%7B%7D&End=%7B%7D&Limit=%7B%7D&ReportTag=%7B%7D&Start=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "No required parameters, DateValue defaults to Today."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8a9ce14c-b029-4560-a0c8-851cb8ba58d8"
            }
          ]
        },
        {
          "id": "c2c7f3fc-23a6-4e13-86c1-b47901c2a3b2",
          "name": "GetAnalyticsViewers",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/Viewers/?DateValue=%7B%7D&ReportTag=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Optional DateValue for length of report."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f3a66440-bb90-4059-88df-d22d0bb6ed87"
            }
          ]
        },
        {
          "id": "3c2a0cca-614d-4137-ae78-0b0eed47ec81",
          "name": "GetAnalyticsViews",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/Views/?DateValue=%7B%7D&ReportTag=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Optional DateValue for length of report."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0944d43b-a136-40f0-9a0b-95d3e0bfca14"
            }
          ]
        },
        {
          "id": "2f537cd1-ef25-4fb7-aaa4-6a94571e82ca",
          "name": "GetAnalyticsViewersByWebBrowsers",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/WebBrowsers/?DateValue=%7B%7D&End=%7B%7D&Limit=%7B%7D&ReportTag=%7B%7D&Start=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "No required parameters, DateValue defaults to Today."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cc8c911b-483b-4d38-9432-a28870eff037"
            }
          ]
        }
      ]
    },
    {
      "name": "Changes",
      "item": [
        {
          "id": "2c6748b6-40bf-4877-b804-2c0e397a25f4",
          "name": "GetEpisodeChangeHistory",
          "request": {
            "url": "http://ee.iva-api.com/Changes/Episodes/History/?Date=%7B%7D&Skip=%7B%7D&Take=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "For each updated episode ID, pull the full episode data for that ID and update."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7fc55ae0-f3cc-4820-b449-b6abe79a385e"
            }
          ]
        },
        {
          "id": "c410d1b2-3bff-445d-8285-ad8c807bc83f",
          "name": "GetEpisodeChangeHistoryWithEntity",
          "request": {
            "url": "http://ee.iva-api.com/Changes/Episodes/HistoryWithEntity/?Date=%7B%7D&Skip=%7B%7D&Take=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Lists each episode ID that has changed as well as the entity in the object that changed."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "61f6fd30-0e21-4954-a2a6-b782cdf259f7"
            }
          ]
        },
        {
          "id": "c27ae2f2-29ba-4515-8289-be3b9296d89e",
          "name": "GetMovieChangeHistory",
          "request": {
            "url": "http://ee.iva-api.com/Changes/Movies/History/?Date=%7B%7D&Skip=%7B%7D&Take=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Use to get the ID's of the movies that have been added or changed and use /Movies/{ID} to get back the object with the updated data and replace in your database."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b4de4c14-89bf-4a6f-9e26-c9a8054c8295"
            }
          ]
        },
        {
          "id": "8aa89b6d-a9c6-409a-93af-b7c5766d36e9",
          "name": "GetMovieChangeHistoryWithEntity",
          "request": {
            "url": "http://ee.iva-api.com/Changes/Movies/HistoryWithEntity/?Date=%7B%7D&Skip=%7B%7D&Take=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Same as /Changes/Movies/History but with the specific entities that have changed inside the MovieResponse."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fdaa6fe4-b176-4b64-9e5b-093214a92680"
            }
          ]
        },
        {
          "id": "1c9dbf7a-a97c-46f0-b4d4-96ac50770d77",
          "name": "GetPersonChangeHistory",
          "request": {
            "url": "http://ee.iva-api.com/Changes/People/History/?Date=%7B%7D&Skip=%7B%7D&Take=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Requires a valid Date."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dc955a53-c5a4-4a8d-b6e4-6e3820860368"
            }
          ]
        },
        {
          "id": "c9010e41-bc47-4b30-aeb8-6b77bbc8f001",
          "name": "GetPersonChangeHistoryWithEntity",
          "request": {
            "url": "http://ee.iva-api.com/Changes/People/HistoryWithEntity/?Date=%7B%7D&Skip=%7B%7D&Take=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Requires a valid Date."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3ace7163-b0dc-4590-95f9-459fb3a5c408"
            }
          ]
        },
        {
          "id": "953c7a17-f313-488d-b003-4322be14944c",
          "name": "GetSeasonChangeHistory",
          "request": {
            "url": "http://ee.iva-api.com/Changes/Seasons/History/?Date=%7B%7D&Skip=%7B%7D&Take=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Use if you want to check for specific updates to season records."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "41393909-45d2-4426-8857-d584c376c24f"
            }
          ]
        },
        {
          "id": "414f1de5-35c3-4f20-98e3-608dcdb60af1",
          "name": "GetSeasonChangeHistoryWithEntity",
          "request": {
            "url": "http://ee.iva-api.com/Changes/Seasons/HistoryWithEntity/?Date=%7B%7D&Skip=%7B%7D&Take=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns list of new or changed SeasonIds with the entity that has changed."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f172d989-ea78-4034-a664-f4edcaec63d8"
            }
          ]
        },
        {
          "id": "ff0cfdcb-a011-445f-9615-fcdb3d5c20ba",
          "name": "GetShowChangeHistory",
          "request": {
            "url": "http://ee.iva-api.com/Changes/Shows/History/?Date=%7B%7D&Skip=%7B%7D&Take=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "All new and updated shows from requested date and time.  When a record gets updated, use the ID to get the full show object and replace the data in your cache."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f727b09d-55cc-434a-b666-92bf9f609c4f"
            }
          ]
        },
        {
          "id": "50a92ecf-790f-4d5c-9213-a7de3741b9bb",
          "name": "GetShowChangeHistoryWithEntity",
          "request": {
            "url": "http://ee.iva-api.com/Changes/Shows/HistoryWithEntity/?Date=%7B%7D&Skip=%7B%7D&Take=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of ShowId and entity of any show that has been updated."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "43d5c247-a94a-4ba3-a8b5-2c70abc5d494"
            }
          ]
        }
      ]
    },
    {
      "name": "Charts",
      "item": [
        {
          "id": "594b0d47-87fc-40d7-aa75-e8b8bb249cd1",
          "name": "GetChartMoviesBoxoffice",
          "request": {
            "url": "http://ee.iva-api.com/Charts/Movies/Boxoffice?Skip=%7B%7D&Take=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns top 10 box office movies."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "050acf11-edb3-443e-b2bb-57c793b61a14"
            }
          ]
        },
        {
          "id": "dc2c8a1d-e947-4ec0-a9bb-b886de909c0c",
          "name": "GetChartMoviesMostAnticipated",
          "request": {
            "url": "http://ee.iva-api.com/Charts/Movies/MostAnticipated?Skip=%7B%7D&Take=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Requires Skip and Take. Maximum page size is 100."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5443c62c-7661-4b30-892f-55f1d0db8680"
            }
          ]
        },
        {
          "id": "214a352c-6c6e-4516-a37e-a76fa23d9008",
          "name": "GetChartMoviesPopular",
          "request": {
            "url": "http://ee.iva-api.com/Charts/Movies/Popular?Skip=%7B%7D&Take=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Requires Skip and Take. Maximum page size is 100."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "06742876-d8f3-4ab1-8438-44b9431549aa"
            }
          ]
        },
        {
          "id": "8e726a47-80de-4e04-b9cd-6e57881c5196",
          "name": "GetChartPeoplePopular",
          "request": {
            "url": "http://ee.iva-api.com/Charts/People/Popular?Skip=%7B%7D&Take=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Requires Skip and Take. Maximum page size is 100."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9ea9f1d0-e5d7-4a50-969d-941fdc1d5c14"
            }
          ]
        },
        {
          "id": "80393814-67bc-4601-ae57-c8bce54b9a77",
          "name": "GetChartShowsPopular",
          "request": {
            "url": "http://ee.iva-api.com/Charts/Shows/Popular?Skip=%7B%7D&Take=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Requires Skip and Take. Maximum page size is 100."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "08844564-2c5d-417b-9f88-99c2aad860b2"
            }
          ]
        }
      ]
    },
    {
      "name": "Common",
      "item": [
        {
          "id": "160ef04a-f797-4a8b-a869-f5033c85fec2",
          "name": "GetCompanies",
          "request": {
            "url": "http://ee.iva-api.com/Common/Companies/?Skip=%7B%7D&Take=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Companies are listed in a movie, show, or game response as those whom are involved with the program.  EX: Universal Pictures."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "66fe5d57-0fff-4857-a94e-f207d8da0ca6"
            }
          ]
        },
        {
          "id": "b22752e3-2066-4e8b-84c1-0fb3d6b3589e",
          "name": "GetCountries",
          "request": {
            "url": "http://ee.iva-api.com/Common/Countries/",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List of Countries, ISO codes and Country IDs used throughout the API."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bed7a968-1574-47fc-858a-32dd1b73a598"
            }
          ]
        },
        {
          "id": "78847570-74aa-430d-81b0-462475d05566",
          "name": "GetImageTypes",
          "request": {
            "url": "http://ee.iva-api.com/Common/ImageTypes/",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "A list of image types available in the IVA database. **EX: Poster**"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "81af2613-6b7c-456d-836b-93599e312aa9"
            }
          ]
        },
        {
          "id": "90162815-e6f7-4a09-8d44-7b7e85e70f9b",
          "name": "GetLanguages",
          "request": {
            "url": "http://ee.iva-api.com/Common/Languages/",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of languages used in the API as well as the ISO code and language ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1470421c-1fca-46b1-906e-54b97fa2cd76"
            }
          ]
        },
        {
          "id": "3b05996a-2be1-448a-9aad-79cf0d08c8f4",
          "name": "GetTags",
          "request": {
            "url": "http://ee.iva-api.com/Common/Tags/?Skip=%7B%7D&Take=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Paged list of all tags used in the API."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fcb51064-0b61-4fd1-8c08-88be9cfa3fde"
            }
          ]
        },
        {
          "id": "6b19904c-640b-4d37-a570-c1412273db68",
          "name": "GetVideoTypes",
          "request": {
            "url": "http://ee.iva-api.com/Common/VideoTypes/",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of the types of videos that can be associated to a title."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8fcbdbeb-2ea7-4f12-83b8-151f8d23af8a"
            }
          ]
        }
      ]
    },
    {
      "name": "ExternalIds",
      "item": [
        {
          "id": "ce325929-f5c2-45ab-ac1e-630491ba2e78",
          "name": "GetGracenoteMovieIds",
          "request": {
            "url": "http://ee.iva-api.com/ExternalIds/GracenoteMovie?Skip=%7B%7D&Take=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Not accessible with a Demo account.  **Special permissions needed** for access to this operation.  Contact [Sales](mailto:sales@internetvideoarchive.com)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "15f870b9-bf1c-4e19-8374-5a13d194c4ac"
            }
          ]
        },
        {
          "id": "43b93cdd-6a11-450f-87c1-67ad7cc2ab0f",
          "name": "GetGracenoteShowIds",
          "request": {
            "url": "http://ee.iva-api.com/ExternalIds/GracenoteShow?Skip=%7B%7D&Take=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Not accessible with a Demo account. **Special permissions needed** for access to this operation. Contact [Sales](mailto:sales@internetvideoarchive.com)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "04ee113e-242c-488c-a54f-e9b98aa4bccd"
            }
          ]
        },
        {
          "id": "2f5f6d51-7ef6-45c5-a86e-e71767974b4c",
          "name": "GetImdbMovieIds",
          "request": {
            "url": "http://ee.iva-api.com/ExternalIds/ImdbMovie?Skip=%7B%7D&Take=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Ingest this ID map to create connections between the objects in your existing database with an IMDB ID to the IVA Movie objects."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3db7fd3f-04eb-4adc-9db0-14801ed01329"
            }
          ]
        }
      ]
    }
  ]
}