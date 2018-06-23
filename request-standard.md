## 请求数据规范

### 目录
- [文件上传](#文件上传)
- [文件下载、收藏、喜欢、删除](#文件下载收藏喜欢删除)
- [文件搜索](#文件搜索)
#### 文件上传
```
{
  "token": "hash",
  "action", "upload",
  "data": [
    {
      "file": {
        "hash": "hash",
        "type": "",
        "name": "string",
        "size": number,
      }
      "path": "string",
      "create_time": timestamp,
      "owner": "user_id",
      "": ""
    },
    ...
  ]
}
```

#### 文件下载、收藏、喜欢、删除
```
/* 
 * @action download, collect, like, delete
 */
{
  "token": "hash",
  "action": "string",
  "data": [
    "file": {
      "hash": "string",
      "initiator": "user_id",
      "time": timestamp
    },
    ...
  ]
}
```

#### 文件搜索
```
/* 
 * @action search
 * @filter 过滤条件
 */
{
  "token": "hash",
  "action": "search",
  "data":{
    "keywords": "string",
    "filter": ["", "", ...],
    "initiator": "user_id",
    "time": timestamp
  }
}
```
