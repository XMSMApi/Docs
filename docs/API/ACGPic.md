---
    title: 随机二次元图
    tags:
        - API
---
<span class="http">HTTP GET/POST</span>  
请求地址: https://fs.lolimapis.ml/ACGPic/

# 随机二次元图
随机输出一张二次元图。

## 返回数据
```
Content-Type:image/jpeg;
```

## 参数
| 参数 | 必填 | 类型 | 说明 | 可填内容 |
| --- | --- | --- | --- | --- |
| from | 否 | string | 从何处引入。分别可以填ixiaowai（小歪API）、dmoe（樱花API），不填则从SkiMino的储存库中获取 | ixiaowai , dmoe |
| case | 否 | string | 仅from为iw233时生效。如果从iw233源引入，要用哪个方式接入 | mp , pc , neared , mirlkoi , random |
| size | 否 | string | 图像大小，默认large | large , mw1024 , mw690 , bmiddle , small , thumb180 , thumbnail , square |
| json | 否 | isset | 请求json数据 |  |

<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-3270219743311431" crossorigin="anonymous"></script>
