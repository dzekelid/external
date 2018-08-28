{
  "info": {
    "name": "Entertainment Express Returns list of all ShowId, TMDB Id pairs.",
    "_postman_id": "ca4d28ec-71fa-48fe-91b1-cf534dc3f9c6",
    "description": "Use to link a TMDB ID to an IVA Show ID.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Analytics",
      "item": [
        {
          "id": "2a54cad3-e23a-4906-8cf6-2661590c1586",
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
              "id": "6c349286-8255-46dc-8104-cf79dc421e41"
            }
          ]
        },
        {
          "id": "5454b879-e4da-4672-9fe7-e7394de6b2cf",
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
              "id": "bd715cc8-4bca-464d-9464-45b681b280ab"
            }
          ]
        },
        {
          "id": "4ad4fe9e-4aa8-4f6f-a5c3-b17bc1272b54",
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
              "id": "c016d97f-3a5f-4373-8998-55e5f99ca876"
            }
          ]
        },
        {
          "id": "a7fbc3bd-94b1-45c7-935f-f9ad66b2f61e",
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
              "id": "2e7a9809-fa7c-4752-89b3-f4a55bc8735e"
            }
          ]
        },
        {
          "id": "b5687af0-62ea-419e-bede-0be66dfed9d6",
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
              "id": "45cf9b4d-ce0a-404b-bd6c-1b3e470615f2"
            }
          ]
        },
        {
          "id": "d4100770-a1f2-4b06-bf9f-cd3c0126da88",
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
              "id": "a2a61f56-513f-4acd-b207-6c920f140594"
            }
          ]
        },
        {
          "id": "b5b7cbc2-3ab5-4489-9f50-fcaaee3d5b8f",
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
              "id": "74720da0-e132-4dfc-aaa0-4742a5d81990"
            }
          ]
        },
        {
          "id": "7e5f47de-6d5c-433d-aba9-55cccf7709f2",
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
              "id": "f9333804-c8a8-451c-b170-757f53cb3308"
            }
          ]
        },
        {
          "id": "b5134f61-35f1-4a81-8b37-85fb9bf4ad03",
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
              "id": "cd994ed7-6195-4ebc-8293-0ebb04898a21"
            }
          ]
        },
        {
          "id": "bc8a92c0-1bb9-421b-bd68-26c3f20edf9a",
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
              "id": "ed07a43e-55b2-4e4c-9107-b0c8d9c55c57"
            }
          ]
        },
        {
          "id": "81c5d877-c6de-4889-bd49-18665fed93d7",
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
              "id": "ceefc376-5517-4d29-8b2b-e0943d84b422"
            }
          ]
        },
        {
          "id": "a4fb4c63-368d-4158-80a5-0157d88a2b36",
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
              "id": "14447ca3-77a1-4540-9d1b-e677ec8251d9"
            }
          ]
        },
        {
          "id": "e0dc5e8d-e0ef-4844-bd17-6b91a084dd8d",
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
              "id": "4ebe16d3-e437-4d83-bcdf-fb0108bf2e04"
            }
          ]
        },
        {
          "id": "9d040b65-7d43-438f-ad95-6f393f157659",
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
              "id": "724cf33c-e055-4449-a8b4-8aa3515296ea"
            }
          ]
        },
        {
          "id": "916a3714-67e8-4692-b9ed-cd5721e08149",
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
              "id": "f9583ba8-756c-45c0-99e1-69dc0917f330"
            }
          ]
        }
      ]
    },
    {
      "name": "Changes",
      "item": [
        {
          "id": "fe4027ae-68f4-4ba1-9e07-fe8f3284ae46",
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
              "id": "7f0c095d-b813-4b5e-8408-1599f8cdb8ec"
            }
          ]
        },
        {
          "id": "31e14d12-52fa-4cee-8492-e7d768243082",
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
              "id": "3efb624b-9317-4c20-96e1-f153b9040f25"
            }
          ]
        },
        {
          "id": "483ef8f2-7a8c-4c8c-ad48-6a9c670c46d0",
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
              "id": "5c758a55-fb21-4e22-9579-0de09a239529"
            }
          ]
        },
        {
          "id": "0ce7212c-4feb-40da-bee8-79c92f5d0eda",
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
              "id": "26db4905-ac09-4dc3-92c5-105274da1895"
            }
          ]
        },
        {
          "id": "33f42138-be78-4c77-8682-34a531e3f02e",
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
              "id": "0b6f5d4b-7182-48ef-b8f6-74862ae4c3cb"
            }
          ]
        },
        {
          "id": "3daef04e-5e42-4c25-97e2-a4e206fc98b4",
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
              "id": "dffe6814-1b04-4e5e-aaaa-7408514a36d7"
            }
          ]
        },
        {
          "id": "95c90ca8-5ebf-4eb0-9881-b44db318ac37",
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
              "id": "6dd0c3c0-e482-40eb-8e60-1115c8ac06f0"
            }
          ]
        },
        {
          "id": "4d09a347-e022-448a-9a7a-0e3b60089bd0",
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
              "id": "98a63235-b08a-4507-83d5-e26c3224604a"
            }
          ]
        },
        {
          "id": "319ed947-984e-43d5-b59c-1fa814e7c0e0",
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
              "id": "c4ca75b2-d47f-4b7e-87d9-3188ad2376eb"
            }
          ]
        },
        {
          "id": "6bfb0e5a-e068-4a66-80cc-fd82bed1dc7f",
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
              "id": "a663e1ca-e93c-4392-87c0-d0384e46d35d"
            }
          ]
        }
      ]
    },
    {
      "name": "Charts",
      "item": [
        {
          "id": "8a86090f-6272-448d-a7ae-c920b1b11deb",
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
              "id": "2db0c402-34b9-4827-b2bf-e5c8d89dd49b"
            }
          ]
        },
        {
          "id": "57b92315-068a-467e-918c-a62d608f685b",
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
              "id": "d65d3b3d-8f73-4428-9a86-b735ec6bd18d"
            }
          ]
        },
        {
          "id": "133e09e3-ddbb-4c9f-86e2-9d18181d0690",
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
              "id": "749f9b47-487a-4724-848d-3afe3178803c"
            }
          ]
        },
        {
          "id": "825151d9-1b43-4ba0-9902-8bff8da776f1",
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
              "id": "d677948f-975e-4535-8b52-4acd9963d33c"
            }
          ]
        },
        {
          "id": "4c583d2c-d235-491f-8917-24e78592d888",
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
              "id": "6a3f95e1-83b1-4ec7-acb4-6bb0ca233962"
            }
          ]
        }
      ]
    },
    {
      "name": "Common",
      "item": [
        {
          "id": "a3b7e6f3-d86d-4ce3-ad32-bca768149723",
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
              "id": "50fad829-faa3-4e80-8eae-9eaff2375c3b"
            }
          ]
        },
        {
          "id": "d5890388-0548-4425-9a21-6b725d6312ef",
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
              "id": "5dc5b336-e3fa-46c5-a317-0f27ecca8b57"
            }
          ]
        },
        {
          "id": "8ad0ea67-6de8-4fa5-8adb-6b01b4f40428",
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
              "id": "79454d82-edcb-4fae-8564-cfdc10fe886f"
            }
          ]
        },
        {
          "id": "c3f17f3a-07f6-4b51-854f-b0cceea1c414",
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
              "id": "82c1edb3-94b1-4617-968f-02711a108891"
            }
          ]
        },
        {
          "id": "e0b0d91d-92ec-4cf3-b51d-47c089afef07",
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
              "id": "bc90e513-ac91-46ad-bed2-25793198b462"
            }
          ]
        },
        {
          "id": "cecbdac4-72ca-4967-bab5-301192eaaded",
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
              "id": "fe9ad687-e04e-4fdb-bb17-463a3425b8ac"
            }
          ]
        }
      ]
    },
    {
      "name": "ExternalIds",
      "item": [
        {
          "id": "77d83233-d9a3-423a-baea-319e607090e1",
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
              "id": "735bb4a9-595b-485f-94a6-612c6bc68c70"
            }
          ]
        },
        {
          "id": "9b143b5c-cd1d-4f8d-a8cd-bd9355de4c0d",
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
              "id": "27cffe97-6374-472b-88b0-f8d011b595ff"
            }
          ]
        },
        {
          "id": "ed6db340-8086-4c06-b001-80182eb7ecd8",
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
              "id": "c63b222c-65a1-48db-a411-762ba003300e"
            }
          ]
        },
        {
          "id": "074bada3-1827-4179-b964-3d91882ebe59",
          "name": "GetImdbShowIds",
          "request": {
            "url": "http://ee.iva-api.com/ExternalIds/ImdbShow?Skip=%7B%7D&Take=%7B%7D",
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
            "description": "ngest this ID map to create connections between the objects in your existing database with an IMDB ID to the IVA Show objects."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "52135886-2a8d-46bd-b541-3163dc13521d"
            }
          ]
        },
        {
          "id": "370b8a2f-7295-40d9-b395-6b4fc6e5fcf2",
          "name": "GetTivoMovieIds",
          "request": {
            "url": "http://ee.iva-api.com/ExternalIds/RoviMovie?Skip=%7B%7D&Take=%7B%7D",
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
              "id": "e36ce867-0c3b-4290-abef-ae723a3c1194"
            }
          ]
        },
        {
          "id": "662513fb-0845-4f32-a45a-86157981d2d1",
          "name": "GetTivoShowIds",
          "request": {
            "url": "http://ee.iva-api.com/ExternalIds/RoviShow?Skip=%7B%7D&Take=%7B%7D",
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
              "id": "92e7f5af-5036-4b52-badc-87d2ba16413a"
            }
          ]
        },
        {
          "id": "f672ef8b-4b9f-419c-a54d-ea72efa111c4",
          "name": "GetTmdbMovieIds",
          "request": {
            "url": "http://ee.iva-api.com/ExternalIds/TmdbMovie?Skip=%7B%7D&Take=%7B%7D",
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
            "description": "Use to link a TMDB ID to an IVA Movie ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "865cafac-1bf1-4600-af19-0a0b55fc4836"
            }
          ]
        },
        {
          "id": "b16bc2f7-6444-482f-b5b2-10ede320e507",
          "name": "GetTmdbShowIds",
          "request": {
            "url": "http://ee.iva-api.com/ExternalIds/TmdbShow?Skip=%7B%7D&Take=%7B%7D",
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
            "description": "Use to link a TMDB ID to an IVA Show ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a669242d-5d76-4f09-822c-d5ecf5da3ea2"
            }
          ]
        }
      ]
    }
  ]
}