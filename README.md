# We are under attack!

本仓库用于记录 B3log 系列站点被 CC、DDoS 和恶意访问攻击的记录，不定期更新。

## 使用方式

使用你的公网 IP，通过 GitHub 提供的搜索功能搜索本库（“In this repository”），从搜索命中结果来判断你是否已经沦为攻击者的肉鸡。

如果你的 IP 出现在搜索结果中，请注意统计自己的网络流量从而发现攻击应用。目前我们分析，攻击是从 Headless 浏览器发出的，如果你安装过类似应用请密切关注其网络使用情况。

## 数据来源

原始日志数据来自 B3log 正在使用的一些服务：

* 七牛云融合 CDN 日志
* 阿里云 DDoS 日志
* 应用服务器日志

## 鸣谢

* [ip2region](https://github.com/lionsoul2014/ip2region)：最自由的 IP 地址查询库 The most free IP address query library
