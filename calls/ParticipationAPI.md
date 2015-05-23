# Participation API
You have to be successfully logged in into the system.
## /join/course/{cid}
You will get a participation to the Course Id (cid). No more needs.

## /get/participation/
Returns the participations of the user.

```json
[
  {
    "role": "PARTICIPANT",
    "description": "description",
    "language": "de",
    "id": 1,
    "title": "title"
  },
  {
    "role": "PARTICIPANT",
    "description": "description",
    "language": "de",
    "id": 12,
    "title": "title"
  }
]
```
