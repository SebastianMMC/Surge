# Surge

#### 广告拦截
- 自动生成
- 数据来源：[`https://github.com/SukkaW/Surge/tree/master`](https://github.com/SukkaW/Surge/tree/master)
```ini
RULE-SET,https://ruleset.isagood.day/reject.conf,REJECT
RULE-SET,https://ruleset.isagood.day/reject_drop.conf,REJECT-DROP
DOMAIN-SET,https://ruleset.isagood.day/reject_tinygif.conf,REJECT-TINYGIF
```

#### Apple CDN
- 自动生成
- 数据来源：[https://github.com/felixonmars/dnsmasq-china-list/blob/master/apple.china.conf](https://github.com/felixonmars/dnsmasq-china-list/blob/master/apple.china.conf)
- Apple 在中国大陆提供 CDN 的域名
```ini
DOMAIN-SET,https://ruleset.isagood.day/apple_cdn_domain.conf,[Replace with your policy]
```

#### Apple Service
- 自动生成
- 数据来源：[https://github.com/SukkaW/Surge/blob/master/Source/non_ip/apple_services.conf](https://github.com/SukkaW/Surge/blob/master/Source/non_ip/apple_services.conf)
- 苹果服务
```ini
RULE-SET,https://ruleset.isagood.day/apple_services.conf,[Replace with your policy],extended-matching
```

#### Apple All
- 手动维护
- Apple 所有域名
```ini
RULE-SET,https://ruleset.isagood.day/apple_domain.conf,[Replace with your policy],extended-matching
```

#### Telegram
- 手动维护
```ini
# Telegram 合集
RULE-SET,https://ruleset.isagood.day/telegram.conf,[Replace with your policy]
# DC 1
RULE-SET,https://ruleset.isagood.day/telegram_dc1.conf,[Replace with your policy]
# DC 2
RULE-SET,https://ruleset.isagood.day/telegram_dc2.conf,[Replace with your policy]
# DC 3
RULE-SET,https://ruleset.isagood.day/telegram_dc3.conf,[Replace with your policy]
# DC 4
RULE-SET,https://ruleset.isagood.day/telegram_dc4.conf,[Replace with your policy]
# DC 5
RULE-SET,https://ruleset.isagood.day/telegram_dc5.conf,[Replace with your policy]
# 其他服务
RULE-SET,https://ruleset.isagood.day/telegram_other.conf,[Replace with your policy]
```

#### WeChat
- 手动维护
```ini
# 非+86
RULE-SET,https://ruleset.isagood.day/wechat.conf,[Replace with your policy]
```

#### Bard
- 手动维护
```ini
RULE-SET,https://ruleset.isagood.day/bardai.conf,[Replace with your policy]
```
#### OpenAI
- 手动维护
```ini
https://ruleset.isagood.day/openai.conf,[Replace with your policy]
```

