# Subscribes

## /updated/course/{cid}
cid is obligatory. You have to be participant to the course. You will get an incoming response like this.

In the header there will be an new attribute `type` which is set to `updated`
```json
{
  "msg": "A course got an updated",
  "cid": 1
}
```

