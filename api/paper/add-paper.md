# 添加试卷

请求地址：`/api/add-paper`

请求方式：POST

请求参数：

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| name | String | 试卷标题 |
| singleQuestions | Array | 单选题 |
| mutipleQuestions | Array | 多选题 |
| blankQuestions | Array | 填空题 |