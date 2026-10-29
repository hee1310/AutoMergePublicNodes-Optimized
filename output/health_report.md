# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-29 22:10:43 |
| 运行耗时 | 339.5s |
| 订阅源总数 | 111 |
| 健康订阅源 | 87 |
| 原始节点 | 99369 |
| 去重后节点 | 27785 |
| TCP 可达 | 3000 |
| 真实可用 | 478 |
| Verified 输出 | 90 |
| Global 输出 | 300 |
| All 输出 | 27785 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 14.9 |
| geo | 1.4 |
| tcp | 86.6 |
| probe | 109.3 |
| real_test | 82.9 |
| china_check | 25.5 |
| write_verified | 0.1 |
| generate | 18.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 61606 |
| vmess | 15152 |
| shadowsocks | 10857 |
| trojan | 9109 |
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
| 88.76 | hysteria2 | 289.7 | 2.2 | 21.07 | 14.92 | 5.94 | 13.93 | 17.4 | Au1rxx-base64 | 129.213.91.185 |
| 88.34 | vless | 252.2 | 12.7 | 21.94 | 14.52 | 9.02 | 8.46 | 17.4 | Au1rxx-base64 | 195.123.235.177 |
| 87.97 | vless | 293.2 | 23.3 | 20.99 | 14.12 | 10.0 | 8.46 | 17.4 | Au1rxx-base64 | 66.70.179.198 |
| 87.91 | vless | 305.1 | 10.2 | 20.72 | 14.62 | 10.0 | 8.46 | 17.4 | Au1rxx-base64 | 169.40.42.235 |
| 87.76 | shadowsocks | 318.7 | 15.7 | 20.4 | 14.41 | 10.0 | 13.05 | 17.4 | Au1rxx-base64 | 185.230.230.18 |
| 87.58 | trojan | 277.5 | 1.6 | 21.35 | 14.94 | 7.62 | 11.77 | 17.4 | Au1rxx-base64 | 170.101.101.19 |
| 87.5 | shadowsocks | 295.0 | 32.8 | 20.95 | 13.77 | 9.83 | 13.05 | 17.4 | Au1rxx-base64 | 15.204.246.132 |
| 87.47 | vless | 337.5 | 7.0 | 19.97 | 14.74 | 10.0 | 8.46 | 17.4 | Au1rxx-base64 | 169.40.42.74 |
| 87.42 | vless | 262.2 | 1.8 | 21.71 | 14.93 | 8.01 | 8.46 | 17.4 | Au1rxx-base64 | 195.211.98.43 |
| 86.5 | shadowsocks | 306.4 | 7.8 | 20.69 | 14.71 | 10.0 | 13.05 | 17.4 | Au1rxx-base64 | 156.146.38.170 |
| 86.48 | shadowsocks | 326.6 | 58.5 | 20.22 | 12.81 | 10.0 | 13.05 | 17.4 | Au1rxx-base64 | 37.19.198.160 |
| 86.25 | vless | 376.4 | 18.1 | 19.07 | 14.32 | 10.0 | 8.46 | 17.4 | Au1rxx-base64 | 185.95.231.156 |
| 86.01 | trojan | 309.9 | 19.9 | 20.6 | 14.25 | 8.12 | 11.77 | 17.4 | Au1rxx-base64 | 216.152.147.85 |
| 86.0 | trojan | 261.1 | 2.3 | 21.73 | 14.91 | 5.69 | 11.77 | 17.4 | Au1rxx-base64 | 216.152.155.176 |
| 85.89 | trojan | 281.5 | 1.8 | 21.26 | 14.93 | 6.03 | 11.77 | 17.4 | Au1rxx-base64 | 216.152.147.79 |
| 85.74 | trojan | 287.7 | 2.6 | 21.12 | 14.9 | 6.05 | 11.77 | 17.4 | Au1rxx-base64 | 216.152.147.93 |
| 85.72 | vless | 374.0 | 12.4 | 19.12 | 14.54 | 10.0 | 8.46 | 17.4 | Au1rxx-base64 | 169.40.42.168 |
| 85.43 | trojan | 280.1 | 5.0 | 21.29 | 14.81 | 5.66 | 11.77 | 17.4 | Au1rxx-base64 | 170.101.101.67 |
| 85.33 | vless | 315.2 | 2.8 | 20.48 | 14.9 | 9.91 | 8.46 | 17.4 | Au1rxx-base64 | 5.34.178.120 |
| 85.32 | trojan | 316.3 | 10.3 | 20.46 | 14.61 | 9.4 | 11.77 | 17.4 | Au1rxx-base64 | 216.152.156.81 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.94 | 0.957 | 23 | 510 | prefer |
| Au1rxx-base64 | 0.923 | 0.856 | 327 | 1722 | prefer |
| Surfboard-tg-mixed | 0.853 | 0.779 | 95 | 7837 | prefer |
| mheidari-all | 0.696 | 0.617 | 162 | 33474 | observe |
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
| test_one_timeout | 15.0s | - | 73 |
| geo | ClientOSError | - | 14 |
| 204 | ProxyError | - | 10 |
| cn-block | ClientOSError | - | 8 |
| 204 | TimeoutError | - | 7 |
| cn-block | TimeoutError | - | 7 |
| speed | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |
| geo | ProxyError | - | 2 |
| speed | TimeoutError | - | 1 |
| geo | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 71 | 90 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
