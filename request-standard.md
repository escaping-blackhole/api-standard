## 请求时提交的数据规范
#### 文件上传
```
{
  "type": "file_upload",
  "token": "hash",
  "data": {
    "file_hash": "hash",
    "initiator": "user_id",
    "file_name": "string",
    "path": "file_path",
    "create_time": "timestamp"
  }
}
```
