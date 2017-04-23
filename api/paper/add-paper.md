# 添加试卷

请求地址：`/api/add-paper`

请求方式：POST

请求参数：

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| name | String | 试卷标题 |
| time | Number | 考试时间 |
| makup | Number | 补考次数 |
| singleQuestions | Array | 单选题 |
| mutipleQuestions | Array | 多选题 |
| blankQuestions | Array | 填空题 |
| judgementQuestions | Array | 判断题 |

# 删除试卷

请求地址：`/api/remove-paper`

请求方式：POST

请求参数：

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| id | String | 试卷 ID |

# 获取试卷详情

请求地址：`/api/get-paper-detail`

请求方式：POST

请求参数：

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| id | String | 试卷 ID |

返回结果：

Paper 对象

# 改试卷为练习模式

请求地址：`/api/changeToPractice`

请求方式：POST

请求参数：

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| id | String | 试卷 ID |


# 获取试卷列表

请求地址：`/api/get-papers`

请求方式：GET

返回结果：

Paper 对象的列表