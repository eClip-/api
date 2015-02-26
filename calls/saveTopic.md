# saveTopic

```json
{
  "CID": 300, //Course ID obligatorisch
  "ID": 2000, //Topic exisitiert bereits
  "title": "letitle",
  "nodes": [
    {
      "CREATE": true,
      "isStart": true,
      "PID": 1600, //Verweis auf Paper
      "ID": 1400, //Target_ID die nicht gespeichert wird, wird nur als Referenz benutzt
      "links": [
        {
          "CREATE": true,
          "type": "default",
          "NID": 1401
        },
        {
          "CREATE": true,
          "type": "fork", 
          "NID": 1400
        }
      ]
    },
    {
      "ID": 1401,
      "PID": 1601,
      "links": [
        {
          "type": "default",
          "NID": 1402
        }
      ]
    },
    {
      "TID": 400, //Node als Topic
      "NID": 1403
    }
  ]
}
```

```json
{
    "msg": "You suck"
}
```

