# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-29 22:03:20 |
| 运行耗时 | 301.0s |
| 订阅源总数 | 111 |
| 健康订阅源 | 87 |
| 原始节点 | 99370 |
| 去重后节点 | 27785 |
| TCP 可达 | 3000 |
| 真实可用 | 484 |
| Verified 输出 | 60 |
| Global 输出 | 300 |
| All 输出 | 27785 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 10.9 |
| geo | 1.3 |
| tcp | 88.2 |
| probe | 74.9 |
| real_test | 85.8 |
| china_check | 30.2 |
| write_verified | 0.0 |
| generate | 9.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 61599 |
| vmess | 15152 |
| shadowsocks | 10862 |
| trojan | 9112 |
| hysteria2 | 2235 |
| shadowsocksr | 171 |
| http | 150 |
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
| 88.53 | shadowsocks | 245.6 | 0.2 | 22.09 | 14.99 | 10.0 | 13.05 | 17.4 | Au1rxx-base64 | 156.146.38.168 |
| 87.88 | trojan | 263.3 | 3.4 | 21.68 | 14.87 | 9.66 | 11.77 | 17.4 | Au1rxx-base64 | 66.163.114.45 |
| 87.77 | trojan | 270.6 | 1.9 | 21.51 | 14.93 | 9.66 | 11.77 | 17.4 | Au1rxx-base64 | 66.163.114.245 |
| 87.73 | shadowsocks | 278.0 | 1.6 | 21.34 | 14.94 | 10.0 | 13.05 | 17.4 | Au1rxx-base64 | 156.146.38.170 |
| 87.54 | shadowsocks | 261.7 | 3.8 | 21.72 | 14.86 | 10.0 | 13.05 | 17.4 | Au1rxx-base64 | 156.146.38.167 |
| 87.29 | shadowsocks | 236.1 | 1.1 | 22.31 | 14.96 | 8.57 | 13.05 | 17.4 | Au1rxx-base64 | 156.146.38.169 |
| 86.47 | shadowsocks | 288.6 | 0.3 | 21.1 | 14.99 | 9.58 | 13.05 | 17.4 | Au1rxx-base64 | 37.19.198.243 |
| 86.37 | shadowsocks | 298.7 | 2.7 | 20.86 | 14.9 | 10.0 | 13.05 | 17.4 | Au1rxx-base64 | 37.19.198.160 |
| 86.36 | trojan | 267.0 | 8.3 | 21.6 | 14.69 | 8.42 | 11.77 | 17.4 | Au1rxx-base64 | 66.163.114.114 |
| 86.21 | trojan | 266.0 | 3.8 | 21.62 | 14.86 | 8.19 | 11.77 | 17.4 | Au1rxx-base64 | 66.163.114.126 |
| 86.08 | trojan | 241.1 | 4.7 | 22.2 | 14.83 | 7.38 | 11.77 | 17.4 | Au1rxx-base64 | 216.152.155.23 |
| 85.84 | trojan | 267.9 | 3.0 | 21.58 | 14.89 | 7.7 | 11.77 | 17.4 | Au1rxx-base64 | 216.152.155.131 |
| 85.72 | trojan | 265.5 | 1.4 | 21.63 | 14.95 | 7.54 | 11.77 | 17.4 | Au1rxx-base64 | 216.152.155.54 |
| 85.42 | trojan | 270.0 | 0.7 | 21.53 | 14.97 | 7.38 | 11.77 | 17.4 | Au1rxx-base64 | 66.163.114.166 |
| 85.33 | trojan | 326.2 | 6.7 | 20.23 | 14.75 | 10.0 | 11.77 | 17.4 | Au1rxx-base64 | 66.163.114.106 |
| 85.26 | vless | 271.3 | 1.0 | 21.5 | 14.96 | 7.94 | 8.46 | 17.4 | Au1rxx-base64 | 195.211.98.43 |
| 85.23 | trojan | 309.2 | 3.1 | 20.62 | 14.88 | 9.56 | 11.77 | 17.4 | Au1rxx-base64 | 216.152.156.81 |
| 84.42 | trojan | 321.1 | 0.9 | 20.35 | 14.96 | 7.44 | 11.77 | 17.4 | Au1rxx-base64 | 170.101.101.211 |
| 84.38 | trojan | 263.9 | 10.1 | 21.67 | 14.62 | 8.2 | 11.77 | 17.4 | Au1rxx-base64 | 66.163.114.132 |
| 83.86 | trojan | 300.1 | 1.8 | 20.83 | 14.93 | 7.6 | 11.77 | 17.4 | Au1rxx-base64 | 216.152.156.65 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.937 | 0.955 | 22 | 510 | prefer |
| Au1rxx-base64 | 0.901 | 0.834 | 320 | 1722 | prefer |
| Surfboard-tg-mixed | 0.9 | 0.827 | 98 | 7837 | prefer |
| mheidari-all | 0.72 | 0.642 | 176 | 33474 | prefer |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 6752 | observe |
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
| test_one_timeout | 15.0s | - | 81 |
| geo | ClientOSError | - | 16 |
| 204 | ProxyError | - | 9 |
| cn-block | ClientOSError | - | 9 |
| 204 | TimeoutError | - | 5 |
| cn-block | ProxyError | - | 4 |
| cn-block | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 4 |
| speed | ClientOSError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 71 | 60 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
