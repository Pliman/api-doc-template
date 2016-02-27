### 登陆

1. [登陆](#登陆)

#### 登陆

*URL*

    POST /api/login

*请求参数*

| 名称 | 是否必须 | 默认值 | 说明 |
|-------|-----------|----------|-------|
| usename| 是 | | 用户名 |
| password | 是 | | 密码 |
*返回结果*

    {
        "code": 0,
        "message": "成功",
        "user": {[User](http://github.com/Pliman/api-doc-template/wikis/object-defination#%E7%94%A8%E6%88%B7User)}
    }
