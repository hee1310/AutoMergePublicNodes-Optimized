# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-01 13:38:12 |
| 运行耗时 | 316.8s |
| 订阅源总数 | 111 |
| 健康订阅源 | 89 |
| 原始节点 | 81865 |
| 去重后节点 | 26805 |
| TCP 可达 | 3000 |
| 真实可用 | 517 |
| Verified 输出 | 108 |
| Global 输出 | 300 |
| All 输出 | 26805 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 11.8 |
| geo | 1.2 |
| tcp | 79.6 |
| probe | 77.6 |
| real_test | 107.6 |
| china_check | 27.9 |
| write_verified | 0.0 |
| generate | 11.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48404 |
| vmess | 13845 |
| trojan | 9119 |
| shadowsocks | 8593 |
| hysteria2 | 1492 |
| shadowsocksr | 145 |
| http | 145 |
| socks | 83 |
| anytls | 16 |
| tuic | 12 |
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
| 94.21 | trojan | 277.4 | 1.8 | 21.36 | 14.93 | 10.0 | 13.4 | 17.84 | Au1rxx-base64 | 66.163.114.45 |
| 94.19 | shadowsocks | 243.4 | 0.1 | 22.14 | 15.0 | 10.0 | 13.21 | 17.84 | Au1rxx-base64 | 156.146.38.168 |
| 94.08 | hysteria2 | 275.8 | 2.1 | 21.39 | 14.92 | 10.0 | 11.43 | 17.84 | Au1rxx-base64 | 129.213.91.185 |
| 93.99 | shadowsocks | 251.7 | 0.3 | 21.95 | 14.99 | 10.0 | 13.21 | 17.84 | Au1rxx-base64 | 156.146.38.167 |
| 93.34 | trojan | 280.5 | 3.8 | 21.29 | 14.86 | 8.45 | 13.4 | 17.84 | Au1rxx-base64 | 66.163.114.132 |
| 92.99 | trojan | 258.9 | 0.8 | 21.78 | 14.97 | 7.5 | 13.4 | 17.84 | Au1rxx-base64 | 66.163.114.245 |
| 92.8 | trojan | 327.9 | 1.3 | 20.19 | 14.95 | 10.0 | 13.4 | 17.84 | Au1rxx-base64 | 66.23.203.21 |
| 92.74 | trojan | 264.3 | 0.3 | 21.66 | 14.99 | 7.35 | 13.4 | 17.84 | Au1rxx-base64 | 66.163.114.114 |
| 92.58 | trojan | 266.9 | 3.1 | 21.6 | 14.88 | 7.36 | 13.4 | 17.84 | Au1rxx-base64 | 66.163.114.166 |
| 92.43 | trojan | 270.3 | 0.7 | 21.52 | 14.97 | 7.22 | 13.4 | 17.84 | Au1rxx-base64 | 66.163.114.126 |
| 92.13 | trojan | 259.9 | 0.6 | 21.76 | 14.98 | 7.33 | 13.4 | 17.84 | Au1rxx-base64 | 66.163.114.106 |
| 92.0 | shadowsocks | 305.1 | 2.8 | 20.72 | 14.89 | 10.0 | 13.21 | 17.84 | Au1rxx-base64 | 37.19.198.244 |
| 91.16 | shadowsocks | 332.3 | 0.4 | 20.09 | 14.98 | 10.0 | 13.21 | 17.84 | Au1rxx-base64 | 37.19.198.160 |
| 90.45 | shadowsocks | 299.0 | 3.4 | 20.86 | 14.87 | 10.0 | 13.21 | 17.84 | Au1rxx-base64 | 185.230.230.18 |
| 90.33 | shadowsocks | 308.3 | 4.0 | 20.64 | 14.85 | 9.92 | 13.21 | 17.84 | Au1rxx-base64 | 45.86.51.18 |
| 89.88 | shadowsocks | 318.7 | 8.7 | 20.4 | 14.67 | 10.0 | 13.21 | 17.84 | Au1rxx-base64 | 193.151.163.18 |
| 89.34 | shadowsocks | 279.9 | 0.1 | 21.3 | 15.0 | 10.0 | 13.21 | 17.84 | Au1rxx-base64 | 173.244.56.9 |
| 88.89 | shadowsocks | 291.5 | 1.3 | 21.03 | 14.95 | 10.0 | 13.21 | 17.84 | Au1rxx-base64 | 95.215.201.18 |
| 88.89 | shadowsocks | 304.1 | 2.4 | 20.74 | 14.91 | 10.0 | 13.21 | 17.84 | Au1rxx-base64 | 37.19.198.243 |
| 88.84 | trojan | 301.6 | 1.0 | 20.8 | 14.96 | 8.2 | 13.4 | 17.84 | Au1rxx-base64 | 66.163.112.242 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.985 | 0.982 | 55 | 499 | prefer |
| zhangkai | 0.877 | 0.947 | 19 | 43 | prefer |
| DeltaKronecker-all | 0.868 | 0.806 | 31 | 3716 | prefer |
| Au1rxx-base64 | 0.846 | 0.778 | 311 | 1751 | prefer |
| Surfboard-tg-mixed | 0.784 | 0.708 | 96 | 8063 | prefer |
| mheidari-all | 0.553 | 0.473 | 224 | 14747 | observe |
| xiaoji235-airport-v2ray-all | 0.32 | 0.5 | 4 | 6752 | observe |
| ermaozi | 0.314 | 1.0 | 2 | 79 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4976 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10600 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5660 | observe |
| barry-far-vless | 0.255 | None | 0 | 5850 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4680 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 121 |
| geo | ClientOSError | - | 44 |
| 204 | ProxyError | - | 15 |
| cn-block | TimeoutError | - | 10 |
| 204 | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 5 |
| geo | ProxyError | - | 4 |
| 204 | ClientOSError | - | 3 |
| geo | TimeoutError | - | 2 |
| speed | ProxyError | - | 2 |
| speed | TimeoutError | - | 2 |
| speed | ClientOSError | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 72 | 108 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
