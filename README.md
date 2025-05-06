**地址①**：http://opendata.baidu.com/api.php?co=&resource_id=6006&oe=utf8&query=

请求类型：GET

请求参数：query

CORS跨域支持：否

请求示例：

```
https://opendata.baidu.com/api.php?co=&resource_id=6006&oe=utf8&query=121.8.215.106
```

示例结果：

```
{
  "status": "0",
  "t": "",
  "set_cache_time": "",
  "data": [
    {
      "ExtendedLocation": "",
      "OriginQuery": "121.8.215.106",
      "appinfo": "",
      "disp_type": 0,
      "fetchkey": "121.8.215.106",
      "location": "广东省广州市 电信",
      "origip": "121.8.215.106",
      "origipquery": "121.8.215.106",
      "resourceid": "6006",
      "role_id": 0,
      "shareImage": 1,
      "showLikeShare": 1,
      "showlamp": "1",
      "titlecont": "IP地址查询",
      "tplt": "ip"
    }
  ]
}
```

&emsp;

**地址②**：https://ipapi.com/ip_api.php?ip=121.8.215.106

请求类型：GET

请求参数：ip

CORS跨域支持：否

请求示例：

```
https://ipapi.com/ip_api.php?ip=121.8.215.106
```

示例结果：

```
{
    "ip": "121.8.215.106",
    "hostname": "121.8.215.106",
    "type": "ipv4",
    "continent_code": "AS",
    "continent_name": "Asia",
    "country_code": "CN",
    "country_name": "China",
    "region_code": "GD",
    "region_name": "Guangdong",
    "city": "Guangzhou",
    "zip": "510000",
    "latitude": 23.124719619750977,
    "longitude": 113.23860931396484,
    "location": {
        "geoname_id": 1809858,
        "capital": "Beijing",
        "languages": [
            {
                "code": "zh",
                "name": "Chinese",
                "native": "中文"
            }
        ],
        "country_flag": "https://assets.ipstack.com/flags/cn.svg",
        "country_flag_emoji": "🇨🇳",
        "country_flag_emoji_unicode": "U+1F1E8 U+1F1F3",
        "calling_code": "86",
        "is_eu": false
    },
    "time_zone": {
        "id": "Asia/Shanghai",
        "current_time": "2024-03-15T15:14:15+08:00",
        "gmt_offset": 28800,
        "code": "CST",
        "is_daylight_saving": false
    },
    "currency": {
        "code": "CNY",
        "name": "Chinese Yuan",
        "plural": "Chinese yuan",
        "symbol": "CN¥",
        "symbol_native": "CN¥"
    },
    "connection": {
        "asn": 4134,
        "isp": "Chinanet"
    },
    "security": {
        "is_proxy": false,
        "proxy_type": null,
        "is_crawler": false,
        "crawler_name": null,
        "crawler_type": null,
        "is_tor": false,
        "threat_level": "low",
        "threat_types": null
    }
}
```

&emsp;

**地址③**：https://ip9.com.cn/get?ip=121.8.215.106

请求类型：GET

请求参数：ip

CORS跨域支持：否

请求示例：

```
https://ip9.com.cn/get?ip=121.8.215.106
```

示例结果：

```
{
    "ret": 200,
    "data": {
        "country": "中国",
        "country_code": "cn",
        "prov": "广东",
        "city": "广州",
        "city_code": "guangzhou",
        "city_short_code": "gz",
        "area": "增城",
        "post_code": "511300",
        "area_code": "020",
        "isp": "中国电信",
        "lng": "113.829579",
        "lat": "23.290497",
        "long_ip": 2030622570,
        "big_area": "华南"
    },
    "qt": 0.001
}
```