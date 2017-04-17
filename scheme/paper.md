# 多选题

### 数据结构

| 字段 | 类型   | 描述 |
| :---:  | :----: | :----: |
| _id | ObjectId | 试卷 ID |
| name | String | 试卷标题 |
| date | Number | 试卷创建时间(时间戳) |
| singleQuestions | Array | 单选题 |
| mutipleQuestions | Array | 多选题 |
| blankQuestions | Array | 填空题 |



### 示例

```
{
    "_id" : ObjectId("583fc4343c5c757741b92b41"),
    "name" : "def",
    "date: "912738410283410234"
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
}
```