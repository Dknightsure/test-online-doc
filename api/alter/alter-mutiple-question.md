# 修改多选题

请求地址：`/api/alter-mutiple-question`

请求方式：POST

请求参数：

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| _id | String | 多选题 ID |
| title | String | 题目标题 |
| selections | Array | 题目标题 |
| answer | Array | 答案（对应 selections 里的下标） |
| diffculty | Number | 难度 |

# 添加多选题

请求地址：`/api/add-mutiple-question`

请求方式：POST

请求参数：

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| title | String | 题目标题 |
| selections | Array | 题目标题 |
| answer | Array | 答案（对应 selections 里的下标） |
| diffculty | Number | 难度 |

# 删除多选题

请求地址：`/api/remove-mutiple-question`

请求方式：POST

请求参数：

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| id | String | 多选题 ID |

# 获取多选题列表

请求地址：`/api/query-mutiple-question`

请求方式：GET