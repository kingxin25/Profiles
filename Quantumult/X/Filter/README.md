在「配置文件」选择「编辑」，在「[filter_remote]」内如下添加文本

```
[filter_remote]
https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/X/Filter/Unbreak.list, tag=后续规则修正, enabled=true
https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/X/Filter/Advertising.list, tag=广告, enabled=true
https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/X/Filter/Hijacking.list, tag=运营商劫持及恶意网站, enabled=true
https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/X/Filter/GlobalMedia.list, tag=国际流媒体服务, enabled=true
https://raw.githubusercontent.com/hw0220/Profiles/master/Quantumult/X/Filter/Cydia.list, tag=Cydia,enabled=true
https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/X/Filter/Global.list, tag=全球加速, enabled=true
https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/X/Filter/Apple.list, tag=Apple 服务, enabled=true
https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/X/Filter/China.list, tag=中国直连, enabled=true


```

若不清楚可看图文教程：[Quantumult X 导入配置及安装证书](https://medium.com/circumvention-technology/import-profile-on-quantumult-x-6dca41b597d8)

更多策略可查阅：https://github.com/ConnersHua/Profiles/tree/master/Quantumult/X/Filter/
