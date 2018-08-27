{
  "info": {
    "name": "Bay Area 511 Transit API Operatorators API",
    "_postman_id": "c50658b4-8295-47e8-83c4-f24f713687e1",
    "description": "San francisco 511 transit operatorators api.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "511",
      "item": [
        {
          "id": "2c1a4887-3325-4e8d-ab48-a460b369d1d0",
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
              "id": "f0baa95f-3a62-4885-b524-d0937b614a64"
            }
          ]
        },
        {
          "id": "bb79fd4e-3f55-4531-a554-9fc15060e71f",
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
              "id": "fddbb6c3-d1a3-46fa-863c-a42635af2f47"
            }
          ]
        },
        {
          "id": "3c264bfd-3441-4dfa-9305-8ed28e983d7a",
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
              "id": "d3b45f6d-80e5-4a19-922e-d4984acf0a52"
            }
          ]
        },
        {
          "id": "2c5c395b-4bb5-4ae5-a9b0-1dd59d5a290b",
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
              "id": "300810f4-f706-455d-90b6-5648a14cbf81"
            }
          ]
        },
        {
          "id": "017b584a-2372-40ce-a733-058f0c344a6c",
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
              "id": "a8ff2d33-c9af-4519-bb4c-c38d6a7e0df2"
            }
          ]
        },
        {
          "id": "ec674257-e255-429f-b75d-35da290f1bc6",
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
              "id": "5ab70179-85b3-46cc-bdf9-23fbe1c86ef8"
            }
          ]
        },
        {
          "id": "2d8e36ae-637a-46b2-b99b-462f02811645",
          "name": "StopPlacesGet",
          "request": {
            "url": "http://api.511.org/transit/stopPlaces?api_key=%7B%7D&operator_id=%7B%7D",
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
            "description": "San francisco 511 transit stop places api."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d2665d7a-c0f1-458d-b6f0-a7f0cabccb3b"
            }
          ]
        },
        {
          "id": "96edff82-236d-4eb1-a3df-110ea0409f95",
          "name": "VehicleMonitoringGet",
          "request": {
            "url": "http://api.511.org/transit/VehicleMonitoring?agency=%7B%7D&api_key=%7B%7D&stopCode=%7B%7D",
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
            "description": "San francisco 511 vehicle monitoring api."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "59ffaa7e-e6d7-4eef-b2cd-cb2454be6629"
            }
          ]
        },
        {
          "id": "ef200a9c-e50b-46b6-9f51-ea32241b4184",
          "name": "OperatorsGet",
          "request": {
            "url": "http://api.511.org/transit/operators?api_key=%7B%7D",
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
            "description": "San francisco 511 transit operatorators api."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "82841d02-a5ed-4af0-ac34-d1a8bfa3a57f"
            }
          ]
        }
      ]
    }
  ]
}