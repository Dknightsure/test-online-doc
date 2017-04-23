 # 添加练习记录

请求地址：`/api/add-practice-answer`

请求方式：post

请求参数：

Paper 的 JSON 对象

# 获取可以参加练习的试卷列表

请求地址：`/api/get-practice-list`

请求方式：post

请求参数：

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| type | String | 试卷类型 |

返回结果：

Paper 对象列表

# 获取练习结果列表

请求地址：`/api/get-practice-record`

请求方式：post

请求参数：

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| user | String | 用户 ID |

返回结果：

Practice 对象列表

# 获取练习详细结果

请求地址：`/api/get-practice-result`

请求方式：post

请求参数：

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| paperId | String | 试卷 ID | 
| examId | String | 考试记录 ID |

```
{
  paper: {},
  practice: {}
}
```
列表