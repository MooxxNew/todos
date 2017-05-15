# Users

## GET /todos

* Content-Type: "application/json; charset=utf-8"
* Accept: "application/json"

===
### Expected response
* Status: `200`
* Content-Type: "application/json; charset=utf-8"
```json
[
  {
    "id": 1,
    "checked": true,
    "message": "Homework 1"
  },
  {
    "id": 2,
    "checked": false,
    "message": "Homework 2"
  }
]
```