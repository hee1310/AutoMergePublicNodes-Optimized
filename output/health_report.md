# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-05 20:13:05 |
| 运行耗时 | 529.0s |
| 订阅源总数 | 111 |
| 健康订阅源 | 90 |
| 原始节点 | 232567 |
| 去重后节点 | 63837 |
| TCP 可达 | 3000 |
| 真实可用 | 353 |
| Verified 输出 | 101 |
| Global 输出 | 300 |
| All 输出 | 63837 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 120.0 |
| geo | 1.7 |
| tcp | 201.2 |
| probe | 86.7 |
| real_test | 66.8 |
| china_check | 25.4 |
| write_verified | 0.0 |
| generate | 27.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 120439 |
| vmess | 38190 |
| trojan | 27749 |
| shadowsocks | 27561 |
| socks | 7776 |
| http | 5567 |
| hysteria2 | 4917 |
| shadowsocksr | 249 |
| tuic | 68 |
| hysteria | 35 |
| anytls | 16 |

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
| 91.23 | shadowsocks | 263.1 | 1.5 | 21.69 | 14.95 | 7.31 | 14.0 | 17.28 | Au1rxx-base64 | 156.146.38.170 |
| 91.06 | shadowsocks | 240.3 | 1.4 | 22.22 | 14.95 | 7.04 | 14.0 | 17.28 | Au1rxx-base64 | 156.146.38.169 |
| 90.39 | shadowsocks | 280.6 | 11.7 | 21.28 | 14.56 | 7.27 | 14.0 | 17.28 | Au1rxx-base64 | 156.146.38.167 |
| 90.05 | shadowsocks | 258.2 | 13.5 | 21.8 | 14.5 | 7.31 | 14.0 | 17.28 | Au1rxx-base64 | 156.146.38.168 |
| 89.24 | shadowsocks | 307.5 | 4.8 | 20.66 | 14.82 | 6.82 | 14.0 | 17.28 | Au1rxx-base64 | 37.19.198.243 |
| 88.26 | shadowsocks | 326.7 | 4.5 | 20.21 | 14.83 | 6.98 | 14.0 | 17.28 | Au1rxx-base64 | 37.19.198.160 |
| 87.2 | shadowsocks | 297.5 | 3.5 | 20.89 | 14.87 | 6.99 | 14.0 | 17.28 | Au1rxx-base64 | 45.86.51.18 |
| 86.48 | shadowsocks | 298.8 | 1.8 | 20.86 | 14.93 | 6.83 | 14.0 | 17.28 | Au1rxx-base64 | 198.98.53.130 |
| 86.24 | shadowsocks | 301.0 | 4.2 | 20.81 | 14.84 | 7.1 | 14.0 | 17.28 | Au1rxx-base64 | 37.19.198.244 |
| 85.9 | shadowsocks | 303.3 | 4.9 | 20.76 | 14.82 | 7.08 | 14.0 | 17.28 | Au1rxx-base64 | 51.222.136.236 |
| 85.59 | shadowsocks | 283.7 | 1.5 | 21.21 | 14.94 | 6.78 | 14.0 | 17.28 | Au1rxx-base64 | 95.215.201.18 |
| 85.29 | shadowsocks | 307.3 | 3.9 | 20.67 | 14.86 | 6.98 | 14.0 | 17.28 | Au1rxx-base64 | 193.151.163.18 |
| 85.2 | shadowsocks | 328.4 | 1.6 | 20.18 | 14.94 | 6.94 | 14.0 | 17.28 | Au1rxx-base64 | 193.151.160.9 |
| 85.16 | hysteria2 | 230.0 | 2.1 | 22.45 | 14.92 | 0.0 | 12.19 | 18.6 | mheidari-all | promo3.goonars.com |
| 84.97 | trojan | 314.6 | 0.7 | 20.5 | 14.97 | 7.74 | 11.5 | 17.28 | Au1rxx-base64 | 66.163.112.76 |
| 84.9 | vless | 300.3 | 30.8 | 20.83 | 13.84 | 7.34 | 9.72 | 17.28 | Au1rxx-base64 | 45.63.53.81 |
| 84.84 | vless | 311.2 | 34.3 | 20.57 | 13.71 | 7.4 | 9.72 | 17.28 | Au1rxx-base64 | 195.123.235.183 |
| 84.52 | hysteria2 | 288.2 | 36.7 | 21.11 | 13.62 | 0.0 | 12.19 | 18.6 | mheidari-all | 88.216.195.188 |
| 84.23 | shadowsocks | 322.2 | 0.3 | 20.32 | 14.99 | 7.02 | 14.0 | 17.28 | Au1rxx-base64 | 173.244.56.9 |
| 83.66 | shadowsocks | 336.5 | 0.7 | 19.99 | 14.97 | 4.86 | 14.0 | 17.28 | Au1rxx-base64 | 193.151.160.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.993 | 0.984 | 63 | 593 | prefer |
| mheidari-all | 0.926 | 0.85 | 160 | 14461 | prefer |
| Surfboard-tg-mixed | 0.894 | 0.825 | 57 | 8690 | prefer |
| Au1rxx-base64 | 0.799 | 0.732 | 138 | 1751 | prefer |
| tg-LonUp_M | 0.365 | 1.0 | 3 | 177 | observe |
| DeltaKronecker-all | 0.335 | 1.0 | 1 | 2653 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| ALL | 0.287 | 0.196 | 56 | 114168 | observe |
| peasoft-NoMoreWalls | 0.259 | 1.0 | 1 | 96 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5039 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10977 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6065 | observe |
| barry-far-vless | 0.255 | None | 0 | 6358 | observe |
| github_links | 0.255 | None | 0 | 35748 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 37 |
| test_one_timeout | 15.0s | - | 34 |
| 204 | ClientOSError | - | 14 |
| 204 | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 5 |
| geo | TimeoutError | - | 5 |
| cn-block | ProxyError | - | 4 |
| speed | ClientOSError | - | 3 |
| geo | ProxyError | - | 2 |
| geo | ClientOSError | - | 2 |
| cn-block | TimeoutError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 91 | 101 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
