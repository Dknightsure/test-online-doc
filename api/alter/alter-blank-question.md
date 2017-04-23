# 修改填空题

请求地址：`/api/alter-blank-question`

请求方式：post

请求参数：

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| _id | string | 填空题 id |
| title | string | 题目标题 |
| selections | array[string] | 答案(一个填空题可能有多个空) |
| diffculty | number | 难度 |

# 添加填空题

请求地址：`/api/add-blank-question`

请求方式：POST

请求参数：

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| title | String | 题目标题 |
| selections | Array[String] | 答案(一个填空题可能有多个空) |
| diffculty | Number | 难度 |

# 删除填空题

请求地址：`/api/remove-blank-question`

请求方式：POST

请求参数：

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| id | String | 题目 ID |

# 获取填空题列表

请求地址：`/api/query-blank-question`

请求方式：POST