# 填空题

### 数据结构

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| _id | ObjectId | 填空题 ID |
| title | String | 题目标题 |
| answer | Array[String] | 答案(一个填空题可能有多个空) |
| diffculty | Number | 难度 |
| author | String | 作者 |
| type | String | 类型 |



### 示例

```
{
    "_id" : ObjectId("58368b93bd9e202f499c0bef"),
    "title" : "题目标题",
    "answer" : ['答案一', '答案二']
    "diffculty" : 3.5,
    "author" : "张三",
    "type" : "blank"
}
```