


**POST Data**

```
curl -X PUT -d '{
  "users": [
      {
    "name": "Mark",
    "salary": "100000"
  },
  {
    "name": "Jim",
    "salary": "200000"
  }
  ]
}' 'https://secondproject-eeef7.firebaseio.com/userdoc.json'

```

**READ Data**
```
curl 'https://secondproject-eeef7.firebaseio.com/userdoc.json'
```
