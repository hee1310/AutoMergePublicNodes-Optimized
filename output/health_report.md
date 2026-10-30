# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-30 06:01:38 |
| 运行耗时 | 316.2s |
| 订阅源总数 | 111 |
| 健康订阅源 | 86 |
| 原始节点 | 99867 |
| 去重后节点 | 27982 |
| TCP 可达 | 3000 |
| 真实可用 | 490 |
| Verified 输出 | 107 |
| Global 输出 | 300 |
| All 输出 | 27982 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 14.1 |
| geo | 1.3 |
| tcp | 88.1 |
| probe | 87.0 |
| real_test | 90.6 |
| china_check | 19.8 |
| write_verified | 0.1 |
| generate | 15.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 62569 |
| vmess | 14330 |
| shadowsocks | 10848 |
| trojan | 9474 |
| hysteria2 | 2246 |
| shadowsocksr | 165 |
| http | 143 |
| socks | 50 |
| tuic | 16 |
| anytls | 15 |
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
| 94.8 | hysteria2 | 235.0 | 16.5 | 22.34 | 14.38 | 10.0 | 13.12 | 18.46 | Au1rxx-base64 | 129.213.91.185 |
| 92.82 | shadowsocks | 246.7 | 0.5 | 22.07 | 14.98 | 10.0 | 13.31 | 18.46 | Au1rxx-base64 | 37.19.198.160 |
| 92.8 | shadowsocks | 247.7 | 0.2 | 22.04 | 14.99 | 10.0 | 13.31 | 18.46 | Au1rxx-base64 | 37.19.198.244 |
| 92.51 | shadowsocks | 251.1 | 6.1 | 21.97 | 14.77 | 10.0 | 13.31 | 18.46 | Au1rxx-base64 | 37.19.198.236 |
| 92.34 | shadowsocks | 266.8 | 0.9 | 21.6 | 14.97 | 10.0 | 13.31 | 18.46 | Au1rxx-base64 | 37.19.198.243 |
| 92.05 | shadowsocks | 247.3 | 7.2 | 22.05 | 14.73 | 10.0 | 13.31 | 18.46 | Au1rxx-base64 | 185.230.230.18 |
| 91.79 | shadowsocks | 258.9 | 6.9 | 21.78 | 14.74 | 10.0 | 13.31 | 18.46 | Au1rxx-base64 | 193.151.163.18 |
| 91.29 | vless | 315.9 | 8.0 | 20.47 | 14.7 | 10.0 | 9.66 | 18.46 | Au1rxx-base64 | 169.40.42.104 |
| 90.75 | shadowsocks | 310.5 | 3.0 | 20.59 | 14.89 | 10.0 | 13.31 | 18.46 | Au1rxx-base64 | 15.204.233.41 |
| 90.48 | trojan | 299.0 | 0.9 | 20.86 | 14.97 | 9.74 | 12.79 | 18.46 | Au1rxx-base64 | 170.101.101.53 |
| 90.46 | vless | 358.3 | 3.7 | 19.48 | 14.86 | 10.0 | 9.66 | 18.46 | Au1rxx-base64 | 169.40.42.168 |
| 89.82 | vless | 388.1 | 2.5 | 18.79 | 14.91 | 10.0 | 9.66 | 18.46 | Au1rxx-base64 | 169.40.42.235 |
| 89.36 | vless | 258.3 | 14.9 | 21.8 | 14.44 | 10.0 | 9.66 | 18.46 | Au1rxx-base64 | 167.17.69.171 |
| 89.27 | trojan | 413.3 | 5.0 | 18.21 | 14.81 | 10.0 | 12.79 | 18.46 | Au1rxx-base64 | 69.164.240.85 |
| 89.06 | shadowsocks | 293.5 | 12.1 | 20.98 | 14.55 | 10.0 | 13.31 | 18.46 | Au1rxx-base64 | 156.146.38.170 |
| 89.03 | trojan | 272.7 | 3.7 | 21.46 | 14.86 | 5.96 | 12.79 | 18.46 | Au1rxx-base64 | 170.101.101.211 |
| 89.0 | shadowsocks | 384.2 | 3.9 | 18.88 | 14.85 | 10.0 | 13.31 | 18.46 | Au1rxx-base64 | 193.151.160.18 |
| 88.99 | vless | 408.9 | 2.9 | 18.31 | 14.89 | 10.0 | 9.66 | 18.46 | Au1rxx-base64 | 169.40.42.90 |
| 88.87 | trojan | 286.0 | 0.2 | 21.16 | 14.99 | 5.97 | 12.79 | 18.46 | Au1rxx-base64 | 216.152.147.89 |
| 88.85 | trojan | 276.7 | 6.2 | 21.37 | 14.77 | 5.96 | 12.79 | 18.46 | Au1rxx-base64 | 170.101.101.19 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.975 | 1.0 | 20 | 515 | prefer |
| Au1rxx-base64 | 0.922 | 0.855 | 345 | 1735 | prefer |
| Surfboard-tg-mixed | 0.701 | 0.622 | 143 | 7756 | prefer |
| mheidari-all | 0.542 | 0.462 | 182 | 34034 | observe |
| xiaoji235-airport-v2ray-all | 0.349 | 0.667 | 3 | 6752 | observe |
| DeltaKronecker-all | 0.335 | 1.0 | 1 | 2709 | observe |
| ninja-vless | 0.327 | 1.0 | 1 | 1791 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5005 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10500 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5729 | observe |
| barry-far-vless | 0.255 | None | 0 | 5941 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4444 | observe |
| Au1rxx-clash | 0.244 | None | 0 | 1735 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 114 |
| geo | ClientOSError | - | 39 |
| cn-block | ClientOSError | - | 10 |
| speed | ClientOSError | - | 10 |
| 204 | ProxyError | - | 9 |
| cn-block | TimeoutError | - | 7 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 2 |
| speed | TimeoutError | - | 2 |
| 204 | TimeoutError | - | 2 |
| geo | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 90 | 107 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
