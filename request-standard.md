## 请求数据规范

### 目录
- [文件上传](#文件上传)
- [文件下载、收藏、喜欢](#文件下载收藏喜欢)
- [文件搜索](#文件搜索)
#### 文件上传
```
{
  "token": "hash",
  "action", "upload",
  "file": {
    "hash": "hash",
    "type": "",
    "name": "string",
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
 * @action download, collect, like
 */
{
  "token": "hash",
  "action": "string",
  "file": {
    "hash": "hash",
    "initiator": "user_id",
    "time": timestamp
  }
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
  "file": {
    "name": "string",
    "filter": ["", "", "", ...],
    "initiator": "user_id",
    "time": timestamp
  }
}
```
