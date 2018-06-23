## 响应数据规范
### 目录
- []()

#### 文件上传
```
{
  "status": number,
  "msg": "用户提示信息",
  "data": {
    "list": [
       {
         "file_hash": "hash",
         "file_type": "string",
         "file_name": "string",
         "size": number,
         "path": "file_path",
         "create_time": timestamp,
         "download_count": number,
         "collect_count": number,
         "like_count": number
       },
       ...
    ]
  }
}
```

#### 文件下载、收藏、喜欢
```
/* 
 * @path 文件的相对路径
 */
{
  "status": number,
  "msg": "用户提示信息",
  "data": {
    "file_hash": "hash",
    "path": "string",
    "download_count": number,
    "collect_count": number,
    "like_count": number
  }
}
```

#### 文件搜索
```
/* 
 * @total 结果数量
 * @list 搜索的结果集
 */
{
  "status": number,
  "msg": "用户提示信息",
  "data": {
    "total": number,
    "list": [
       {
         "file_hash": "hash",
         "file_type": "string",
         "file_name": "string",
         "size": number,
         "path": "file_path",
         "create_time": timestamp,
         "download_count": number,
         "collect_count": number,
         "like_count": number,
         "owner": "user_id"
       },
       ...
    ]
  }
}
```
