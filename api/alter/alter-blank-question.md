# 修改填空题

请求地址：`/api/alter-blank-question`

请求方式：POST


请求参数：

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| _id | String | 填空题 ID |
| title | String | 题目标题 |
| selections | Array[String] | 答案(一个填空题可能有多个空) |
| diffculty | Number | 难度 |
| type | String | 类型 |