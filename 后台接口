# knowledge-sharing-system
知识分享系统

## 目录
- [用户](#用户)
- [专业](#专业)
- [课程](#课程)
- [文件](#文件)

***
### 用户
***

#### 1.用户列表信息 <br>

**url:http://localhost:8088/demo/manage/user/list**
**type: post**

> request

     pageNum,pageSize
     
> response

success

	{
	    "status": 0,
	    "msg": null,
	    "data": {
	        "total": 5,
	        "list": [
	            {
	                "userId": 2,
	                "nickname": null,
	                "username": "?",
	                "password": "8C491AA8E35D13E9DFC7768B9B76829E",
	                "email": null,
	                "userSchool": null,
	                "userNo": null,
	                "userMajor": null,
	                "integral": null,
	                "gmtCreate": "2018-06-24 10:57:23"
	            },
	            {
	                "userId": 5,
	                "nickname": null,
	                "username": "和21",
	                "password": "8C491AA8E35D13E9DFC7768B9B76829E",
	                "email": null,
	                "userSchool": null,
	                "userNo": null,
	                "userMajor": null,
	                "integral": null,
	                "gmtCreate": "2018-06-27 11:42:03"
	            },
	            {
	                "userId": 6,
	                "nickname": null,
	                "username": "和212",
	                "password": "8C491AA8E35D13E9DFC7768B9B76829E",
	                "email": null,
	                "userSchool": null,
	                "userNo": null,
	                "userMajor": null,
	                "integral": null,
	                "gmtCreate": "2018-06-27 11:42:04"
	            },
	            {
	                "userId": 7,
	                "nickname": null,
	                "username": "和2121",
	                "password": "8C491AA8E35D13E9DFC7768B9B76829E",
	                "email": null,
	                "userSchool": null,
	                "userNo": null,
	                "userMajor": null,
	                "integral": null,
	                "gmtCreate": "2018-06-27 11:42:05"
	            },
	            {
	                "userId": 8,
	                "nickname": null,
	                "username": "qqq",
	                "password": "5240358412DC9CB103BA5BD40947D1A6",
	                "email": null,
	                "userSchool": null,
	                "userNo": null,
	                "userMajor": null,
	                "integral": null,
	                "gmtCreate": "2018-06-28 17:10:04"
	            }
	        ],
	        "pageNum": 1,
	        "pageSize": 10,
	        "size": 5,
	        "startRow": 1,
	        "endRow": 5,
	        "pages": 1,
	        "prePage": 0,
	        "nextPage": 0,
	        "isFirstPage": true,
	        "isLastPage": true,
	        "hasPreviousPage": false,
	        "hasNextPage": false,
	        "navigatePages": 8,
	        "navigatepageNums": [
	            1
	        ],
	        "navigateFirstPage": 1,
	        "navigateLastPage": 1,
	        "firstPage": 1,
	        "lastPage": 1
	    },
	    "success": true
	}

fail

***

#### 2.删除用户 <br>
**url:http://10.10.57.62:8088/demo/manage/user/{id}**
**type: delete**
> request    id可为数组  如: 01,02,02

     无参数
> response

success

	  {
	    "status": 0,
	    "msg": "删除成功",
	    "data": {},
	    "success": true
	   }

fail

    {
	    "status": 1,
	    "msg": "删除失败",
	    "data": null,
	    "success": false
    }

***

#### 3.修改用户 <br>
**url:http://10.10.57.62:8088/demo/manage/user/{id}**
**type: put**
> request  (只需要提交需要修改的数据)

     userId,nickname,username,password,email,userSchool,userNo,userMajor,integral
> response  

success

	   {
	    "status": 0,
	    "msg": "修改成功",
	    "data": {},
	    "success": true
	   }

fail  有很多种情况  具体再讨论

    {
	    "status": 1,
	    "msg": "删除失败",
	    "data": null,
	    "success": false
    }

***

#### 4.添加用户 <br>
**url:http://10.10.57.62:8088/demo/manage/user/**
**type: post**
> request  

     userId,nickname,username,password,email,userSchool,userNo,userMajor,integral
> response  

success

	   {
	    "status": 0,
	    "msg": "添加成功成功",
	    "data": null,
	    "success": true
	   }

fail  有很多种情况  具体再讨论

    {
	    "status": 1,
	    "msg": "添加失败",
	    "data": null,
	    "success": false
    }
    
	{
	    "status": 1,
	    "msg": "用户名已存在",
	    "data": null,
	    "success": false
	}


***
### 课程
***
#### 1.课程列表信息 <br>
**url:http://localhost:8088/demo/manage/course/list**
**type: post**
> request

     pageNum,pageSize,majorName
     
> response

success

	{
	    "status": 0,
	    "msg": null,
	    "data": {
	        "total": 4,
	        "list": [
	            {
	                "courseId": "011",
	                "courseName": "计算机网络"
	            },
	            {
	                "courseId": "012",
	                "courseName": "软件工程"
	            },
	            {
	                "courseId": "013",
	                "courseName": "操作系统"
	            },
	            {
	                "courseId": "014",
	                "courseName": "数据结构"
	            }
	        ],
	        "pageNum": 1,
	        "pageSize": 10,
	        "size": 4,
	        "startRow": 1,
	        "endRow": 4,
	        "pages": 1,
	        "prePage": 0,
	        "nextPage": 0,
	        "isFirstPage": true,
	        "isLastPage": true,
	        "hasPreviousPage": false,
	        "hasNextPage": false,
	        "navigatePages": 8,
	        "navigatepageNums": [
	            1
	        ],
	        "navigateFirstPage": 1,
	        "navigateLastPage": 1,
	        "firstPage": 1,
	        "lastPage": 1
	    },
	    "success": true
	}

fail

***

#### 2.删除课程 <br>
**url:http://10.10.57.62:8088/demo/manage/course/{id}**
**type: delete**
> request    id可为数组  如: 01,02,02

     无参数
> response

success

	  {
	    "status": 0,
	    "msg": "删除成功",
	    "data": {},
	    "success": true
	   }

fail

    {
	    "status": 1,
	    "msg": "删除失败",
	    "data": null,
	    "success": false
    }

***

#### 3.修改课程 <br>
**url:http://10.10.57.62:8088/demo/manage/course/{id}**
**type: put**
> request  (只需要提交需要修改的数据)

     courseId,courseName
> response  

success

	   {
	    "status": 0,
	    "msg": "修改成功",
	    "data": {},
	    "success": true
	   }

fail  有很多种情况  具体再讨论

    {
	    "status": 1,
	    "msg": "修改失败",
	    "data": null,
	    "success": false
    }


***
### 专业
***
### 文件
***

#### 1.文件显示 <br>
**url:http://10.10.57.62:8088/demo/manage/file/{id}**
**type: put**
> request  (只需要提交需要修改的数据)

     courseId,courseName
> response  

success
      {
	    "status": 0,
	    "msg": "修改成功",
	    "data": 显示:文件名,文件摘要，路径，创建日期，收藏次数，喜欢次数，下载次数
	    "success": true
      }

fail  有很多种情况  具体再讨论

     {
	    "status": 1,
	    "msg": "修改失败",
	    "data": null,
	    "success": false
     }

***



#### 5.模板 <br>
**url:http://10.10.57.62:8088/demo/user/list**
**type: post**
> request

     无参数
> response

success

	{
	    "status": 0,
	    "msg": "",
	    "data": {}
	}

fail

    {
    "status": 1,
    "msg": ""
    }








