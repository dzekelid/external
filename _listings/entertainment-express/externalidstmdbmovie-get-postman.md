{
  "info": {
    "name": "Entertainment Express Returns list of all MovieId, Tmdb Id pairs.",
    "_postman_id": "0021bf34-83a0-4c07-b040-e6ef8c5139ba",
    "description": "Use to link a TMDB ID to an IVA Movie ID.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Analytics",
      "item": [
        {
          "id": "50198032-d0b6-4d07-a512-9b6e036e7f57",
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
              "id": "decd9f70-887b-4dcc-9d26-5301cba3aed1"
            }
          ]
        },
        {
          "id": "3462716e-701f-4be5-915f-458c42e11117",
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
              "id": "76253387-e00d-458e-9a08-143407816ce2"
            }
          ]
        },
        {
          "id": "6accafeb-7306-45a4-b072-6453d5a26106",
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
              "id": "28ce18cb-bd78-4858-bf33-08a5f51fe374"
            }
          ]
        },
        {
          "id": "a1a02fd9-7226-4dbc-bf90-27b5ba0e2961",
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
              "id": "363b0cd8-a500-4461-9be4-89f79e9bba84"
            }
          ]
        },
        {
          "id": "bae60837-b89d-4f06-aaa7-bac5c9389425",
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
              "id": "7c64de2f-7189-4103-84aa-1b505002188b"
            }
          ]
        },
        {
          "id": "4b8a457d-e3fb-447b-8ab8-43363486f1c2",
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
              "id": "1528e935-849e-4b5d-8210-7c1a21f238b2"
            }
          ]
        },
        {
          "id": "d51af7dd-9983-4966-a653-b9149060947a",
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
              "id": "27a4610e-cd05-4457-ae18-242c795fc280"
            }
          ]
        },
        {
          "id": "c3599e19-d97f-49c9-b88b-7bb9553ba0f6",
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
              "id": "7db706b4-1d59-4e14-b356-7c32fda5d8f7"
            }
          ]
        },
        {
          "id": "972a8e1c-a074-4085-9256-1725f6806644",
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
              "id": "81f60991-0f13-4152-abe2-af669195f0c6"
            }
          ]
        },
        {
          "id": "f87e9365-91fa-42c3-b87c-6a6283e4733e",
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
              "id": "37d14b1a-07cf-4403-aba2-8ef71d3d2e93"
            }
          ]
        },
        {
          "id": "db4b7e17-fe13-4268-9481-2eba38dd2278",
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
              "id": "c88e29f4-0e64-4e21-adf2-9a7fb33f6a5c"
            }
          ]
        },
        {
          "id": "e49ee75f-403c-40ad-9577-93de7f4009b4",
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
              "id": "4166782a-d6ca-4f85-a3d5-fa4637c4fbe3"
            }
          ]
        },
        {
          "id": "70cc1c3c-589a-4dfa-9616-baa9a0304e9a",
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
              "id": "3a32d2c3-9c67-49e5-8ae0-d81a70c4fd7a"
            }
          ]
        },
        {
          "id": "c918789d-841f-4f66-b282-daa2e0068cf8",
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
              "id": "13f34ce5-eeec-4baa-b8cd-1114adda5974"
            }
          ]
        },
        {
          "id": "d09b3542-44a4-4345-b868-28507f7bbf6e",
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
              "id": "c39005c5-9c86-406c-a459-45fb52b39e73"
            }
          ]
        }
      ]
    },
    {
      "name": "Changes",
      "item": [
        {
          "id": "efbfb0c9-e11b-4770-9c43-e13619dea05b",
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
              "id": "0a2fdde5-2d7e-4b22-8053-11c1b4dacf80"
            }
          ]
        },
        {
          "id": "220d777b-f1ef-41a9-b160-de46e0bf9f5f",
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
              "id": "1a048f9d-1b41-4931-9968-0492aaf340c7"
            }
          ]
        },
        {
          "id": "865991e1-c1e3-4a93-96e3-97a164800fb7",
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
              "id": "3ae74ac2-31ce-426f-a9ec-b97eae826095"
            }
          ]
        },
        {
          "id": "3e299261-2500-4b83-87c0-4ce0947ecfcb",
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
              "id": "28abcaab-e741-4dbf-9d89-a02a896d8240"
            }
          ]
        },
        {
          "id": "758a1380-c5fc-4a21-92a4-610eb7706531",
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
              "id": "083f6717-6c00-4d1f-b6a2-629eb075f150"
            }
          ]
        },
        {
          "id": "26b6f6ad-10e5-4354-8aad-19cead9962b7",
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
              "id": "69a3fd73-c737-4c48-b782-ec8712cc3b77"
            }
          ]
        },
        {
          "id": "cb46f2a4-af81-450a-b822-45f0763507e1",
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
              "id": "a7751020-0c23-4f54-9c9c-12cc861c4c85"
            }
          ]
        },
        {
          "id": "182adf7a-6fb9-43c6-9b34-5b9fee8a545d",
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
              "id": "7818f263-c29c-4029-9cf5-3f21f76dd35d"
            }
          ]
        },
        {
          "id": "94fab183-51bd-4e29-ae6c-729177864482",
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
              "id": "7be0f31e-574d-4fb1-99cd-6f71e2a99203"
            }
          ]
        },
        {
          "id": "53b578b9-5ae8-4e3c-b045-95c74e734069",
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
              "id": "fab9e352-e93c-4dc8-8821-0b6ff5d14165"
            }
          ]
        }
      ]
    },
    {
      "name": "Charts",
      "item": [
        {
          "id": "ba59d89b-1e11-4577-8c3a-336be6fd12cb",
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
              "id": "8f20a7eb-89e9-460c-8445-199c2b4de11b"
            }
          ]
        },
        {
          "id": "7008a152-4c0c-4785-877a-c183df82e042",
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
              "id": "de2e2afd-12f2-4202-8ff0-50024ab97ba5"
            }
          ]
        },
        {
          "id": "0a89d34a-73dd-4919-81e9-1b104a05aa19",
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
              "id": "a1e9b8db-93d0-4c60-afb4-214644e78dfc"
            }
          ]
        },
        {
          "id": "85af25cf-f55e-40ac-a545-dcd7378fe96a",
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
              "id": "81a746bd-ad3e-4840-8e64-40a476f5b2c8"
            }
          ]
        },
        {
          "id": "bbc3e332-7764-48d3-8487-9e433f78bee0",
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
              "id": "4acf1d2c-525c-4008-862b-70843726ead3"
            }
          ]
        }
      ]
    },
    {
      "name": "Common",
      "item": [
        {
          "id": "c38b2ade-d312-4d95-8319-f17f58c9f413",
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
              "id": "6a73b13e-1768-4582-84be-5ce5103e9529"
            }
          ]
        },
        {
          "id": "c196df88-719c-4ecc-9bdf-7d94b0054fc6",
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
              "id": "ce4353a7-5fba-436c-89c7-68d17b35e240"
            }
          ]
        },
        {
          "id": "db952120-60b2-45fe-8606-de2b75b7b19c",
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
              "id": "5c966c0e-1be8-4406-a1b1-5be16a9789a8"
            }
          ]
        },
        {
          "id": "1ef806ce-1664-4cb0-b93f-a1458b331fb6",
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
              "id": "2f9c0a64-9440-4abb-bb19-ca6e989f8725"
            }
          ]
        },
        {
          "id": "e65e188e-6eec-45de-805a-b939182a2893",
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
              "id": "4d041327-5617-4541-ac1d-20932ea49aee"
            }
          ]
        },
        {
          "id": "3e8b8908-6ca6-4668-8aa0-2b41966f837d",
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
              "id": "52d16220-3703-4879-9bb7-8aa277681d6b"
            }
          ]
        }
      ]
    },
    {
      "name": "ExternalIds",
      "item": [
        {
          "id": "6c3c5e8e-41b5-48e0-a6be-731d688718e1",
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
              "id": "8fbaa70a-0a7f-4d5a-b293-4e9e0b09b0c8"
            }
          ]
        },
        {
          "id": "e350b8a9-dc38-4e72-908e-9e2aa4cc9ea3",
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
              "id": "a0d33347-e9ec-4ee8-a20c-082e83bb1507"
            }
          ]
        },
        {
          "id": "bfc6c314-9dee-406a-9fed-e28b297ac4e1",
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
              "id": "6a176c9a-2e02-4c3a-b5a2-f2f7d0ceecf0"
            }
          ]
        },
        {
          "id": "b20cbd51-7b7d-4c02-ad4c-dcb8d0b8d412",
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
              "id": "7a3983bb-55ee-4ecc-b7d2-d22ae517ba7d"
            }
          ]
        },
        {
          "id": "83c2159b-8736-4f5e-aae9-d774537eff6c",
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
              "id": "61656e38-6ad1-417f-b5f3-4272cfd87a03"
            }
          ]
        },
        {
          "id": "a189e950-427c-4546-89a5-80c1d35c828e",
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
              "id": "1100a21e-0e1b-403f-aba4-ec556ce95e4e"
            }
          ]
        },
        {
          "id": "48a87677-899b-4136-abd0-d8beb7b54783",
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
              "id": "546d25db-6cc4-46fe-8d86-07b900db7459"
            }
          ]
        }
      ]
    }
  ]
}