# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-29 21:55:02 |
| 运行耗时 | 299.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 87 |
| 原始节点 | 99300 |
| 去重后节点 | 27781 |
| TCP 可达 | 3000 |
| 真实可用 | 484 |
| Verified 输出 | 71 |
| Global 输出 | 300 |
| All 输出 | 27781 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| geo | 1.4 |
| tcp | 88.2 |
| probe | 80.0 |
| real_test | 84.3 |
| china_check | 28.5 |
| generate | 11.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 61570 |
| vmess | 15140 |
| shadowsocks | 10848 |
| trojan | 9098 |
| hysteria2 | 2235 |
| shadowsocksr | 171 |
| http | 149 |
| socks | 49 |
| tuic | 16 |
| anytls | 13 |
| hysteria | 11 |

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
| 88.93 | shadowsocks | 221.4 | 4.6 | 22.65 | 14.83 | 10.0 | 13.05 | 17.4 | Au1rxx-base64 | 173.244.56.9 |
| 88.26 | vless | 204.5 | 17.0 | 23.04 | 14.36 | 10.0 | 8.46 | 17.4 | Au1rxx-base64 | 144.202.126.147 |
| 88.22 | vless | 201.8 | 20.0 | 23.11 | 14.25 | 10.0 | 8.46 | 17.4 | Au1rxx-base64 | 45.76.172.197 |
| 88.03 | shadowsocks | 260.3 | 3.7 | 21.75 | 14.86 | 9.97 | 13.05 | 17.4 | Au1rxx-base64 | 156.146.38.167 |
| 86.87 | trojan | 247.7 | 3.4 | 22.04 | 14.87 | 8.29 | 11.77 | 17.4 | Au1rxx-base64 | 167.88.61.175 |
| 86.73 | shadowsocks | 299.7 | 1.6 | 20.84 | 14.94 | 10.0 | 13.05 | 17.4 | Au1rxx-base64 | 95.215.201.18 |
| 86.71 | shadowsocks | 260.1 | 0.9 | 21.76 | 14.97 | 10.0 | 13.05 | 17.4 | Au1rxx-base64 | 156.146.38.170 |
| 86.47 | trojan | 220.8 | 1.3 | 22.67 | 14.95 | 7.18 | 11.77 | 17.4 | Au1rxx-base64 | 167.88.61.198 |
| 86.25 | trojan | 197.6 | 1.0 | 23.2 | 14.96 | 6.42 | 11.77 | 17.4 | Au1rxx-base64 | 66.163.112.76 |
| 86.23 | trojan | 197.2 | 2.0 | 23.21 | 14.93 | 6.42 | 11.77 | 17.4 | Au1rxx-base64 | 66.163.112.13 |
| 86.11 | vless | 292.6 | 20.0 | 21.0 | 14.25 | 10.0 | 8.46 | 17.4 | Au1rxx-base64 | 195.123.240.65 |
| 86.1 | trojan | 199.4 | 4.1 | 23.16 | 14.85 | 6.42 | 11.77 | 17.4 | Au1rxx-base64 | 66.163.112.142 |
| 85.55 | trojan | 197.0 | 0.5 | 23.22 | 14.98 | 5.68 | 11.77 | 17.4 | Au1rxx-base64 | 66.163.112.242 |
| 85.53 | trojan | 196.9 | 1.1 | 23.22 | 14.96 | 5.68 | 11.77 | 17.4 | Au1rxx-base64 | 66.163.112.121 |
| 84.68 | trojan | 277.5 | 0.7 | 21.36 | 14.97 | 8.17 | 11.77 | 17.4 | Au1rxx-base64 | 66.163.114.45 |
| 84.66 | trojan | 248.4 | 62.0 | 22.03 | 12.67 | 8.29 | 11.77 | 17.4 | Au1rxx-base64 | 167.88.61.20 |
| 84.61 | trojan | 230.7 | 0.4 | 22.44 | 14.99 | 5.51 | 11.77 | 17.4 | Au1rxx-base64 | 167.88.61.85 |
| 84.25 | trojan | 236.2 | 1.3 | 22.31 | 14.95 | 6.25 | 11.77 | 17.4 | Au1rxx-base64 | 167.88.61.193 |
| 83.93 | trojan | 315.0 | 0.1 | 20.49 | 15.0 | 8.17 | 11.77 | 17.4 | Au1rxx-base64 | 66.163.114.245 |
| 83.57 | trojan | 275.3 | 3.4 | 21.4 | 14.87 | 6.99 | 11.77 | 17.4 | Au1rxx-base64 | 66.163.114.126 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.94 | 0.957 | 23 | 510 | prefer |
| Au1rxx-base64 | 0.918 | 0.851 | 323 | 1722 | prefer |
| Surfboard-tg-mixed | 0.827 | 0.753 | 97 | 7837 | prefer |
| mheidari-all | 0.737 | 0.659 | 170 | 33474 | prefer |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 6752 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 176 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5005 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2709 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10376 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5821 | observe |
| barry-far-vless | 0.255 | None | 0 | 6033 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4444 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.244 | None | 0 | 1722 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 80 |
| geo | ClientOSError | - | 16 |
| cn-block | ClientOSError | - | 8 |
| 204 | ProxyError | - | 7 |
| 204 | TimeoutError | - | 6 |
| cn-block | TimeoutError | - | 4 |
| speed | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 3 |
| speed | ProxyError | - | 2 |
| geo | TimeoutError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | True | 71 | 11 | 0.5 |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
