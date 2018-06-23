## 请求时提交的数据规范
#### 文件上传
```
{
  "token": "hash",
  "type", "upload"
  "data": {
    "file_hash": "hash",
    "file_type": "",
    "file_name": "string",
    "size": number,
    "path": "file_path",
    "create_time": timestamp,
    "owner": "user_id"
  }
}
```

#### 文件下载、收藏、喜欢
```
/* 
 * @type download, collect, like
 */
{
  "token": "hash",
  "type": "string",
  "data": {
    "file_hash": "hash",
    "initiator": "user_id",
    "time": timestamp
  }
}
```

#### 文件搜索
```
/* 
 * @type search
 * @filter 过滤条件
 */
{
  "token": "hash",
  "type": "search",
  "data": {
    "file_name": "string",
    "filter": ["", "", "", ...],
    "initiator": "user_id",
    "time": timestamp
  }
}
```
