# 使用说明
applications目录存放app相关内容，每新增一个application，在applications目录下创建application同名目录。
目录结构如下：
```
└─applications
    ├─tiktok
    │      app.json   // 记录application属性及特征
    │      README.md  // 帮助文档
    │      icon.png   // 尺寸： 512*512 px， 大小不超过2MB
    ├─wechat
    │      app.json
    │      README.md
    │      icon.png
```
app.json 内容模版如下
```
{
    "name":"陕西社会保险",
    "longName":"陕西社会保险",
    "developer":"陕西省社会保障局",
    "website":"http://www.pansky.com.cn/",
    "packageName":{
        "android":"cn.com.pansky.sxzgyl",
        "ios":"cn.com.pansky.sxzgyl"
    },
    "properties":{
        "category":"business-systems",
        "subcategory":"general-business",
        "content":"unknown",
        "parentApp":"",
        "risk":1
    },
    "surrogates": [
        {
          "name": "surrogate-1",
          "description": "",
          "signatures": [
            {
              "name": "signature-陕西社会保险-1",
              "description": "",
              "conditions": [
                {
                  "attributeName": "common.server_fqdn",
                  "attributeType": "string",
                  "negate_option": false,
                  "description": "",
                  "items": [
                    {
                      "item": "$zcxc.shaanxi.gov.cn",
                      "description": "陕西省社会保障局"
                    },
                    {
                      "item": "$ylbx.shaanxi.gov.cn",
                      "description": "陕西省社会保障局"
                    },
                    {
                      "item": "$s.eqxiu.cn",
                      "description": "北京中网易企秀科技有限公司"
                    },
                    {
                      "item": "$v.eqxiu.com",
                      "description": "北京中网易企秀科技有限公司"
                    }
                  ]
                }
              ]
            }
          ]
        }
    ]
}
```