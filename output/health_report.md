# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-06 19:39:29 |
| 运行耗时 | 521.4s |
| 订阅源总数 | 111 |
| 健康订阅源 | 89 |
| 原始节点 | 231414 |
| 去重后节点 | 63717 |
| TCP 可达 | 3000 |
| 真实可用 | 367 |
| Verified 输出 | 48 |
| Global 输出 | 300 |
| All 输出 | 63717 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 120.0 |
| geo | 1.7 |
| tcp | 204.1 |
| probe | 71.3 |
| real_test | 73.3 |
| china_check | 29.7 |
| write_verified | 0.0 |
| generate | 21.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 118988 |
| vmess | 38455 |
| shadowsocks | 27621 |
| trojan | 27494 |
| socks | 8061 |
| http | 5649 |
| hysteria2 | 4769 |
| shadowsocksr | 254 |
| tuic | 65 |
| hysteria | 36 |
| anytls | 22 |

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
| 94.97 | shadowsocks | 235.5 | 1.0 | 22.33 | 14.96 | 10.0 | 13.9 | 17.78 | Au1rxx-base64 | 156.146.38.170 |
| 94.14 | shadowsocks | 271.8 | 0.7 | 21.49 | 14.97 | 10.0 | 13.9 | 17.78 | Au1rxx-base64 | 156.146.38.167 |
| 90.46 | shadowsocks | 406.1 | 1.6 | 18.38 | 14.94 | 10.0 | 13.9 | 17.78 | Au1rxx-base64 | 37.19.198.244 |
| 89.45 | shadowsocks | 234.2 | 0.7 | 22.36 | 14.97 | 4.44 | 13.9 | 17.78 | Au1rxx-base64 | 156.146.38.169 |
| 89.05 | shadowsocks | 240.0 | 0.6 | 22.22 | 14.98 | 10.0 | 13.9 | 17.78 | Au1rxx-base64 | 156.146.38.168 |
| 88.98 | shadowsocks | 322.8 | 0.1 | 20.3 | 15.0 | 10.0 | 13.9 | 17.78 | Au1rxx-base64 | 95.215.201.18 |
| 88.92 | shadowsocks | 323.5 | 0.6 | 20.29 | 14.98 | 10.0 | 13.9 | 17.78 | Au1rxx-base64 | 173.244.56.9 |
| 88.82 | shadowsocks | 301.5 | 1.1 | 20.8 | 14.96 | 10.0 | 13.9 | 17.78 | Au1rxx-base64 | 149.22.95.183 |
| 88.67 | shadowsocks | 349.6 | 4.0 | 19.69 | 14.85 | 10.0 | 13.9 | 17.78 | Au1rxx-base64 | 173.244.56.6 |
| 88.5 | vless | 292.7 | 0.5 | 21.0 | 14.98 | 6.81 | 10.0 | 17.78 | Au1rxx-base64 | 195.123.235.183 |
| 88.49 | vless | 325.2 | 5.3 | 20.25 | 14.8 | 9.33 | 10.0 | 17.78 | Au1rxx-base64 | 159.89.87.21 |
| 87.84 | vless | 425.0 | 0.8 | 17.94 | 14.97 | 10.0 | 10.0 | 17.78 | Au1rxx-base64 | 169.40.42.35 |
| 87.48 | shadowsocks | 434.4 | 12.1 | 17.72 | 14.55 | 10.0 | 13.9 | 17.78 | Au1rxx-base64 | 51.222.136.236 |
| 87.38 | shadowsocks | 479.8 | 3.4 | 16.67 | 14.87 | 10.0 | 13.9 | 17.78 | Au1rxx-base64 | 37.19.198.160 |
| 87.23 | shadowsocks | 326.0 | 6.1 | 20.23 | 14.77 | 8.89 | 13.9 | 17.78 | Au1rxx-base64 | 193.151.160.18 |
| 87.09 | vless | 354.9 | 1.0 | 19.56 | 14.96 | 10.0 | 10.0 | 17.78 | Au1rxx-base64 | 169.40.42.74 |
| 86.38 | vless | 284.3 | 1.0 | 21.2 | 14.96 | 6.62 | 10.0 | 17.78 | Au1rxx-base64 | 45.63.53.81 |
| 85.87 | trojan | 317.6 | 0.5 | 20.43 | 14.98 | 10.0 | 10.42 | 17.78 | Au1rxx-base64 | 66.23.203.21 |
| 85.85 | shadowsocks | 280.8 | 2.2 | 21.28 | 14.92 | 10.0 | 13.9 | 17.78 | Au1rxx-base64 | 37.19.198.243 |
| 85.53 | trojan | 351.4 | 0.5 | 19.64 | 14.98 | 10.0 | 10.42 | 17.78 | Au1rxx-base64 | 216.238.80.100 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.992 | 1.0 | 33 | 513 | prefer |
| mheidari-all | 0.922 | 0.855 | 55 | 14184 | prefer |
| Au1rxx-base64 | 0.829 | 0.761 | 222 | 1751 | prefer |
| Surfboard-tg-mixed | 0.811 | 0.734 | 158 | 8758 | prefer |
| ALL | 0.344 | 0.259 | 85 | 113013 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 179 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4934 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10962 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6135 | observe |
| barry-far-vless | 0.255 | None | 0 | 6479 | observe |
| github_links | 0.255 | None | 0 | 35748 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4703 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 63 |
| test_one_timeout | 15.0s | - | 50 |
| 204 | TimeoutError | - | 19 |
| 204 | ClientOSError | - | 10 |
| cn-block | ProxyError | - | 10 |
| cn-block | ClientOSError | - | 5 |
| cn-block | TimeoutError | - | 4 |
| geo | ProxyError | - | 3 |
| geo | TimeoutError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 79 | 48 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
