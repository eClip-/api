# Subscribes

## /updated/course/{cid}
cid is obligatory. You have to be participant to the course. You will get an incoming response like this.
In the header the will be an new attribute type:updated
```json
{
  "msg": "A course got an updated",
  "cid": 1
}
```

