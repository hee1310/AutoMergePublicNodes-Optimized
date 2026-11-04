# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-04 23:55:53 |
| 运行耗时 | 301.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 87 |
| 原始节点 | 81907 |
| 去重后节点 | 26702 |
| TCP 可达 | 3000 |
| 真实可用 | 448 |
| Verified 输出 | 33 |
| Global 输出 | 300 |
| All 输出 | 26702 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| geo | 1.3 |
| tcp | 75.9 |
| probe | 98.2 |
| real_test | 74.9 |
| china_check | 29.2 |
| write_verified | 0.0 |
| generate | 14.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49176 |
| vmess | 14062 |
| shadowsocks | 9071 |
| trojan | 7627 |
| hysteria2 | 1609 |
| shadowsocksr | 148 |
| http | 77 |
| socks | 68 |
| hysteria | 33 |
| anytls | 21 |
| tuic | 15 |

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
| 90.54 | hysteria2 | 264.0 | 1.8 | 21.67 | 14.93 | 10.0 | 10.26 | 15.18 | Au1rxx-base64 | 129.213.91.185 |
| 89.45 | shadowsocks | 287.9 | 3.4 | 21.11 | 14.87 | 10.0 | 12.79 | 15.18 | Au1rxx-base64 | 45.86.51.18 |
| 89.13 | shadowsocks | 273.0 | 9.2 | 21.46 | 14.66 | 10.0 | 12.79 | 15.18 | Au1rxx-base64 | 193.151.163.18 |
| 89.12 | vless | 261.5 | 3.7 | 21.72 | 14.86 | 7.31 | 10.05 | 15.18 | Au1rxx-base64 | 195.123.235.183 |
| 88.64 | shadowsocks | 285.3 | 40.0 | 21.17 | 13.5 | 10.0 | 12.79 | 15.18 | Au1rxx-base64 | 37.19.198.244 |
| 88.31 | vless | 279.6 | 4.2 | 21.3 | 14.84 | 9.8 | 10.05 | 15.18 | Au1rxx-base64 | 159.89.87.21 |
| 88.29 | shadowsocks | 295.3 | 19.4 | 20.94 | 14.27 | 10.0 | 12.79 | 15.18 | Au1rxx-base64 | 185.230.230.18 |
| 88.09 | shadowsocks | 284.9 | 1.7 | 21.18 | 14.94 | 10.0 | 12.79 | 15.18 | Au1rxx-base64 | 37.19.198.236 |
| 87.55 | vless | 360.5 | 1.2 | 19.43 | 14.95 | 9.87 | 10.05 | 15.18 | Au1rxx-base64 | 167.17.69.171 |
| 87.55 | vless | 380.6 | 3.4 | 18.97 | 14.87 | 9.83 | 10.05 | 15.18 | Au1rxx-base64 | 169.40.42.89 |
| 85.75 | vless | 379.4 | 5.9 | 19.0 | 14.78 | 10.0 | 10.05 | 15.18 | Au1rxx-base64 | 169.40.42.35 |
| 85.06 | vless | 338.9 | 14.8 | 19.93 | 14.44 | 10.0 | 10.05 | 15.18 | Au1rxx-base64 | 169.40.42.74 |
| 84.9 | vless | 401.1 | 1.3 | 18.49 | 14.95 | 9.82 | 10.05 | 15.18 | Au1rxx-base64 | 169.40.42.202 |
| 84.58 | vless | 380.0 | 3.3 | 18.98 | 14.87 | 10.0 | 10.05 | 15.18 | Au1rxx-base64 | 45.138.100.248 |
| 84.55 | trojan | 248.3 | 7.2 | 22.03 | 14.73 | 8.89 | 7.22 | 15.18 | Au1rxx-base64 | 216.152.147.48 |
| 84.11 | vless | 385.8 | 3.6 | 18.85 | 14.86 | 7.69 | 10.05 | 15.18 | Au1rxx-base64 | 169.40.42.229 |
| 83.57 | trojan | 278.5 | 2.2 | 21.33 | 14.92 | 7.42 | 7.22 | 15.18 | Au1rxx-base64 | 170.101.101.19 |
| 83.51 | vless | 385.7 | 6.2 | 18.85 | 14.77 | 6.97 | 10.05 | 15.18 | Au1rxx-base64 | 2.24.124.64 |
| 83.15 | vless | 355.1 | 2.2 | 19.56 | 14.92 | 9.83 | 10.05 | 15.18 | Au1rxx-base64 | 169.40.42.168 |
| 82.79 | shadowsocks | 365.7 | 1.3 | 19.31 | 14.95 | 10.0 | 12.79 | 15.18 | Au1rxx-base64 | 156.146.38.167 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.968 | 0.897 | 87 | 8651 | prefer |
| zhangkai | 0.923 | 1.0 | 19 | 43 | prefer |
| Au1rxx-base64 | 0.893 | 0.826 | 241 | 1751 | prefer |
| mheidari-all | 0.879 | 0.802 | 197 | 14725 | prefer |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5005 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2526 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10844 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6015 | observe |
| barry-far-vless | 0.255 | None | 0 | 6228 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4612 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 56 |
| 204 | ProxyError | - | 9 |
| 204 | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| cn-block | TimeoutError | - | 3 |
| speed | ClientOSError | - | 2 |
| geo | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |
| geo | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 40 | 33 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
