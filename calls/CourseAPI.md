# Course API
These calls works only if you are not logged into the system.
## /get/course
Returns an JSONArry with the courses of the user without details. Only with id, title, language & description.
```json
[
  {
    "description": "description1",
    "language": "de",
    "ID": 1,
    "title": "title1"
  },
  {
    "description": "description2",
    "language": "de",
    "ID": 12,
    "title": "title2"
  },
  {
    "description": "description3",
    "language": "de",
    "ID": 23,
    "title": "title3"
  },
  {
    "description": "description4",
    "language": "de",
    "ID": 34,
    "title": "title4"
  },
  {
    "description": "description5",
    "language": "de",
    "ID": 45,
    "title": "title5"
  },
  {
    "description": "description6",
    "language": "de",
    "ID": 56,
    "title": "title6"
  },
  {
    "description": "description7",
    "language": "de",
    "ID": 67,
    "title": "title7"
  }
]
```
## /get/course/{cid}
Returns an JSONObject with the details of a course.

```json
{
  "topics": [
    {
      "nodes": [
        {
          "links": [
            {
              "NID": 7,
              "type": "DEFAULT"
            }
          ],
          "PID": 6,
          "ID": 7
        },
        {
          "links": [
            {
              "NID": 3,
              "type": "DEFAULT"
            },
            {
              "NID": 3,
              "type": "FORK"
            }
          ],
          "PID": 2,
          "ID": 3
        },
        {
          "links": [
            
          ],
          "PID": 9,
          "ID": 10
        }
      ],
      "ID": 11,
      "title": "topic_title"
    }
  ],
  "description": "description",
  "language": "de",
  "ID": 1,
  "title": "title",
  "papers": [
    {
      "ID": 9,
      "title": "paper 2 title",
      "modules": [
        
      ]
    },
    {
      "ID": 6,
      "title": "paper 3 title",
      "modules": [
        
      ]
    },
    {
      "ID": 2,
      "title": "paper title",
      "modules": [
        
      ]
    }
  ]
}
```
