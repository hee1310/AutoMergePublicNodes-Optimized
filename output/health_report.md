# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-31 21:46:27 |
| 运行耗时 | 309.5s |
| 订阅源总数 | 111 |
| 健康订阅源 | 88 |
| 原始节点 | 80847 |
| 去重后节点 | 26339 |
| TCP 可达 | 3000 |
| 真实可用 | 487 |
| Verified 输出 | 106 |
| Global 输出 | 300 |
| All 输出 | 26339 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 13.2 |
| geo | 1.3 |
| tcp | 75.1 |
| probe | 96.2 |
| real_test | 84.6 |
| china_check | 24.6 |
| write_verified | 0.1 |
| generate | 14.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47580 |
| vmess | 13807 |
| trojan | 8988 |
| shadowsocks | 8619 |
| hysteria2 | 1444 |
| http | 164 |
| shadowsocksr | 163 |
| socks | 48 |
| tuic | 12 |
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
| 93.37 | shadowsocks | 248.0 | 0.6 | 22.04 | 14.98 | 10.0 | 13.33 | 17.02 | Au1rxx-base64 | 156.146.38.170 |
| 93.33 | shadowsocks | 247.5 | 1.8 | 22.05 | 14.93 | 10.0 | 13.33 | 17.02 | Au1rxx-base64 | 156.146.38.168 |
| 92.99 | hysteria2 | 272.8 | 17.6 | 21.46 | 14.34 | 10.0 | 11.67 | 17.02 | Au1rxx-base64 | 129.213.91.185 |
| 92.16 | shadowsocks | 286.7 | 8.9 | 21.14 | 14.67 | 10.0 | 13.33 | 17.02 | Au1rxx-base64 | 156.146.38.167 |
| 91.52 | shadowsocks | 293.2 | 18.8 | 20.99 | 14.3 | 10.0 | 13.33 | 17.02 | Au1rxx-base64 | 37.19.198.244 |
| 91.29 | shadowsocks | 306.5 | 3.0 | 20.68 | 14.89 | 10.0 | 13.33 | 17.02 | Au1rxx-base64 | 185.230.230.18 |
| 90.59 | trojan | 265.8 | 16.5 | 21.63 | 14.38 | 10.0 | 11.2 | 17.02 | Au1rxx-base64 | 66.163.114.45 |
| 90.2 | shadowsocks | 241.6 | 5.7 | 22.18 | 14.79 | 6.88 | 13.33 | 17.02 | Au1rxx-base64 | 156.146.38.169 |
| 89.76 | trojan | 260.9 | 2.9 | 21.74 | 14.89 | 7.69 | 11.2 | 17.02 | Au1rxx-base64 | 66.163.114.106 |
| 89.68 | trojan | 268.6 | 1.3 | 21.56 | 14.95 | 7.7 | 11.2 | 17.02 | Au1rxx-base64 | 66.163.114.245 |
| 89.47 | trojan | 269.4 | 3.1 | 21.54 | 14.88 | 7.7 | 11.2 | 17.02 | Au1rxx-base64 | 66.163.114.114 |
| 89.24 | trojan | 268.3 | 2.5 | 21.57 | 14.91 | 7.68 | 11.2 | 17.02 | Au1rxx-base64 | 66.163.114.126 |
| 89.17 | trojan | 260.9 | 0.7 | 21.74 | 14.97 | 7.82 | 11.2 | 17.02 | Au1rxx-base64 | 216.152.155.59 |
| 88.55 | trojan | 274.7 | 0.2 | 21.42 | 14.99 | 7.92 | 11.2 | 17.02 | Au1rxx-base64 | 66.163.114.132 |
| 88.27 | shadowsocks | 299.4 | 14.7 | 20.85 | 14.45 | 10.0 | 13.33 | 17.02 | Au1rxx-base64 | 37.19.198.160 |
| 87.87 | shadowsocks | 318.8 | 3.1 | 20.4 | 14.88 | 10.0 | 13.33 | 17.02 | Au1rxx-base64 | 173.244.56.6 |
| 87.68 | shadowsocks | 327.4 | 2.1 | 20.2 | 14.92 | 10.0 | 13.33 | 17.02 | Au1rxx-base64 | 193.151.160.9 |
| 87.51 | trojan | 452.2 | 0.4 | 17.31 | 14.98 | 10.0 | 11.2 | 17.02 | Au1rxx-base64 | 66.23.203.21 |
| 87.48 | trojan | 268.4 | 4.3 | 21.57 | 14.84 | 5.35 | 11.2 | 17.02 | Au1rxx-base64 | 216.152.155.54 |
| 87.23 | trojan | 308.1 | 1.3 | 20.65 | 14.95 | 7.6 | 11.2 | 17.02 | Au1rxx-base64 | 216.152.156.65 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.925 | 0.857 | 322 | 1751 | prefer |
| zhangkai | 0.923 | 1.0 | 19 | 43 | prefer |
| Surfboard-tg-mixed | 0.919 | 0.85 | 60 | 7936 | prefer |
| mheidari-all | 0.743 | 0.665 | 203 | 14850 | prefer |
| DeltaKronecker-all | 0.4 | 0.75 | 4 | 2848 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| ermaozi-get_subscribe | 0.328 | 1.0 | 2 | 412 | observe |
| peasoft-NoMoreWalls | 0.264 | 1.0 | 1 | 227 | observe |
| tg-oneclickvpnkeys | 0.259 | 1.0 | 1 | 108 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4970 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10505 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5636 | observe |
| barry-far-vless | 0.255 | None | 0 | 5849 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 61 |
| geo | ClientOSError | - | 29 |
| 204 | ProxyError | - | 12 |
| cn-block | ClientOSError | - | 8 |
| 204 | TimeoutError | - | 5 |
| geo | TimeoutError | - | 2 |
| 204 | ClientOSError | - | 2 |
| cn-block | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |
| speed | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 77 | 106 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
