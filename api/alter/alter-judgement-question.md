# 修改判断题

请求地址：`/api/alter-judgement-question`

请求方式：POST

请求参数：

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| _id | ObjectId | 判断题 ID |
| title | String | 题目标题 |
| answer | Boolean | 答案 |
| diffculty | Number | 难度 |

# 添加判断题

请求地址：`/api/add-judgement-question`

请求方式：POST

请求参数：

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| title | String | 题目标题 |
| answer | Boolean | 答案 |
| diffculty | Number | 难度 |

# 删除判断题

请求地址：`/api/remove-judgement-question`

请求方式：POST

请求参数：

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| id | String | 题目 ID |

# 获取判断题列表

请求地址：`/api/query-judgement-question`

请求方式：POST