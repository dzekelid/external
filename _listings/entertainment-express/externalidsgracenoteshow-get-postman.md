{
  "info": {
    "name": "Entertainment Express Returns list of all ShowId, Gracenote Id pairs.",
    "_postman_id": "b20a3bd9-59fe-456e-b4cb-be7bf4ddbbe8",
    "description": "Not accessible with a Demo account. **Special permissions needed** for access to this operation. Contact [Sales](mailto:sales@internetvideoarchive.com).",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Analytics",
      "item": [
        {
          "id": "1b930b20-3dc9-4d1d-b159-aa3898ae5dcd",
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
              "id": "09718041-8565-42be-a4c9-bc3e6e916634"
            }
          ]
        },
        {
          "id": "73735d70-5f13-4b41-bb66-208b57ea44dc",
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
              "id": "7443c4c8-ac7c-4896-9850-ad543a11026b"
            }
          ]
        },
        {
          "id": "369b6d2d-f37f-4863-a90a-bdfc386bf618",
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
              "id": "5ae2a0ac-19c2-47d9-b371-f78975d819e2"
            }
          ]
        },
        {
          "id": "ce522a3f-2536-429d-9e37-303e87341ab9",
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
              "id": "8df2adcb-d336-4053-9e0a-95b507412543"
            }
          ]
        },
        {
          "id": "290dfece-ba17-4edb-9424-e6892e92ef6e",
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
              "id": "083a9f65-c5a3-435a-b0f5-7512fabbee95"
            }
          ]
        },
        {
          "id": "58266bda-a0a3-4911-a516-14aa5a31b48e",
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
              "id": "21fb7767-c954-487d-ac10-3f38f547feda"
            }
          ]
        },
        {
          "id": "32edf4f2-da68-40cd-b5f2-2ce386f57687",
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
              "id": "ffe47d6f-530b-4eac-a7d7-8c60bb721d19"
            }
          ]
        },
        {
          "id": "0096c2bc-c8c6-42e5-8681-ce38f160695e",
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
              "id": "85d43fa3-bb73-4d16-af6a-c75a5e126428"
            }
          ]
        },
        {
          "id": "1445ae47-800a-4a1f-b5ae-5c79893d6094",
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
              "id": "d4b69725-d955-4686-bfdf-f56b170d595b"
            }
          ]
        },
        {
          "id": "bd5777cd-66c1-448f-a432-a63ff613c3ea",
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
              "id": "9bb5c5c9-dd9d-4e42-84d2-490b63cdd82e"
            }
          ]
        },
        {
          "id": "45ac2270-0eac-40f0-8ead-222d298261f9",
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
              "id": "38b48606-d6a7-41a2-9fdd-e97072833232"
            }
          ]
        },
        {
          "id": "7f5712da-3d9a-4135-85ac-bba3faedef5e",
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
              "id": "54100bd9-1bae-4fe4-83c0-5262a9ba5742"
            }
          ]
        },
        {
          "id": "0c6c6e8a-98af-4ad8-906e-b3b8fad56d3f",
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
              "id": "2ff342f0-38cf-44e3-b003-3dc8eb7487ff"
            }
          ]
        },
        {
          "id": "7e303caf-2cd1-4f04-bd7a-40589c8f4653",
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
              "id": "330f51ac-2c5f-4bb0-8291-8dd2d23f19da"
            }
          ]
        },
        {
          "id": "cc900ea9-97db-4316-be79-aa3cb744f764",
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
              "id": "d7369aae-3cf4-460c-b949-46539fdd36f7"
            }
          ]
        }
      ]
    },
    {
      "name": "Changes",
      "item": [
        {
          "id": "cb32ac33-0faf-4bb1-ab8d-71bbfbc2b73b",
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
              "id": "92a33b8c-9f51-444f-96df-60d588a53105"
            }
          ]
        },
        {
          "id": "590eb4bf-a411-449d-95d6-699c6cd45801",
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
              "id": "1060c29a-932e-4d3e-a31c-04417ae0129a"
            }
          ]
        },
        {
          "id": "38c8b3d3-a700-47c4-a907-2611b551a1c7",
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
              "id": "521bf253-fd13-4b70-880f-a2b18b47f787"
            }
          ]
        },
        {
          "id": "aed24e13-f832-4a4b-8056-387a6bd5654d",
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
              "id": "f5a71fdd-57b1-4e66-9d89-0b93d5b0587a"
            }
          ]
        },
        {
          "id": "6246921b-a89a-4c3d-a373-8f257ef55c84",
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
              "id": "4ea220e7-13c5-4989-822a-ca01cffc2535"
            }
          ]
        },
        {
          "id": "8b10352b-98a7-4fb2-9276-1407a18873cf",
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
              "id": "4e0c9033-478e-4177-b815-fb2c202b7ec3"
            }
          ]
        },
        {
          "id": "49efa033-b297-4b6b-b32d-6338f265f2fc",
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
              "id": "7aa55c41-3c19-434b-8868-a95bbc115a0e"
            }
          ]
        },
        {
          "id": "c413b513-8277-4c17-88f2-63cda9a43bfb",
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
              "id": "95624da1-5806-4829-a313-fea1b3a6488e"
            }
          ]
        },
        {
          "id": "23a4dec8-964f-4d98-af3d-2de567b0af30",
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
              "id": "406ba53b-4ca8-4a4c-9838-74ef809600d7"
            }
          ]
        },
        {
          "id": "23950058-1067-414b-8ae5-b02f9577f34a",
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
              "id": "d5e607e3-280b-4163-acd0-de4439d3ca20"
            }
          ]
        }
      ]
    },
    {
      "name": "Charts",
      "item": [
        {
          "id": "045b73c6-de88-476b-b31f-91941a304e7d",
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
              "id": "ef6cde51-dd40-408b-93cb-e25d9dc96688"
            }
          ]
        },
        {
          "id": "e9d6942a-16b0-4ef7-8807-b8743f5cdb4b",
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
              "id": "2724e9c1-39ea-437b-a1a1-52746cd040ce"
            }
          ]
        },
        {
          "id": "4be5500f-c532-4865-bbd3-3a2bdab29dca",
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
              "id": "18bca87d-ff12-4f0a-9d67-a46f1a30f07c"
            }
          ]
        },
        {
          "id": "cc53f53f-0e83-48e1-ab63-0e72c03c7ea8",
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
              "id": "c4f36b7b-35d6-4126-af18-de7157c5f761"
            }
          ]
        },
        {
          "id": "a50cf23d-08f8-4a81-a3fa-2dfdb230aec5",
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
              "id": "91f21e6d-6140-4173-9c3d-e9914ab2b8a8"
            }
          ]
        }
      ]
    },
    {
      "name": "Common",
      "item": [
        {
          "id": "c365f326-9ca3-41d2-8cf2-88d7146df2e5",
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
              "id": "b2c5c87a-bded-404a-82d9-56bd4db0a576"
            }
          ]
        },
        {
          "id": "4d99423d-f1c7-425b-bb11-ff66c57c40fc",
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
              "id": "a915f2b1-9003-4192-8f66-ed357dab4f19"
            }
          ]
        },
        {
          "id": "24189471-44aa-424c-b2e2-f5d4702ff1a1",
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
              "id": "34f11eb6-131b-4223-a2d4-a8cb8f5acaaf"
            }
          ]
        },
        {
          "id": "ca6f034c-8daa-4af9-9681-23f57d5ddf54",
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
              "id": "62d6e9e1-e0c7-4098-a64e-6c75a876d615"
            }
          ]
        },
        {
          "id": "2703839f-8213-4c0e-b69f-2ac877609851",
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
              "id": "c6908525-ba64-4901-a55e-fcccd27f9184"
            }
          ]
        },
        {
          "id": "2965626d-71cd-4432-848b-340c4e239fea",
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
              "id": "cb2cd691-44fc-4c02-a622-8436d783ac27"
            }
          ]
        }
      ]
    },
    {
      "name": "ExternalIds",
      "item": [
        {
          "id": "9cba4b4e-bd95-4277-9523-006979bad07a",
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
              "id": "b39e68c8-a187-47c4-af9d-c334e24dffc4"
            }
          ]
        },
        {
          "id": "cb308579-623a-4dff-9de8-739a1345239c",
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
              "id": "c426e264-a150-4b2a-a9f0-9d60e842d9f0"
            }
          ]
        }
      ]
    }
  ]
}