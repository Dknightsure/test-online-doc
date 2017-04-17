# 多选题

### 数据结构

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| _id | ObjectId | 多选题 ID |
| title | String | 题目标题 |
| selections | Array | 题目标题 |
| answer | Array | 答案（对应 selections 里的下标） |
| diffculty | Number | 难度 |
| type | String | 类型 |



### 示例

```
{
    "_id" : ObjectId("58368b93bd9e202f499c0bef"),
    "title" : "题目标题",
    "answer" : [0, 2]
    "diffculty" : 3.5,
    "type" : "mutiple",
    "selections" : [
        {
            "title": "adsafsd"
        },
        {
            "title": "adsafsd"
        },
        {
            "title": "adsafsd"
        },
        {
            "title": "adsafsd"
        }
    ]
}
```