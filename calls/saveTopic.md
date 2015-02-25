# savePaper

```json
{
  "CID": 364, //Course ID obligatorisch
  "ID": 365, //Topic exisitiert bereits
  "title": "letitle",
  "nodes": [
    {
      "isStart": "true",
      "PID": 366, //Verweis auf Paper
      "target_ID": "1402-f213-4cb5", //Target_ID die nicht gespeichert wird, wird nur als Referenz benutzt
      "links": [
        {
          "ID": 376, //Link exisitiert bereits
          "type": "default", 
          "target_ID": "1401-f213-4cb5", //Referenz 
          "NID": 1337                    // zu Node mit ID 1337
        },
        {
          "ID": 378, //Link exisitiert, aber es gab eine Veränderung
          "type": "fork", 
          "target_ID": "1403-f213-4cb5" //Referenz zum unten definierten Topic
        }
      ]
    },
    {
      "ID": 1337,
      "PID": 366,
      "target_ID": "1401-f213-4cb5",
      "links": [
        {
          "ID": 391,
          "type": "default",
          "target_ID": "1402-f213-4cb5" //Endlosschleife
        }
      ]
    },
    {
      "TID": 400, //Node als Topic
      "target_ID": "1403-f213-4cb5"
    }
  ]
}
```

```json
{
    "msg": "You suck"
}
```

