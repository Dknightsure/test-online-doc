# 修改多选题

请求地址：`/api/alter-mutiple-question`

请求方式：POST


请求参数：

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| _id | ObjectId | 多选题 ID |
| title | String | 题目标题 |
| itemList | Array | 题目标题 |
| answer | Array | 答案（对应 itemList 里的下标） |
| diffculty | Number | 难度 |
| author | String | 作者 |
| type | String | 类型 |