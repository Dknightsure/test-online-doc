# 判断题

### 数据结构

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| _id | ObjectId | 填空题 ID |
| title | String | 题目标题 |
| answer | Number | 答案(0 代表 否，1 代表 是) |
| diffculty | Number | 难度 |
| type | String | 类型 |



### 示例

```
{
  "_id" : ObjectId("58368b93bd9e202f499c0bef"),
  "title" : "题目标题",
  "answer" : 1,
  "diffculty" : 3.5,
  "type" : "judgement"
}
```