# 单选题

### 数据结构

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| _id | ObjectId | 单选题 ID |
| title | String | 题目标题 |
| itemList | Array | 题目标题 |
| answer | Number | 答案（对应 itemList 里的下标） |
| diffculty | Number | 难度 |
| author | String | 作者 |
| type | String | 类型 |



### 示例

```
{
    "_id" : ObjectId("58368b93bd9e202f499c0bef"),
    "title" : "题目标题",
    "answer" : 1,
    "diffculty" : 3.5,
    "author" : "张三",
    "type" : "single",
    "itemList" : [ 
        "asdf", 
        "we", 
        "er"
    ]
}
```