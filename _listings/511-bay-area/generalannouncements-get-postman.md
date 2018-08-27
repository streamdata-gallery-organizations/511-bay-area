{
  "info": {
    "name": "Bay Area 511 Transit API San Francisco 511 General Announcements API",
    "_postman_id": "4de7f98a-9c46-44c8-b52f-ab3f7cf87734",
    "description": "San francisco 511 general announcements api.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "511",
      "item": [
        {
          "id": "05147aed-d762-40d8-828c-6757c6dec475",
          "name": "LinesGet",
          "request": {
            "url": "http://api.511.org/transit/lines?api_key=%7B%7D&operator_id=%7B%7D",
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
            "description": "San francisco 511 transit lines api."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "26381527-b1a4-40b7-87df-896b036f6f2a"
            }
          ]
        },
        {
          "id": "f4d53138-365b-44eb-b4d2-b5eba160eb68",
          "name": "PatternsGet",
          "request": {
            "url": "http://api.511.org/transit/patterns?api_key=%7B%7D&operator_id=%7B%7D&pattern_id=%7B%7D",
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
            "description": "San francisco 511 transit transit patterns api."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c9e80a83-866b-4a3f-b357-e41b5018188e"
            }
          ]
        },
        {
          "id": "0ff9f4f5-ef56-4fb4-8a95-026a52ac71fd",
          "name": "StopsGet",
          "request": {
            "url": "http://api.511.org/transit/stops?api_key=%7B%7D&operator_id=%7B%7D",
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
            "description": "San francisco 511 transit stops api."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ff0f4213-adbf-4b82-b54a-c552bd1e075f"
            }
          ]
        },
        {
          "id": "5675c815-418e-4116-831c-b4647b33119d",
          "name": "StopMonitoringGet",
          "request": {
            "url": "http://api.511.org/transit/StopMonitoring?agency=%7B%7D&api_key=%7B%7D&stopCode=%7B%7D",
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
            "description": "San francisco 511 transit stop monitoring api."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1201c036-4978-4935-9d65-2bfbef242752"
            }
          ]
        },
        {
          "id": "a65b2541-6b7f-4dd3-822c-4d6fa9dc9500",
          "name": "StoptimetableGet",
          "request": {
            "url": "http://api.511.org/transit/stoptimetable?api_key=%7B%7D&MonitoringRef=%7B%7D&OperatorRef=%7B%7D",
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
            "description": "San francisco 511 transit stop timetable api."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2b3f6f9d-456d-4572-b61e-4e4bac0f97c7"
            }
          ]
        },
        {
          "id": "111aab20-1056-4c52-907c-e141723a764a",
          "name": "GeneralAnnouncementsGet",
          "request": {
            "url": "http://api.511.org/transit/GeneralAnnouncements?api_key=%7B%7D",
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
            "description": "San francisco 511 general announcements api."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "25563ac9-4c76-4e5a-b5c9-49767bbd4c16"
            }
          ]
        }
      ]
    }
  ]
}