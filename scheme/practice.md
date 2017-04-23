# 练习记录

### 数据结构

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| _id | ObjectId | 考试记录 ID |
| paperId | String | 试卷 ID |
| user | String | 用户 ID |
| paperId | String | 试卷 ID |
| singleQuestions | Array | 单选题 |
| mutipleQuestions | Array | 多选题 |
| blankQuestions | Array | 填空题 |
| judgementQuestions | Array | 填空题 |



### 示例

```
{
    "_id" : ObjectId("58fb861e7af58af6be41be02"),
    "paperId" : "58fb7de55cb6fbf4cc0f68f8",
    "user" : "hushuo",
    "date" : 1492878878958.0,
    "judgementQuestions" : [ 
        {
            "answer" : 0,
            "_id" : ObjectId("58fb7de55cb6fbf4cc0f68fc")
        }, 
        {
            "answer" : 1,
            "_id" : ObjectId("58fb7de55cb6fbf4cc0f68fd")
        }
    ],
    "blankQuestions" : [ 
        {
            "_id" : ObjectId("58fb7de55cb6fbf4cc0f68fb"),
            "selections" : [ 
                {
                    "title" : "adsf",
                    "_id" : ObjectId("58f042c45bc03b0ea1dbd6c4")
                }, 
                {
                    "title" : "asdfsafsdf",
                    "_id" : ObjectId("58f042c45bc03b0ea1dbd6c3")
                }
            ]
        }
    ],
    "mutipleQuestions" : [ 
        {
            "_id" : ObjectId("58fb7de55cb6fbf4cc0f68fa"),
            "answer" : [ 
                0
            ]
        }
    ],
    "singleQuestions" : [ 
        {
            "answer" : 0,
            "_id" : ObjectId("58fb7de55cb6fbf4cc0f68f9")
        }
    ],
    "__v" : 0
}
```