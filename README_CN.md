```
 _____                      
/  ___|                     
\ `--. _   _ _ __ __ _  ___ 
 `--. \ | | | '__/ _` |/ _ \
/\__/ / |_| | | | (_| |  __/
\____/ \__,_|_|  \__, |\___|
                  __/ |     
                 |___/                                   

```


# SurgeUsage

[![Platform](https://img.shields.io/badge/platform-iOS-blue.svg?style=flat)][myGithub]
[![License](https://img.shields.io/badge/license-MIT-brightgreen.svg)](https://github.com/RoyalMjz/SurgeUsage/blob/master/License)


[`English→`](https://github.com/RoyalMjz/SurgeUsage/blob/master/README.md)


## 介绍

SurgeUsage是一个在iOS9上的网络调试工具，他有很多功能，但大多数人使用它是为了FQ和屏蔽应用内广告。

## 主要功能

- 截获 iOS 上的所有应用程序的 HTTP/HTTPS/TCP 流量，将其重定向到 HTTP/HTTPS/SOCK5 代理服务器转发。
- 重载 iOS 蜂窝网络下的 DNS 服务器配置，使得 iOS 设备工作在蜂窝网络之下时，开发者也能够配置 DNS 服务器。
- 记录设备所发出/接收的 HTTP 请求/应答首部信息。
- 配置基于 domain, domain suffix, domain keyword, CIDR IP 以及 GeoIP 的过滤规则。
- 对设备上 WIFI、蜂窝网络以及代理连接会话的流量进行统计以及测速。
- 从 URL 或 iTunes 导入/导出配置文件。
- 重度使用场景下有很高的性能以及适应性。
- 基于 domain 规则屏蔽广告。
- 完全兼容蜂窝网络。


## 用法

![](https://raw.githubusercontent.com/RoyalMjz/SurgeUsage/master/images/step.png)


1. 打开应用程序

2. 点击`Download Configuration from URL`

3. 输入`https://raw.githubusercontent.com/RoyalMjz/SurgeUsage/master/Surge.conf`

4. 点击`OK`


## 协议

SurgeUsage根据MIT开源许可证授权。有关更多信息，请参阅此存储库中的LICENSE文件。


[myGithub]: https://github.com/RoyalMjz/SurgeUsage