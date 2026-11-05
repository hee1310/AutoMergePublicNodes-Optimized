# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-05 07:06:44 |
| 运行耗时 | 504.6s |
| 订阅源总数 | 111 |
| 健康订阅源 | 90 |
| 原始节点 | 233613 |
| 去重后节点 | 63394 |
| TCP 可达 | 3000 |
| 真实可用 | 408 |
| Verified 输出 | 91 |
| Global 输出 | 300 |
| All 输出 | 63394 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 120.0 |
| geo | 1.7 |
| tcp | 185.7 |
| probe | 73.0 |
| real_test | 78.4 |
| china_check | 26.5 |
| generate | 19.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 120503 |
| vmess | 37897 |
| trojan | 29026 |
| shadowsocks | 27507 |
| socks | 7768 |
| http | 5612 |
| hysteria2 | 4920 |
| shadowsocksr | 255 |
| tuic | 67 |
| hysteria | 39 |
| anytls | 19 |

## 评分权重

| 因子 | 权重 |
| --- | --- |
| latency | 25.0 |
| jitter | 15.0 |
| tcp | 10.0 |
| speed | 10.0 |
| fingerprint_resistance | 5.0 |
| protocol_history | 15.0 |
| source_history | 20.0 |

## Top 节点评分

| 评分 | 协议 | 延迟(ms) | 抖动(ms) | 延迟分 | 抖动分 | TCP分 | 协议历史分 | 来源历史分 | 来源 | 服务器 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 97.67 | trojan | 246.5 | 1.6 | 22.07 | 14.94 | 9.98 | 14.14 | 19.04 | Au1rxx-base64 | 66.163.114.132 |
| 97.22 | trojan | 241.3 | 1.5 | 22.19 | 14.94 | 10.0 | 14.14 | 19.04 | Au1rxx-base64 | 66.163.114.45 |
| 97.02 | trojan | 244.3 | 0.9 | 22.12 | 14.97 | 9.25 | 14.14 | 19.04 | Au1rxx-base64 | 66.163.114.106 |
| 96.9 | trojan | 245.5 | 3.2 | 22.09 | 14.88 | 9.25 | 14.14 | 19.04 | Au1rxx-base64 | 66.163.114.166 |
| 96.69 | trojan | 258.9 | 0.8 | 21.79 | 14.97 | 9.25 | 14.14 | 19.04 | Au1rxx-base64 | 66.163.114.114 |
| 96.54 | trojan | 244.6 | 3.5 | 22.12 | 14.87 | 8.87 | 14.14 | 19.04 | Au1rxx-base64 | 66.163.114.126 |
| 96.37 | trojan | 253.9 | 5.6 | 21.9 | 14.79 | 9.34 | 14.14 | 19.04 | Au1rxx-base64 | 66.163.114.245 |
| 96.21 | trojan | 175.2 | 6.9 | 23.72 | 14.74 | 7.07 | 14.14 | 19.04 | Au1rxx-base64 | 216.106.186.32 |
| 95.17 | trojan | 179.3 | 0.2 | 23.63 | 14.99 | 5.87 | 14.14 | 19.04 | Au1rxx-base64 | 216.106.186.33 |
| 93.96 | trojan | 261.7 | 7.2 | 21.72 | 14.73 | 9.86 | 14.14 | 19.04 | Au1rxx-base64 | 167.88.61.198 |
| 91.95 | trojan | 180.5 | 0.9 | 23.6 | 14.97 | 2.7 | 14.14 | 19.04 | Au1rxx-base64 | resources.findlocaljobnetworkandbuildcommunityconnections.com |
| 91.72 | hysteria2 | 381.3 | 2.8 | 18.95 | 14.9 | 6.59 | 13.24 | 19.04 | Au1rxx-base64 | 66.94.121.46 |
| 91.23 | trojan | 265.0 | 7.3 | 21.64 | 14.73 | 10.0 | 14.14 | 19.04 | Au1rxx-base64 | 167.88.61.175 |
| 91.2 | trojan | 286.6 | 0.6 | 21.14 | 14.98 | 9.09 | 14.14 | 19.04 | Au1rxx-base64 | 66.163.112.76 |
| 91.07 | trojan | 206.6 | 0.2 | 23.0 | 14.99 | 2.4 | 14.14 | 19.04 | Au1rxx-base64 | www.findlocaljobnetworkandbuildcommunityconnections.com |
| 91.01 | shadowsocks | 273.1 | 5.3 | 21.45 | 14.8 | 10.0 | 13.57 | 19.04 | Au1rxx-base64 | 95.215.201.18 |
| 90.98 | trojan | 264.6 | 4.7 | 21.65 | 14.82 | 9.86 | 14.14 | 19.04 | Au1rxx-base64 | 167.88.61.193 |
| 90.93 | shadowsocks | 292.6 | 2.4 | 21.0 | 14.91 | 10.0 | 13.57 | 19.04 | Au1rxx-base64 | 173.244.56.6 |
| 90.88 | trojan | 254.4 | 3.4 | 21.89 | 14.87 | 9.86 | 14.14 | 19.04 | Au1rxx-base64 | 167.88.61.20 |
| 90.24 | vless | 262.5 | 13.1 | 21.7 | 14.51 | 8.67 | 10.1 | 19.04 | Au1rxx-base64 | 45.63.53.81 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.931 | 0.95 | 20 | 555 | prefer |
| mheidari-all | 0.93 | 0.857 | 105 | 14576 | prefer |
| Au1rxx-base64 | 0.864 | 0.797 | 246 | 1751 | prefer |
| Surfboard-tg-mixed | 0.847 | 0.771 | 131 | 8675 | prefer |
| ALL | 0.5 | 0.417 | 48 | 115536 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 6752 | observe |
| ermaozi-get_subscribe | 0.269 | 1.0 | 1 | 351 | observe |
| chromego_merge | 0.264 | 1.0 | 1 | 228 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5005 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2526 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10857 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6030 | observe |
| barry-far-vless | 0.255 | None | 0 | 6243 | observe |
| github_links | 0.255 | None | 0 | 35748 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 60 |
| 204 | ProxyError | - | 33 |
| 204 | ClientOSError | - | 8 |
| cn-block | TimeoutError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 4 |
| speed | TimeoutError | - | 3 |
| speed | ClientOSError | - | 3 |
| speed | ProxyError | - | 2 |
| 204 | TimeoutError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | True | 91 | 40 | 0.5 |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
