# Xray-core/sing-box 一键脚本快速安装

- [感谢 JetBrains 提供的非商业开源软件开发授权](https://www.jetbrains.com/?from=v2ray-agent)
- [Thanks for non-commercial open source development authorization by JetBrains](https://www.jetbrains.com/?from=v2ray-agent)

- [English Version](https://github.com/mack-a/v2ray-agent/blob/master/documents/en/README_EN.md)
- [VPS选购攻略，避坑指南](https://www.592083.xyz/archives/1679975663984)
- [TG频道](https://t.me/v2rayAgentChannel)、[TG群组](https://t.me/technologyshare)、[官方网站](https://www.592083.xyz/)
- [RackNerd低价AS4837套餐，年付10美起](https://www.592083.xyz/archives/racknerdtao-can-zheng-li-nian-fu-10mei-yuan)
- [传家宝级别搬瓦工（GIA、软银），强烈推荐](https://bandwagonhost.com/aff.php?aff=64917&pid=94)
- 终极套餐搬瓦工（GIA、软银、CMI），强烈推荐。[THE PLAN v1](https://bandwagonhost.com/aff.php?aff=64917&pid=144)、[THE PLAN v2](https://bandwagonhost.com/aff.php?aff=64917&pid=131)

- **请给个⭐支持一下**

# 一、项目介绍

## 核心

- Xray-core
- sing-box

## 协议

> 以下均使用TLS，支持多种协议组合

- VLESS(Reality、Vision(TCP)、WS、gRPC、XHTTP)
- VMess(TCP、WS、HTTPUpgrade)
- Trojan(TCP、gRPC)
- Hysteria2(sing-box)
- Tuic(sing-box)
- NaiveProxy(sing-box)

## 功能

- 支持不同核心之间的配置读取
- 支持个性化安装单个协议
- [支持无域名版本的VLESS Reality搭建](https://www.592083.xyz/archives/1708584312877)
- [支持多种分流用于解锁（wireguard、IPv6、Socks5、DNS、VMess(ws)、SNI反向代理）](https://www.592083.xyz/archives/ba-he-yi-jiao-ben-yu-ming-fen-liu-jiao-cheng)
- [支持批量添加CDN节点并配合ClashMeta自动优选](https://www.592083.xyz/archives/1684858575649)
- 支持普通证书和通配符证书自动申请及更新
- [支持订阅以及多VPS组合订阅](https://www.592083.xyz/archives/1681804748677)
- 支持批量新增端口[仅支持Xray-core]
- 支持核心的升级以及回退
- 支持自主更换伪装站点
- 支持BT下载管理以及域名黑名单管理

# 二、使用指南

- [八合一脚本从入门到精通](https://www.592083.xyz/archives/1710141233)
- [脚本快速搭建教程](https://www.592083.xyz/archives/1682491479771)
- [垃圾VPS大救星，hysteria2最新协议一键搭建](https://www.592083.xyz/archives/1697162969693)
- [Tuic V5性能提升及使用方法](https://www.592083.xyz/archives/1687167522196)
- [Cloudflare优选IP、自动选择最快节点教程](https://www.592083.xyz/archives/1684858575649)
- [脚本使用注意事项](https://www.592083.xyz/archives/1679931532764)
- [脚本异常处理](https://www.592083.xyz/archives/1684115970026)

# 三、线路推荐

- [VPS选购指南,避坑指南](https://www.592083.xyz/archives/1679975663984)

## 1.高端

- [CN2 GIA](https://www.592083.xyz/tags/cn2-gia)
- [AS9929](https://www.592083.xyz/tags/as9929)
- [日本软银](https://www.592083.xyz/tags/ruan-yin)

## 2.性价比

- [AS4837](https://www.592083.xyz/tags/as4837)
- [CMI](https://www.592083.xyz/tags/cmi)

# 四、安装使用

## 1.下载脚本

- 支持快捷方式启动，安装完毕后，shell输入【**vasma**】即可打开脚本，脚本执行路径[**/etc/v2ray-agent/install.sh**]

- Github

```
wget -P /root -N --no-check-certificate "https://raw.githubusercontent.com/mack-a/v2ray-agent/master/install.sh" && chmod 700 /root/install.sh && /root/install.sh
```

- 官方网站【备用】

```
wget -P /root -N --no-check-certificate "https://www.592083.xyz/v2ray-agent/install.sh" && chmod 700 /root/install.sh && /root/install.sh
```

## 2.使用

# 五、反馈和建议

-

# 六、捐赠

- 感谢您对开源项目的关注和支持。如果您觉得这个项目对您有帮助，欢迎通过以下方式进行捐赠。


# 七、许可证

[AGPL-3.0](https://github.com/mack-a/v2ray-agent/blob/master/LICENSE)
💡 声明
本项目由VTEXS的「项目开源免费VPS计划」提供算力支持。
感谢VTEXS对开源社区的支持！
