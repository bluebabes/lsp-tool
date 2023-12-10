## 老司机工具

[商店](https://chrome.google.com/webstore/detail/enekgmgmfmgmjndgahlnggndehihfjoi)

zip下载地址：[releases](https://github.com/bluebabes/lsp-tool/releases)

<img width="429" alt="image" src="https://github.com/bluebabes/lsp-tool/assets/3329261/b49305a0-fc22-4866-ab54-bbe1fef8f35e">

### 功能

1. 百度云地址补全
2. 磁力链接补全
3. 百家姓加密
4. 百家姓解密
5. 价值观加密
6. 价值观解密
7. 与佛论禅加密
8. 与佛论禅解密
9. 右键自定义搜索功能（google/baidu/jav/磁力）
10. 百度盘自动下载（自动下载）
11. 定时器功能（倒计时提醒,默认30秒）

### 配置

商店审核配置无法包含敏感内容，下面是一些敏感配置

右键搜索配置，其中 %s 是特殊制定符号，代表需要替换的文本

```
[
  {
    "action": "http://pan.baidu.com/s/%s",
    "name": "百度云地址补全"
  },
  {
    "action": "magnet:?xt=urn:btih:%s",
    "name": "磁力链接补全",
    "open": false
  },
  {
    "action": "Bjx-encode",
    "name": "百家姓加密",
    "open": false
  },
  {
    "action": "Bjx-decode",
    "name": "百家姓解密",
    "open": false
  },
  {
    "action": "Jzg-encode",
    "name": "价值观加密",
    "open": false
  },
  {
    "action": "Jzg-decode",
    "name": "价值观解密",
    "open": false
  },
  {
    "action": "yflc-encode",
    "name": "与佛论禅加密",
    "open": false
  },
  {
    "action": "yflc-decode",
    "name": "与佛论禅解密",
    "open": false
  },
  {
    "action": "https://www.google.com/search?q=%s",
    "name": "Google"
  },
  {
    "action": "https://www.google.com/search?q=%s site:hjd2048.com",
    "name": "2048"
  },
  {
    "action": "https://www.google.com/search?q=%s 新片速遞 site:hjd2048.com",
    "name": "2048-新片速遞"
  },
  {
    "action": "https://www.baidu.com/s?wd=%s",
    "name": "baidu"
  },
  {
    "action": "https://javbus.com/%s",
    "name": "javbus"
  },
  {
    "action": "http://www.javlibrary.com/cn/vl_searchbyid.php?keyword=%s",
    "name": "javlibrary"
  },
  {
    "action": "https://clm307.buzz/search-%s-0-1-1.html",
    "name": "磁力猫"
  },
  {
    "action": "https://wuqiandi.top/search?keyword=%s&sos=length&sofs=all&sot=all&soft=all&som=exact&p=1",
    "name": "吴签磁力"
  },
  {
    "action": " https://duo5.link/",
    "name": "磁力多"
  },
  {
    "action": "https://bt4g.org/search/%s",
    "name": "磁力bt4g"
  },
  {
    "action": "https://rarbg.to/torrents.php?category=2;4&search=%s&order=size&by=DESC",
    "name": "rarbg"
  },
  {
    "action": "https://sukebei.nyaa.si/?f=0&c=0_0&q=_%s",
    "name": "sukebei磁力"
  },
  {
    "action": "https://u3c3.com/?p=2&search2=fjeofakansriji&search=%s",
    "name": "u3c3"
  },
    {
    "name": "baidupan",
    "action": "autodownload"
  },
  {
    "name": "倒计时",
    "action": "countdown",
    "time": "30",
    "on": false
  }
]

```

