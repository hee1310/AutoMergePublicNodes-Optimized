# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-31 05:57:22 |
| 运行耗时 | 295.0s |
| 订阅源总数 | 111 |
| 健康订阅源 | 88 |
| 原始节点 | 80805 |
| 去重后节点 | 26598 |
| TCP 可达 | 3000 |
| 真实可用 | 617 |
| Verified 输出 | 95 |
| Global 输出 | 300 |
| All 输出 | 26598 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 10.9 |
| geo | 1.3 |
| tcp | 80.0 |
| probe | 69.8 |
| real_test | 93.6 |
| china_check | 30.5 |
| write_verified | 0.0 |
| generate | 8.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48677 |
| vmess | 13897 |
| shadowsocks | 8530 |
| trojan | 7642 |
| hysteria2 | 1471 |
| http | 337 |
| shadowsocksr | 159 |
| socks | 54 |
| tuic | 15 |
| hysteria | 12 |
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
| 97.04 | trojan | 261.2 | 0.1 | 21.73 | 15.0 | 10.0 | 14.27 | 18.54 | Au1rxx-base64 | 66.163.114.45 |
| 96.56 | hysteria2 | 269.7 | 0.5 | 21.54 | 14.98 | 10.0 | 13.0 | 18.54 | Au1rxx-base64 | 129.213.91.185 |
| 95.77 | shadowsocks | 215.4 | 2.1 | 22.79 | 14.92 | 10.0 | 13.52 | 18.54 | Au1rxx-base64 | 156.146.38.170 |
| 95.68 | trojan | 255.7 | 0.2 | 21.86 | 14.99 | 8.92 | 14.27 | 18.54 | Au1rxx-base64 | 66.163.114.132 |
| 95.67 | shadowsocks | 222.6 | 0.5 | 22.63 | 14.98 | 10.0 | 13.52 | 18.54 | Au1rxx-base64 | 156.146.38.168 |
| 94.32 | trojan | 252.6 | 0.1 | 21.93 | 15.0 | 7.08 | 14.27 | 18.54 | Au1rxx-base64 | 66.163.114.106 |
| 94.06 | trojan | 256.9 | 1.7 | 21.83 | 14.94 | 7.08 | 14.27 | 18.54 | Au1rxx-base64 | 66.163.114.166 |
| 93.91 | trojan | 262.7 | 0.5 | 21.7 | 14.98 | 7.28 | 14.27 | 18.54 | Au1rxx-base64 | 66.163.114.245 |
| 93.88 | trojan | 262.4 | 0.9 | 21.7 | 14.97 | 6.9 | 14.27 | 18.54 | Au1rxx-base64 | 66.163.114.126 |
| 93.64 | trojan | 261.1 | 0.5 | 21.73 | 14.98 | 8.88 | 14.27 | 18.54 | Au1rxx-base64 | 66.163.112.242 |
| 93.58 | shadowsocks | 226.3 | 0.7 | 22.54 | 14.98 | 10.0 | 13.52 | 18.54 | Au1rxx-base64 | 156.146.38.167 |
| 93.37 | shadowsocks | 250.2 | 0.7 | 21.99 | 14.97 | 10.0 | 13.52 | 18.54 | Au1rxx-base64 | 173.244.56.6 |
| 93.25 | trojan | 256.1 | 0.6 | 21.85 | 14.98 | 7.1 | 14.27 | 18.54 | Au1rxx-base64 | 66.163.114.114 |
| 92.74 | shadowsocks | 250.2 | 0.9 | 21.99 | 14.97 | 10.0 | 13.52 | 18.54 | Au1rxx-base64 | 95.215.201.18 |
| 92.38 | trojan | 298.0 | 0.5 | 20.88 | 14.98 | 6.85 | 14.27 | 18.54 | Au1rxx-base64 | 216.152.156.65 |
| 92.27 | trojan | 442.1 | 2.1 | 17.54 | 14.92 | 10.0 | 14.27 | 18.54 | Au1rxx-base64 | 66.23.203.21 |
| 92.07 | trojan | 260.7 | 0.7 | 21.74 | 14.97 | 7.04 | 14.27 | 18.54 | Au1rxx-base64 | 66.163.112.13 |
| 91.94 | trojan | 264.4 | 0.7 | 21.66 | 14.97 | 7.03 | 14.27 | 18.54 | Au1rxx-base64 | 66.163.112.76 |
| 91.64 | vless | 292.9 | 0.4 | 21.0 | 14.98 | 10.0 | 9.12 | 18.54 | Au1rxx-base64 | 31.172.69.31 |
| 91.6 | shadowsocks | 301.1 | 0.7 | 20.81 | 14.97 | 10.0 | 13.52 | 18.54 | Au1rxx-base64 | 193.151.160.9 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 1.0 | 0.989 | 94 | 622 | prefer |
| Au1rxx-base64 | 0.952 | 0.884 | 354 | 1751 | prefer |
| mheidari-all | 0.903 | 0.829 | 111 | 14594 | prefer |
| Surfboard-tg-mixed | 0.772 | 0.694 | 170 | 7827 | prefer |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4960 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2724 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10524 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5680 | observe |
| barry-far-vless | 0.255 | None | 0 | 5895 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4635 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 59 |
| geo | ClientOSError | - | 32 |
| 204 | TimeoutError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| speed | ClientOSError | - | 4 |
| cn-block | TimeoutError | - | 3 |
| 204 | ClientOSError | - | 2 |
| speed | TimeoutError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 52 | 95 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
