# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-05 00:09:10 |
| 运行耗时 | 580.9s |
| 订阅源总数 | 111 |
| 健康订阅源 | 89 |
| 原始节点 | 233568 |
| 去重后节点 | 63768 |
| TCP 可达 | 3000 |
| 真实可用 | 427 |
| Verified 输出 | 91 |
| Global 输出 | 300 |
| All 输出 | 63768 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 120.0 |
| geo | 1.8 |
| tcp | 202.7 |
| probe | 98.9 |
| real_test | 103.5 |
| china_check | 21.1 |
| write_verified | 0.1 |
| generate | 32.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 120265 |
| vmess | 38239 |
| trojan | 29111 |
| shadowsocks | 27395 |
| socks | 7722 |
| http | 5577 |
| hysteria2 | 4886 |
| shadowsocksr | 249 |
| tuic | 66 |
| hysteria | 35 |
| anytls | 23 |

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
| 91.49 | shadowsocks | 199.1 | 4.0 | 23.17 | 14.85 | 10.0 | 12.79 | 15.18 | Au1rxx-base64 | 95.215.201.18 |
| 90.71 | shadowsocks | 258.0 | 1.6 | 21.8 | 14.94 | 10.0 | 12.79 | 15.18 | Au1rxx-base64 | 173.244.56.6 |
| 89.84 | shadowsocks | 257.5 | 0.4 | 21.82 | 14.98 | 10.0 | 12.79 | 15.18 | Au1rxx-base64 | 156.146.38.168 |
| 89.7 | shadowsocks | 263.5 | 6.4 | 21.68 | 14.76 | 10.0 | 12.79 | 15.18 | Au1rxx-base64 | 156.146.38.170 |
| 88.78 | shadowsocks | 213.6 | 0.6 | 22.83 | 14.98 | 10.0 | 12.79 | 15.18 | Au1rxx-base64 | 173.244.56.9 |
| 88.53 | shadowsocks | 308.3 | 0.3 | 20.64 | 14.99 | 10.0 | 12.79 | 15.18 | Au1rxx-base64 | 156.146.38.167 |
| 87.14 | vless | 201.3 | 3.0 | 23.12 | 14.89 | 3.9 | 10.05 | 15.18 | Au1rxx-base64 | 45.63.53.81 |
| 86.86 | hysteria2 | 320.7 | 3.7 | 20.35 | 14.86 | 10.0 | 10.26 | 15.18 | Au1rxx-base64 | 129.213.91.185 |
| 86.75 | trojan | 225.2 | 1.4 | 22.57 | 14.95 | 9.33 | 7.22 | 15.18 | Au1rxx-base64 | 167.88.61.198 |
| 85.58 | vless | 208.7 | 0.4 | 22.95 | 14.98 | 0.0 | 10.05 | 17.6 | mheidari-all | 43.153.121.144 |
| 85.24 | vless | 209.2 | 9.3 | 22.94 | 14.65 | 0.0 | 10.05 | 17.6 | mheidari-all | 154.29.159.211 |
| 84.28 | vless | 261.6 | 2.3 | 21.72 | 14.91 | 0.0 | 10.05 | 17.6 | mheidari-all | 107.173.237.146 |
| 84.28 | trojan | 292.6 | 5.7 | 21.0 | 14.79 | 10.0 | 7.22 | 15.18 | Au1rxx-base64 | 66.163.114.45 |
| 83.86 | shadowsocks | 254.1 | 1.3 | 21.9 | 14.95 | 3.54 | 12.79 | 15.18 | Au1rxx-base64 | 156.146.38.169 |
| 83.64 | shadowsocks | 345.8 | 0.9 | 19.77 | 14.97 | 10.0 | 12.79 | 15.18 | Au1rxx-base64 | 37.19.198.244 |
| 83.64 | shadowsocks | 354.3 | 1.1 | 19.58 | 14.96 | 10.0 | 12.79 | 15.18 | Au1rxx-base64 | 193.151.160.9 |
| 83.39 | trojan | 298.7 | 7.4 | 20.86 | 14.72 | 9.2 | 7.22 | 15.18 | Au1rxx-base64 | 66.163.114.132 |
| 83.38 | shadowsocks | 359.5 | 3.6 | 19.46 | 14.87 | 10.0 | 12.79 | 15.18 | Au1rxx-base64 | 45.86.51.18 |
| 83.21 | shadowsocks | 372.9 | 1.0 | 19.15 | 14.96 | 10.0 | 12.79 | 15.18 | Au1rxx-base64 | 37.19.198.160 |
| 83.01 | hysteria2 | 253.4 | 6.0 | 21.91 | 14.77 | 1.96 | 10.26 | 15.18 | Au1rxx-base64 | 66.94.121.46 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.952 | 0.886 | 167 | 1751 | prefer |
| zhangkai | 0.923 | 1.0 | 19 | 43 | prefer |
| Surfboard-tg-mixed | 0.904 | 0.833 | 66 | 8651 | prefer |
| mheidari-all | 0.617 | 0.537 | 378 | 14725 | observe |
| ALL | 0.41 | 0.326 | 95 | 115838 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5005 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2526 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10844 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6015 | observe |
| barry-far-vless | 0.255 | None | 0 | 6228 | observe |
| github_links | 0.255 | None | 0 | 35748 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4612 | observe |
| xiaoji235-airport-v2ray-all | 0.249 | 0.2 | 10 | 6752 | downweight |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 148 |
| 204 | ProxyError | - | 40 |
| speed | ClientOSError | - | 30 |
| geo | ClientOSError | - | 16 |
| 204 | TimeoutError | - | 11 |
| 204 | ClientOSError | - | 6 |
| cn-block | ClientOSError | - | 6 |
| cn-block | TimeoutError | - | 6 |
| speed | TimeoutError | - | 5 |
| cn-block | ProxyError | - | 4 |
| geo | TimeoutError | - | 4 |
| geo | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 40 | 91 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
