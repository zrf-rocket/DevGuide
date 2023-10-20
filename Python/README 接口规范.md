分页格式1

```json
{
  "result": true,
  "message": "",
  "code": 200,
  "data": [
    {
      "id": 1,
      "name": "test1"
    },
    {
      "id": 2,
      "name": "test2"
    }
  ],
  "meta": {
    "total": 100
  }
}

```

分页格式2

```json
{
  "result": true,
  "message": "",
  "code": 200,
  "data": {
    "total": 10,
    "results": [
      {
        "id": 1,
        "name": "test1"
      },
      {
        "id": 2,
        "name": "test2"
      }
    ]
  }
}
```

返回空列表

```json
{
  "result": true,
  "message": "",
  "code": 200,
  "data": []
}
```

```json
{
  "result": true,
  "message": "",
  "code": 200,
  "data": [
    {
      "code": "110000",
      "name": "北京市"
    },
    {
      "code": "120000",
      "name": "天津市"
    }
  ]
}
```
