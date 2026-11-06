# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-06 07:07:46 |
| 运行耗时 | 548.9s |
| 订阅源总数 | 111 |
| 健康订阅源 | 90 |
| 原始节点 | 232447 |
| 去重后节点 | 63660 |
| TCP 可达 | 3000 |
| 真实可用 | 407 |
| Verified 输出 | 79 |
| Global 输出 | 300 |
| All 输出 | 63660 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 120.0 |
| geo | 1.6 |
| tcp | 201.6 |
| probe | 87.5 |
| real_test | 77.5 |
| china_check | 34.4 |
| write_verified | 0.0 |
| generate | 26.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 120069 |
| vmess | 38243 |
| trojan | 27424 |
| shadowsocks | 27422 |
| socks | 8200 |
| http | 5894 |
| hysteria2 | 4828 |
| shadowsocksr | 244 |
| tuic | 66 |
| hysteria | 37 |
| anytls | 20 |

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
| 92.34 | shadowsocks | 238.6 | 6.2 | 22.26 | 14.77 | 10.0 | 13.33 | 15.98 | Au1rxx-base64 | 149.22.95.183 |
| 89.85 | hysteria2 | 226.9 | 20.6 | 22.53 | 14.23 | 4.99 | 13.12 | 15.98 | Au1rxx-base64 | 66.94.121.46 |
| 88.16 | vless | 262.3 | 2.4 | 21.71 | 14.91 | 8.07 | 10.0 | 15.98 | Au1rxx-base64 | 45.63.53.81 |
| 87.08 | shadowsocks | 279.8 | 9.2 | 21.3 | 14.65 | 10.0 | 13.33 | 15.98 | Au1rxx-base64 | 95.215.201.18 |
| 85.98 | trojan | 274.5 | 0.8 | 21.42 | 14.97 | 8.31 | 9.8 | 15.98 | Au1rxx-base64 | 66.163.114.106 |
| 84.99 | shadowsocks | 291.8 | 9.6 | 21.02 | 14.64 | 10.0 | 13.33 | 15.98 | Au1rxx-base64 | 173.244.56.9 |
| 84.95 | shadowsocks | 221.7 | 1.4 | 22.65 | 14.95 | 0.0 | 13.33 | 18.52 | mheidari-all | 137.184.89.151 |
| 84.61 | hysteria2 | 239.4 | 9.8 | 22.24 | 14.63 | 7.62 | 13.12 | 15.98 | Au1rxx-base64 | 8.209.247.109 |
| 83.76 | shadowsocks | 309.4 | 1.2 | 20.62 | 14.95 | 9.85 | 13.33 | 15.98 | Au1rxx-base64 | 149.22.87.241 |
| 83.68 | shadowsocks | 316.2 | 0.9 | 20.46 | 14.97 | 9.84 | 13.33 | 15.98 | Au1rxx-base64 | 149.22.87.204 |
| 83.47 | trojan | 293.1 | 0.2 | 20.99 | 14.99 | 8.21 | 9.8 | 15.98 | Au1rxx-base64 | 66.163.112.76 |
| 83.04 | shadowsocks | 329.4 | 2.6 | 20.15 | 14.9 | 6.81 | 13.33 | 15.98 | Au1rxx-base64 | 156.146.38.169 |
| 82.53 | trojan | 295.8 | 2.4 | 20.93 | 14.91 | 9.62 | 9.8 | 15.98 | Au1rxx-base64 | 66.163.112.242 |
| 82.47 | trojan | 297.0 | 0.2 | 20.9 | 14.99 | 8.21 | 9.8 | 15.98 | Au1rxx-base64 | 66.163.112.13 |
| 82.39 | shadowsocks | 249.2 | 4.7 | 22.01 | 14.82 | 0.0 | 13.33 | 17.88 | Surfboard-tg-mixed | 38.145.220.193 |
| 81.98 | vless | 289.6 | 6.1 | 21.07 | 14.77 | 8.34 | 10.0 | 15.98 | Au1rxx-base64 | 195.123.240.65 |
| 81.93 | shadowsocks | 285.7 | 12.7 | 21.16 | 14.52 | 9.87 | 13.33 | 15.98 | Au1rxx-base64 | 149.22.87.240 |
| 81.62 | vless | 244.0 | 11.3 | 22.13 | 14.58 | 0.0 | 10.0 | 18.52 | mheidari-all | 198.2.251.107 |
| 81.59 | trojan | 267.6 | 1.8 | 21.58 | 14.93 | 8.42 | 9.8 | 15.98 | Au1rxx-base64 | 66.163.114.245 |
| 81.24 | vless | 438.4 | 2.6 | 17.63 | 14.9 | 9.68 | 10.0 | 15.98 | Au1rxx-base64 | 169.40.42.90 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 1.0 | 1.0 | 101 | 639 | prefer |
| Surfboard-tg-mixed | 0.959 | 0.893 | 56 | 8762 | prefer |
| Au1rxx-base64 | 0.889 | 0.824 | 125 | 1751 | prefer |
| mheidari-all | 0.85 | 0.773 | 194 | 14233 | prefer |
| ALL | 0.397 | 0.312 | 80 | 113829 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5039 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2653 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10891 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6268 | observe |
| barry-far-vless | 0.255 | None | 0 | 6478 | observe |
| github_links | 0.255 | None | 0 | 35748 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4703 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 43 |
| 204 | ProxyError | - | 37 |
| 204 | TimeoutError | - | 14 |
| 204 | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 5 |
| cn-block | TimeoutError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| geo | ProxyError | - | 4 |
| geo | ClientOSError | - | 3 |
| speed | ProxyError | - | 2 |
| speed | TimeoutError | - | 2 |
| geo | TimeoutError | - | 1 |
| cn-block | ServerDisconnectedError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 101 | 79 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
