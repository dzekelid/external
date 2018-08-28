{
  "info": {
    "name": "Entertainment Express Returns list of all MovieId, Webedia Id pairs.",
    "_postman_id": "e5cd1a86-08c0-4d67-8604-014d2b869087",
    "description": "Not accessible with a Demo account. **Special permissions needed** for access to this operation. Contact [Sales](mailto:sales@internetvideoarchive.com).",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Analytics",
      "item": [
        {
          "id": "dab32145-91d4-4acc-920e-5d7a2792da8a",
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
              "id": "b83b810a-20c8-4f77-858f-6b29d0e9b138"
            }
          ]
        },
        {
          "id": "32f44eb6-2a02-416b-856f-9fe58b82046e",
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
              "id": "8e346d85-c5fb-4723-9cc3-466a984bf341"
            }
          ]
        },
        {
          "id": "6e753811-7d25-47c0-a50b-40a4561647e6",
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
              "id": "9160a85a-4a23-4899-b027-9cd101210ae9"
            }
          ]
        },
        {
          "id": "fd985270-bff3-4a8e-872e-01522ca1e617",
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
              "id": "77f62ad9-3129-4f83-9cad-5b016724a27f"
            }
          ]
        },
        {
          "id": "84873a22-ff2b-4793-a314-3ea9d3a0916c",
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
              "id": "8b918516-cedb-4786-9b8f-b9b6178477bc"
            }
          ]
        },
        {
          "id": "451a9d52-79be-43fe-85a7-4391c1ed4e57",
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
              "id": "126eaaf6-9ca3-464f-83ba-4a4e88fb51a8"
            }
          ]
        },
        {
          "id": "c85da197-85c1-4530-b115-9e97713ea8e5",
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
              "id": "e1f18cea-3ee8-4ea7-b85f-713dea9fc037"
            }
          ]
        },
        {
          "id": "8a1ebe74-650e-42a9-a222-97965f503496",
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
              "id": "0b3f8e34-5a58-4da9-a179-3c0e959a68e3"
            }
          ]
        },
        {
          "id": "7fed1265-0fc6-4a6a-ad70-af5dd99bd280",
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
              "id": "d2a84179-80ce-4e10-b710-4fd46b96a1c4"
            }
          ]
        },
        {
          "id": "f8213a29-12c9-4475-87b6-c6104153e478",
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
              "id": "8e879d74-8550-4231-ab35-233c95e212be"
            }
          ]
        },
        {
          "id": "4d16ba0c-7c4c-4957-ad57-6b6ec0c1b819",
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
              "id": "2c45d19b-bea8-4fd5-8529-fcd58e85984a"
            }
          ]
        },
        {
          "id": "fe9ef2df-ce12-4443-a801-cd1a7b58f8c7",
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
              "id": "8c3d03ab-217b-4cb4-a1ff-6b2c1198c420"
            }
          ]
        },
        {
          "id": "a42bf108-8888-430b-93c0-dce90ddacb0c",
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
              "id": "d4862ec9-875e-489d-b745-328486f4907e"
            }
          ]
        },
        {
          "id": "7af469fd-16a7-4dac-9123-b3807c750ae2",
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
              "id": "ca3dd120-4998-441f-aa47-6fb09c834051"
            }
          ]
        },
        {
          "id": "0c6bfad4-8ded-4c68-8910-afc3080f4890",
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
              "id": "7f4913d6-18c6-433e-8451-5d729dda155a"
            }
          ]
        }
      ]
    },
    {
      "name": "Changes",
      "item": [
        {
          "id": "caf96eb6-7c53-46f6-b942-a63cc142c746",
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
              "id": "18ab7eaf-6a46-4301-bc4a-738351b1ce98"
            }
          ]
        },
        {
          "id": "f8950e3d-0aaa-4ef0-9f8b-67d48aa1aac1",
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
              "id": "042212b1-1a02-436c-a6f0-adc2793f8b7b"
            }
          ]
        },
        {
          "id": "225d8f08-30a9-45e7-b84a-dc6e810994cf",
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
              "id": "28b03990-8f24-46ee-ae4f-48c137ec8e70"
            }
          ]
        },
        {
          "id": "c1553234-78ff-4fda-9b67-d845c2540abc",
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
              "id": "fc53907e-839a-45f0-806a-8802b730b292"
            }
          ]
        },
        {
          "id": "2d4032bd-17cd-4a19-b14d-1c0409b9e900",
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
              "id": "ff1c045a-6b64-47c6-af58-ecc7df607e93"
            }
          ]
        },
        {
          "id": "a433b43b-559d-4beb-a54c-9a5e79d869e1",
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
              "id": "c19d1a96-93ca-4075-93ad-ca6c584c57c1"
            }
          ]
        },
        {
          "id": "5b0228dd-e583-4b26-a863-295079ad4f71",
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
              "id": "d352cb11-599a-46ac-8719-9e9913ea411b"
            }
          ]
        },
        {
          "id": "d4b6b10f-8960-49d7-9316-6c5909f953f7",
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
              "id": "2020b711-6a35-4719-9ede-5e563755598e"
            }
          ]
        },
        {
          "id": "21b786d6-69f7-400a-8100-df2284321b75",
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
              "id": "11d93792-724c-4514-b242-e0b9c7bc14f2"
            }
          ]
        },
        {
          "id": "712452d7-3085-4905-a93c-a09128cacadf",
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
              "id": "b517d68b-64e6-4f93-8268-99edd133ff9c"
            }
          ]
        }
      ]
    },
    {
      "name": "Charts",
      "item": [
        {
          "id": "01cda010-26cf-4122-b150-f8cfbf2d808e",
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
              "id": "d2968c90-643a-4dba-a114-3a9d7ad62e36"
            }
          ]
        },
        {
          "id": "31d58c4b-24bc-413c-bb80-c536ecc24038",
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
              "id": "03750e75-a7ae-47c7-8d9a-adc40fc9aa36"
            }
          ]
        },
        {
          "id": "a8797e78-07f7-4590-80dd-24decc79d5f4",
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
              "id": "3f28c087-b5e6-4fa7-ba42-e1d2ce06d7cb"
            }
          ]
        },
        {
          "id": "bd6544c9-2345-41b0-a861-165505162bfa",
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
              "id": "4d401601-7b4c-4b82-b512-685f28e443a3"
            }
          ]
        },
        {
          "id": "39880483-fc41-466a-9347-5deee1527fea",
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
              "id": "e43c990a-ac89-4a32-87fd-b9a2cedf108b"
            }
          ]
        }
      ]
    },
    {
      "name": "Common",
      "item": [
        {
          "id": "b0ac0882-04a4-44f7-ab59-25d48ce8f7e4",
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
              "id": "0c20b4d0-3b39-463a-9df5-81db9080339d"
            }
          ]
        },
        {
          "id": "410f2a8b-faa3-45a5-b4ec-8cb2bda2ad77",
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
              "id": "910a29de-0a7c-4369-898b-266183d3b8cf"
            }
          ]
        },
        {
          "id": "493649f9-5de6-4de4-b241-ad42b7dc52d8",
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
              "id": "f3abdf48-9bd6-4422-a6db-953d99075dcf"
            }
          ]
        },
        {
          "id": "c271cdf6-07e4-42ff-8519-6421fa2886b5",
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
              "id": "e2fa2bbc-6a1f-4dc9-a0dc-27e42848973f"
            }
          ]
        },
        {
          "id": "c20f0f7d-399c-4d41-8e24-b62370c93174",
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
              "id": "36871898-2134-4c13-ae70-31a4f362184f"
            }
          ]
        },
        {
          "id": "5ab79107-f624-4b49-9d1a-a6da526bcf32",
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
              "id": "7a5d9818-5f4f-4113-b57d-ed84baa2dde8"
            }
          ]
        }
      ]
    },
    {
      "name": "ExternalIds",
      "item": [
        {
          "id": "39be3b68-8903-4c35-a5c4-1f5bd9956fae",
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
              "id": "9740ef56-5b43-49c2-90bc-743b3d20bcdc"
            }
          ]
        },
        {
          "id": "0c546c20-2274-4a5a-aec6-3344a550bc42",
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
              "id": "6e2ae3f7-3b0a-4280-9d7b-dd4e663aaf8a"
            }
          ]
        },
        {
          "id": "f5df1574-97bf-4629-8109-d45003d37032",
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
              "id": "03d22f74-b77e-4eba-9ef0-e6f982073473"
            }
          ]
        },
        {
          "id": "f4c20c4d-cc0c-4403-ab3d-3e1d6ee405be",
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
              "id": "7986bf4b-0723-4c07-955d-da8a0486f1a8"
            }
          ]
        },
        {
          "id": "5f8c045a-47ad-477f-ae3e-22cceb2abe75",
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
              "id": "45615966-4cbb-404e-ae95-b06b715577f8"
            }
          ]
        },
        {
          "id": "52c073d1-573d-4396-bb46-aa86b80c9cfa",
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
              "id": "b43a5ad4-7212-41de-bd55-03a3efbe0590"
            }
          ]
        },
        {
          "id": "d68acd6c-6705-46cc-9e6d-5a72e736cfb5",
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
              "id": "7c72bafb-0a53-4582-a979-e43b7f31953a"
            }
          ]
        },
        {
          "id": "d1775148-a6db-4180-876f-fba47921c02a",
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
              "id": "f7ea2f76-438f-4552-90a9-7597ad32fa12"
            }
          ]
        },
        {
          "id": "6dab0f16-b881-4d47-960d-8cc26e15e35c",
          "name": "GetWebediaMovieIds",
          "request": {
            "url": "http://ee.iva-api.com/ExternalIds/Webedia?Skip=%7B%7D&Take=%7B%7D",
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
              "id": "e5b9ec82-9bc4-4528-b67d-17191fa76304"
            }
          ]
        }
      ]
    }
  ]
}