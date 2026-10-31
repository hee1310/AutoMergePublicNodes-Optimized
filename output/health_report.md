# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-31 12:46:34 |
| 运行耗时 | 272.1s |
| 订阅源总数 | 111 |
| 健康订阅源 | 88 |
| 原始节点 | 80704 |
| 去重后节点 | 26392 |
| TCP 可达 | 3000 |
| 真实可用 | 373 |
| Verified 输出 | 77 |
| Global 输出 | 300 |
| All 输出 | 26392 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 11.0 |
| geo | 1.2 |
| tcp | 76.3 |
| probe | 70.5 |
| real_test | 79.1 |
| china_check | 25.2 |
| write_verified | 0.0 |
| generate | 8.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48278 |
| vmess | 13596 |
| shadowsocks | 8542 |
| trojan | 8423 |
| hysteria2 | 1456 |
| shadowsocksr | 163 |
| http | 161 |
| socks | 49 |
| tuic | 14 |
| hysteria | 11 |
| anytls | 11 |

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
| 97.2 | trojan | 261.9 | 0.0 | 21.72 | 15.0 | 10.0 | 14.18 | 19.04 | Au1rxx-base64 | 66.163.114.45 |
| 96.99 | hysteria2 | 280.9 | 1.8 | 21.28 | 14.93 | 10.0 | 13.24 | 19.04 | Au1rxx-base64 | 129.213.91.185 |
| 96.64 | trojan | 293.9 | 1.4 | 20.97 | 14.95 | 10.0 | 14.18 | 19.04 | Au1rxx-base64 | 216.238.80.100 |
| 96.47 | shadowsocks | 227.8 | 0.1 | 22.5 | 15.0 | 10.0 | 13.93 | 19.04 | Au1rxx-base64 | 156.146.38.168 |
| 96.41 | shadowsocks | 227.1 | 2.2 | 22.52 | 14.92 | 10.0 | 13.93 | 19.04 | Au1rxx-base64 | 156.146.38.170 |
| 95.04 | trojan | 263.4 | 0.3 | 21.68 | 14.99 | 8.2 | 14.18 | 19.04 | Au1rxx-base64 | 66.163.114.132 |
| 94.79 | shadowsocks | 257.0 | 0.2 | 21.83 | 14.99 | 10.0 | 13.93 | 19.04 | Au1rxx-base64 | 156.146.38.167 |
| 94.77 | trojan | 253.9 | 0.8 | 21.9 | 14.97 | 7.29 | 14.18 | 19.04 | Au1rxx-base64 | 66.163.114.166 |
| 94.7 | trojan | 262.7 | 0.2 | 21.7 | 14.99 | 7.29 | 14.18 | 19.04 | Au1rxx-base64 | 66.163.114.114 |
| 94.59 | trojan | 268.7 | 3.7 | 21.56 | 14.86 | 9.85 | 14.18 | 19.04 | Au1rxx-base64 | 66.163.112.121 |
| 94.49 | trojan | 367.3 | 0.1 | 19.28 | 14.99 | 10.0 | 14.18 | 19.04 | Au1rxx-base64 | 66.23.203.21 |
| 94.36 | trojan | 257.0 | 0.0 | 21.83 | 15.0 | 7.21 | 14.18 | 19.04 | Au1rxx-base64 | 66.163.114.106 |
| 93.77 | trojan | 262.4 | 0.3 | 21.7 | 14.99 | 7.52 | 14.18 | 19.04 | Au1rxx-base64 | 66.163.114.245 |
| 93.67 | shadowsocks | 252.5 | 1.2 | 21.93 | 14.95 | 10.0 | 13.93 | 19.04 | Au1rxx-base64 | 173.244.56.6 |
| 93.58 | vless | 241.8 | 0.8 | 22.18 | 14.97 | 10.0 | 10.0 | 19.04 | Au1rxx-base64 | 45.32.69.110 |
| 93.33 | vless | 257.8 | 1.4 | 21.81 | 14.95 | 9.23 | 10.0 | 19.04 | Au1rxx-base64 | 144.202.126.147 |
| 93.12 | trojan | 269.1 | 1.0 | 21.55 | 14.96 | 8.17 | 14.18 | 19.04 | Au1rxx-base64 | 66.163.112.242 |
| 92.9 | trojan | 268.1 | 0.0 | 21.57 | 15.0 | 7.27 | 14.18 | 19.04 | Au1rxx-base64 | 66.163.112.13 |
| 92.54 | shadowsocks | 294.0 | 0.0 | 20.97 | 15.0 | 10.0 | 13.93 | 19.04 | Au1rxx-base64 | 95.215.201.18 |
| 92.5 | trojan | 260.4 | 0.1 | 21.75 | 15.0 | 7.21 | 14.18 | 19.04 | Au1rxx-base64 | 66.163.112.76 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.923 | 1.0 | 19 | 43 | prefer |
| Au1rxx-base64 | 0.851 | 0.783 | 304 | 1751 | prefer |
| DeltaKronecker-all | 0.725 | 0.684 | 19 | 2848 | prefer |
| mheidari-all | 0.638 | 0.558 | 163 | 14723 | observe |
| Surfboard-tg-mixed | 0.515 | 0.5 | 16 | 7861 | observe |
| ermaozi | 0.314 | 1.0 | 2 | 79 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 6752 | observe |
| ermaozi-get_subscribe | 0.271 | 1.0 | 1 | 412 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4970 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10576 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5698 | observe |
| barry-far-vless | 0.255 | None | 0 | 5912 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4635 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 78 |
| geo | ClientOSError | - | 20 |
| 204 | TimeoutError | - | 14 |
| cn-block | TimeoutError | - | 11 |
| 204 | ProxyError | - | 10 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| speed | ProxyError | - | 3 |
| geo | TimeoutError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| speed | TimeoutError | - | 2 |
| speed | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 95 | 77 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
