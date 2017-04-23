# 多选题

### 数据结构

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| _id | ObjectId | 试卷 ID |
| name | String | 试卷标题 |
| date | Number | 试卷创建时间(时间戳) |
| time | Number | 考试时间（单位：分钟） |
| makeup | Number | 补考次数 |
| type | String | 试卷类型（考试 exam，练习 practice） |
| singleQuestions | Array | 单选题 |
| mutipleQuestions | Array | 多选题 |
| blankQuestions | Array | 填空题 |
| judgementQuestions | Array | 填空题 |



### 示例

```
{
    "_id" : ObjectId("583fc4343c5c757741b92b41"),
    "name" : "def",
    "date: "912738410283410234"
    "time: 10,
    "makeup": 2,
    type: "exam"
    "blankQuestions" : [ 
        {
            "title" : "qwerqwerqwerqwe",
            "diffculty" : 3,
            "_id" : ObjectId("583fc4343c5c757741b92b44"),
            "selections" : [ 
                {
                    "title": "asdfasdf"
                }
            ]
        }
    ],
    "mutipleQuestions" : [ 
        {
            "title" : "65489asdfasdf",
            "diffculty" : 12,
            "_id" : ObjectId("583fc4343c5c757741b92b43"),
            "answer" : [ 
                0, 
                1
            ],
            "selections" : [ 
                {
                    "title": "asdfadf"
                },
                {
                    "title": "asdfadf"
                },
                {
                    "title": "asdfadf"
                }
            ]
        }
    ],
    "singleQuestions" : [ 
        {
            "title" : "pqwe",
            "answer" : 0,
            "diffculty" : 3.5,
            "_id" : ObjectId("583fc4343c5c757741b92b42"),
            "selections" : [ 
                {
                    "title": "asdfadf"
                },
                {
                    "title": "asdfadf"
                },
                {
                    "title": "asdfadf"
                }
            ]
        }
    ]
    "judgementQuestions": [
        {
            "_id" : ObjectId("58368b93bd9e202f499c0bef"),
            "title" : "题目标题",
            "answer" : 1,
            "diffculty" : 3.5,
            "type" : "judgement"
        }
    ]
}
```