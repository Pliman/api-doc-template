### 新建项目

1. [新建项目](#新建项目)

#### 新建项目

*URL*

    POST /api/projects

*请求参数*

| 名称 | 是否必须 | 默认值 | 说明 |
|-------|-----------|----------|-------|
| projectName| 是 | | 项目名 |
| owner | 是 | | 项目拥有者 |
*返回结果*

    {
        "code": 0,
        "message": "成功",
        "project": {[Project](http://github.com/Pliman/api-doc-template/wikis/object-defination#%E9%A1%B9%E7%9B%AEproject)}
    }
