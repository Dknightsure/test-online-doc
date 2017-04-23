# 考试记录

### 数据结构

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| _id | ObjectId | 考试记录 ID |
| paperId | String | 试卷 ID |
| user | String | 用户 ID |
| paperId | String | 试卷 ID |
| result | Boolean | 考试结果（及格 TRUE，不及格 FALSE） |
| singleQuestions | Array | 单选题 |
| mutipleQuestions | Array | 多选题 |
| blankQuestions | Array | 填空题 |
| judgementQuestions | Array | 填空题 |



### 示例

```
{
    "_id" : ObjectId("58fb93e0f5ba23f95b877702"),
    "result" : false,
    "paperId" : "58fb9380f5ba23f95b8776fb",
    "user" : "hushuo",
    "date" : 1492882400080.0,
    "judgementQuestions" : [ 
        {
            "result" : false,
            "answer" : 0,
            "_id" : ObjectId("58fb9380f5ba23f95b8776ff")
        }
    ],
    "blankQuestions" : [ 
        {
            "result" : false,
            "_id" : ObjectId("58fb9380f5ba23f95b8776fe"),
            "selections" : [ 
                {
                    "title" : "阿斯顿发斯蒂芬",
                    "_id" : ObjectId("58f042c45bc03b0ea1dbd6c4")
                }, 
                {
                    "title" : "",
                    "_id" : ObjectId("58f042c45bc03b0ea1dbd6c3")
                }
            ]
        }
    ],
    "mutipleQuestions" : [ 
        {
            "result" : false,
            "_id" : ObjectId("58fb9380f5ba23f95b8776fd"),
            "answer" : [ 
                0
            ]
        }
    ],
    "singleQuestions" : [ 
        {
            "result" : true,
            "answer" : 0,
            "_id" : ObjectId("58fb9380f5ba23f95b8776fc")
        }
    ]
    "__v" : 0
}
```