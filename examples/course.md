```json
{
  "CREATE": true,
  "description": "description",
  "language": "de",
  "ID": 1000,
  "title": "title",
  "papers": [
    {
      "ID": 2001,
      "title": "paper title"
    },
    {
      "ID": 2002,
      "title": "paper 2 title"
    },
    {
      "ID": 2003,
      "title": "paper 3 title"
    }
  ],
  "topics": [
    {
      "ID": 3001,
      "title": "topic_title",
      "nodes": [
        {
          "ID": 4001,
          "PID": 2001,
          "links": [
            {
              "NID": 4003,
              "type": "default"
            },
            {
              "NID": 4002,
              "type": "fork"
            }
          ]
        },
        {
          "ID": 4002,
          "PID": 2002
        },
        {
          "ID": 4003,
          "PID": 2003,
          "links": [
            {
              "NID": 4001,
              "type": "default"
            }
          ]
        }
      ]
    }
  ]
}
```
