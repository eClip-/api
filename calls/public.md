# Public API
These calls do not require any permission

## /register
```json
{
  "reply-to": "yoloqueue",
  "email": "test1@tasdfsdfest.de",
  "username": "test",
  "password": "test"
}
```
## /login
### first option
request:
```json
{
  "reply-to": "yoloqueue",
  "username": "test",
  "password": "test"
}
```
response:
```json
{
  "token": "87db1ad0-6e70-4744-9b02-9f222b12d9d5"
}
```
### second option
Login via token, but there has been an issue closed...
