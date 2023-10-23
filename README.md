# 世界各国基本信息数据集
> 截止2019年，世界上共有233个国家和地区，其中国家有195个，地区有38个

此项目是根据业务需要整理的各个国家的中文名、英文名、字母缩写、经纬度、国旗emoji字符🇨🇳、国旗png图片等，共计 `117` 个国家   
## 我新增加到  
此项目是根据业务需要整理的各个国家的中文名、英文名、字母缩写、经纬度、国旗emoji字符🇨🇳、国旗png图片等，共计 `139` 个国家  

我新增的不需要emoji,所以emoji这里只是引用了国家码 同时[tw]繁体这里使用了简体字 

【在github上找了一圈，没有符合期望的数据，于是结合3个github的开源项目的信息，整理出的一份集合】


基本格式如下：
```json
[
    {
        "code": 86, //地区码
        "tw": "中國", //繁体中文名
        "en": "China", //英文名
        "locale": "CN", //缩写
        "zh": "中国", //简体中文名
        "lat": 35.86166, //纬度 latitude
        "lng": 104.195397, //经度 longitude
        "emoji": "🇨🇳" //emoji字符
    },
    {
        "code": 244,
        "tw": "安哥拉",
        "en": "Angola",
        "locale": "AO",
        "zh": "安哥拉",
        "lat": -9.3005898,
        "lng": 14.9134098,
        "emoji": "🇦🇴"
    },
    {
        "code": 93,
        "tw": "阿富汗",
        "en": "Afghanistan",
        "locale": "AF",
        "zh": "阿富汗",
        "lat": 34.352865,
        "lng": 62.20402869999999,
        "emoji": "🇦🇫"
    },
    ...

]
```



共享出来，希望对大家有帮助。

- 如果对您有帮助，欢迎star
- 如果您有补充，欢迎提merge
