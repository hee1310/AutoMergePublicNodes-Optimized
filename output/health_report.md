# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-30 22:32:11 |
| 运行耗时 | 329.5s |
| 订阅源总数 | 111 |
| 健康订阅源 | 87 |
| 原始节点 | 80873 |
| 去重后节点 | 26300 |
| TCP 可达 | 3000 |
| 真实可用 | 523 |
| Verified 输出 | 52 |
| Global 输出 | 300 |
| All 输出 | 26300 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 14.2 |
| geo | 1.3 |
| tcp | 74.8 |
| probe | 95.9 |
| real_test | 89.9 |
| china_check | 38.8 |
| write_verified | 0.0 |
| generate | 14.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49038 |
| vmess | 14042 |
| shadowsocks | 8571 |
| trojan | 7374 |
| hysteria2 | 1494 |
| shadowsocksr | 154 |
| http | 111 |
| socks | 51 |
| tuic | 14 |
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
| 96.12 | trojan | 176.0 | 2.5 | 23.7 | 14.91 | 10.0 | 12.45 | 17.56 | Au1rxx-base64 | 167.88.61.193 |
| 96.04 | trojan | 180.7 | 1.8 | 23.6 | 14.93 | 10.0 | 12.45 | 17.56 | Au1rxx-base64 | 167.88.61.20 |
| 95.92 | trojan | 186.2 | 1.6 | 23.47 | 14.94 | 10.0 | 12.45 | 17.56 | Au1rxx-base64 | 167.88.61.198 |
| 95.5 | trojan | 192.7 | 8.8 | 23.32 | 14.67 | 10.0 | 12.45 | 17.56 | Au1rxx-base64 | 167.88.61.175 |
| 94.3 | vless | 193.1 | 1.7 | 23.31 | 14.94 | 10.0 | 8.49 | 17.56 | Au1rxx-base64 | 144.202.126.147 |
| 93.74 | trojan | 249.7 | 5.3 | 22.0 | 14.8 | 10.0 | 12.45 | 17.56 | Au1rxx-base64 | 66.163.112.121 |
| 93.1 | trojan | 246.4 | 4.5 | 22.07 | 14.83 | 9.84 | 12.45 | 17.56 | Au1rxx-base64 | 66.163.112.242 |
| 92.37 | trojan | 244.0 | 1.7 | 22.13 | 14.94 | 8.23 | 12.45 | 17.56 | Au1rxx-base64 | 66.163.112.13 |
| 92.13 | trojan | 271.9 | 6.2 | 21.48 | 14.77 | 10.0 | 12.45 | 17.56 | Au1rxx-base64 | 66.163.114.45 |
| 91.84 | trojan | 243.2 | 0.8 | 22.15 | 14.97 | 8.23 | 12.45 | 17.56 | Au1rxx-base64 | 66.163.112.76 |
| 91.78 | vless | 256.7 | 2.8 | 21.83 | 14.89 | 9.85 | 8.49 | 17.56 | Au1rxx-base64 | 185.168.208.190 |
| 91.78 | trojan | 271.4 | 4.2 | 21.5 | 14.84 | 9.75 | 12.45 | 17.56 | Au1rxx-base64 | 66.163.114.132 |
| 91.65 | trojan | 240.8 | 1.3 | 22.2 | 14.95 | 7.01 | 12.45 | 17.56 | Au1rxx-base64 | 66.163.112.31 |
| 91.38 | shadowsocks | 303.1 | 6.4 | 20.76 | 14.76 | 10.0 | 13.19 | 17.56 | Au1rxx-base64 | 149.22.95.183 |
| 91.16 | shadowsocks | 283.1 | 8.3 | 21.22 | 14.69 | 10.0 | 13.19 | 17.56 | Au1rxx-base64 | 95.215.201.18 |
| 90.93 | vless | 204.3 | 4.4 | 23.05 | 14.83 | 10.0 | 8.49 | 17.56 | Au1rxx-base64 | 45.32.69.110 |
| 90.81 | trojan | 289.2 | 0.9 | 21.08 | 14.97 | 8.14 | 12.45 | 17.56 | Au1rxx-base64 | 66.163.114.166 |
| 90.59 | trojan | 242.7 | 1.5 | 22.16 | 14.94 | 5.98 | 12.45 | 17.56 | Au1rxx-base64 | 216.106.186.32 |
| 90.43 | trojan | 245.3 | 5.0 | 22.1 | 14.81 | 7.02 | 12.45 | 17.56 | Au1rxx-base64 | 66.163.112.142 |
| 90.03 | vless | 215.5 | 2.6 | 22.79 | 14.9 | 8.29 | 8.49 | 17.56 | Au1rxx-base64 | 47.251.108.158 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.99 | 1.0 | 29 | 550 | prefer |
| Au1rxx-base64 | 0.927 | 0.859 | 348 | 1751 | prefer |
| Surfboard-tg-mixed | 0.842 | 0.765 | 170 | 7917 | prefer |
| mheidari-all | 0.678 | 0.6 | 105 | 14611 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| ermaozi-get_subscribe | 0.328 | 1.0 | 2 | 430 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4960 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2724 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10557 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5777 | observe |
| barry-far-vless | 0.255 | None | 0 | 6013 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4459 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 44 |
| geo | ClientOSError | - | 43 |
| cn-block | ClientOSError | - | 11 |
| 204 | ProxyError | - | 9 |
| 204 | TimeoutError | - | 8 |
| 204 | ClientOSError | - | 5 |
| cn-block | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 3 |
| speed | ClientOSError | - | 1 |
| speed | TimeoutError | - | 1 |
| geo | ProxyError | - | 1 |
| geo | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 96 | 52 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
