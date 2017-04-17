# 修改单选题

请求地址：`/api/alter-single-question`

请求方式：POST


请求参数：


| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| _id | String | 单选题 ID |
| title | String | 题目标题 |
| selections | Array | 题目标题 |
| answer | Number | 答案（对应 selections 里的下标） |
| diffculty | Number | 难度 |
| type | String | 类型 |