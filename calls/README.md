# ePC (*eClip Procedure Call*)

## Scheme
eCPs follow the following basic scheme:
`/action/entity/ID`
### Action
- save: Creates a new record or updates an existing one
- get: Reads one or all records of the requested entity
- delete: Deletes the specified record

### Entity
- Course
- User
- Participation
- Pack

### ID
- optional for get and save
- required for delete
