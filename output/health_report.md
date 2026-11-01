# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-01 06:22:38 |
| 运行耗时 | 339.7s |
| 订阅源总数 | 111 |
| 健康订阅源 | 88 |
| 原始节点 | 80510 |
| 去重后节点 | 26376 |
| TCP 可达 | 3000 |
| 真实可用 | 614 |
| Verified 输出 | 72 |
| Global 输出 | 300 |
| All 输出 | 26376 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 14.1 |
| geo | 1.3 |
| tcp | 74.3 |
| probe | 99.0 |
| real_test | 101.2 |
| china_check | 35.1 |
| write_verified | 0.1 |
| generate | 14.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47637 |
| vmess | 13734 |
| trojan | 8725 |
| shadowsocks | 8441 |
| hysteria2 | 1499 |
| http | 231 |
| shadowsocksr | 154 |
| socks | 50 |
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
| 98.36 | trojan | 179.6 | 1.6 | 23.62 | 14.94 | 10.0 | 13.8 | 18.5 | Au1rxx-base64 | 167.88.61.175 |
| 98.35 | trojan | 179.2 | 2.2 | 23.63 | 14.92 | 10.0 | 13.8 | 18.5 | Au1rxx-base64 | 167.88.61.193 |
| 97.25 | trojan | 188.4 | 25.7 | 23.42 | 14.03 | 10.0 | 13.8 | 18.5 | Au1rxx-base64 | 167.88.61.198 |
| 96.69 | trojan | 254.3 | 0.0 | 21.89 | 15.0 | 10.0 | 13.8 | 18.5 | Au1rxx-base64 | 66.163.112.242 |
| 96.0 | trojan | 262.4 | 0.1 | 21.7 | 15.0 | 10.0 | 13.8 | 18.5 | Au1rxx-base64 | 66.163.112.121 |
| 95.95 | trojan | 238.4 | 0.1 | 22.26 | 15.0 | 8.89 | 13.8 | 18.5 | Au1rxx-base64 | 66.163.112.13 |
| 95.94 | trojan | 237.4 | 0.6 | 22.28 | 14.98 | 8.88 | 13.8 | 18.5 | Au1rxx-base64 | 66.163.112.76 |
| 95.75 | trojan | 263.3 | 1.9 | 21.68 | 14.93 | 10.0 | 13.8 | 18.5 | Au1rxx-base64 | 66.163.114.132 |
| 95.59 | trojan | 277.2 | 0.1 | 21.36 | 15.0 | 10.0 | 13.8 | 18.5 | Au1rxx-base64 | 66.163.114.45 |
| 95.5 | shadowsocks | 235.7 | 2.1 | 22.32 | 14.92 | 10.0 | 13.76 | 18.5 | Au1rxx-base64 | 173.244.56.9 |
| 95.32 | vless | 190.2 | 1.4 | 23.37 | 14.95 | 10.0 | 8.5 | 18.5 | Au1rxx-base64 | 45.32.69.110 |
| 95.23 | trojan | 265.5 | 2.0 | 21.63 | 14.92 | 9.36 | 13.8 | 18.5 | Au1rxx-base64 | 66.163.114.245 |
| 95.07 | vless | 200.1 | 2.3 | 23.15 | 14.92 | 10.0 | 8.5 | 18.5 | Au1rxx-base64 | 144.202.126.147 |
| 94.98 | shadowsocks | 249.5 | 0.8 | 22.0 | 14.97 | 10.0 | 13.76 | 18.5 | Au1rxx-base64 | 149.22.95.183 |
| 94.97 | shadowsocks | 229.9 | 6.8 | 22.46 | 14.75 | 10.0 | 13.76 | 18.5 | Au1rxx-base64 | 95.215.201.18 |
| 94.87 | trojan | 261.1 | 1.0 | 21.73 | 14.96 | 8.8 | 13.8 | 18.5 | Au1rxx-base64 | 66.163.114.166 |
| 94.47 | trojan | 262.0 | 3.2 | 21.71 | 14.88 | 8.79 | 13.8 | 18.5 | Au1rxx-base64 | 66.163.114.106 |
| 94.37 | vless | 213.7 | 12.2 | 22.83 | 14.54 | 10.0 | 8.5 | 18.5 | Au1rxx-base64 | 195.123.240.65 |
| 94.09 | trojan | 259.4 | 0.3 | 21.77 | 14.99 | 8.8 | 13.8 | 18.5 | Au1rxx-base64 | 66.163.114.114 |
| 94.07 | trojan | 267.3 | 0.1 | 21.59 | 15.0 | 8.25 | 13.8 | 18.5 | Au1rxx-base64 | 66.163.114.126 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.971 | 0.973 | 37 | 558 | prefer |
| Au1rxx-base64 | 0.892 | 0.824 | 341 | 1751 | prefer |
| zhangkai | 0.877 | 0.947 | 19 | 43 | prefer |
| mheidari-all | 0.831 | 0.753 | 215 | 14747 | prefer |
| Surfboard-tg-mixed | 0.695 | 0.616 | 185 | 7809 | observe |
| DeltaKronecker-all | 0.335 | 1.0 | 1 | 2848 | observe |
| xiaoji235-airport-v2ray-all | 0.32 | 0.5 | 4 | 6752 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 178 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4970 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10495 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5637 | observe |
| barry-far-vless | 0.255 | None | 0 | 5805 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 90 |
| geo | ClientOSError | - | 40 |
| 204 | ProxyError | - | 19 |
| cn-block | ClientOSError | - | 10 |
| 204 | TimeoutError | - | 5 |
| cn-block | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 4 |
| speed | ClientOSError | - | 4 |
| geo | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 3 |
| speed | TimeoutError | - | 3 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 106 | 72 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
