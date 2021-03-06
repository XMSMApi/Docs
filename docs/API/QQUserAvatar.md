---
    title: QQ用户头像获取
    tags:
        - API
---
<span class="http">HTTP GET/POST</span>  
请求地址: https://fs.lolimapis.ml/QQUserAvatar/

# QQ头像获取
获取某个QQ用户的头像。

## 返回数据
Defult: 
```
Content-Type:image/jpeg;
```
Json: 
```json
{
    "status": 200,
    "data": {
        "qqcode": "(QQCode)",
        "size": (Size),
        "avatars": {
            "t0": "(Url0)",
            "t1": "(Url1)",
            "t2": "(Url2)",
            "t3": "(Url3)",
            "t4": "(Url4)"
        }
    }
}
```

## 参数
| 参数 | 必填 | 类型 | 说明 | 可填内容 |
| --- | --- | --- | --- | --- |
| qc | 是 | string | 需要查询的QQ号 | * |
| t | 否 | string | 接口，请求json时无效 | 0 , 1 , 2 , 3 , 4 |
| size | 否 | string | 图像质量 | 0 , 40 , 100 , 140 , 640 |
| json | 否 | isset | 请求json数据 |  |

<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-3270219743311431" crossorigin="anonymous"></script>