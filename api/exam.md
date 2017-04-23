 # 添加考试记录

请求地址：`/api/add-exam-answer`

请求方式：post

请求参数：

Paper 的 JSON 对象

# 获取可以参加考试的试卷列表

请求地址：`/api/get-exams`

请求方式：post

请求参数：

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| type | String | 试卷类型 |

返回结果：

Paper 对象的列表

# 获取考试结果列表

请求地址：`/api/get-exam-list`

请求方式：post

请求参数：

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| user | String | 用户 ID |

返回记过：

Exam 对象的列表

# 获取考试详细结果

请求地址：`/api/get-exam-result`

请求方式：post

请求参数：

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| paperId | String | 试卷 ID | 
| examId | String | 考试记录 ID | 

返回结果：
```
{
  "paper"： {}，
  "exam": {}
}
```
列表

