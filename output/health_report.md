# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-30 13:09:22 |
| 运行耗时 | 316.3s |
| 订阅源总数 | 111 |
| 健康订阅源 | 87 |
| 原始节点 | 100337 |
| 去重后节点 | 27803 |
| TCP 可达 | 3000 |
| 真实可用 | 439 |
| Verified 输出 | 96 |
| Global 输出 | 300 |
| All 输出 | 27803 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 14.6 |
| geo | 1.3 |
| tcp | 87.8 |
| probe | 96.3 |
| real_test | 79.3 |
| china_check | 21.6 |
| write_verified | 0.1 |
| generate | 15.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 62090 |
| vmess | 14684 |
| shadowsocks | 10865 |
| trojan | 10120 |
| hysteria2 | 2209 |
| shadowsocksr | 166 |
| http | 114 |
| socks | 48 |
| tuic | 17 |
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
| 96.26 | trojan | 184.9 | 1.6 | 23.5 | 14.94 | 10.0 | 12.88 | 18.44 | Au1rxx-base64 | 167.88.61.20 |
| 96.22 | trojan | 182.2 | 4.3 | 23.56 | 14.84 | 10.0 | 12.88 | 18.44 | Au1rxx-base64 | 167.88.61.193 |
| 93.53 | trojan | 286.2 | 2.6 | 21.15 | 14.9 | 10.0 | 12.88 | 18.44 | Au1rxx-base64 | 66.163.114.45 |
| 93.51 | shadowsocks | 236.4 | 0.6 | 22.3 | 14.98 | 10.0 | 13.29 | 18.44 | Au1rxx-base64 | 95.215.201.18 |
| 93.42 | trojan | 179.1 | 3.2 | 23.63 | 14.88 | 7.09 | 12.88 | 18.44 | Au1rxx-base64 | 167.88.61.85 |
| 93.25 | trojan | 239.8 | 0.1 | 22.23 | 15.0 | 8.48 | 12.88 | 18.44 | Au1rxx-base64 | 66.163.112.13 |
| 93.0 | trojan | 300.6 | 4.2 | 20.82 | 14.84 | 9.9 | 12.88 | 18.44 | Au1rxx-base64 | 66.163.112.242 |
| 92.91 | trojan | 292.7 | 2.4 | 21.0 | 14.91 | 10.0 | 12.88 | 18.44 | Au1rxx-base64 | 66.163.112.121 |
| 92.89 | trojan | 279.3 | 1.5 | 21.31 | 14.94 | 9.81 | 12.88 | 18.44 | Au1rxx-base64 | 66.163.114.132 |
| 92.7 | shadowsocks | 243.3 | 2.1 | 22.15 | 14.92 | 10.0 | 13.29 | 18.44 | Au1rxx-base64 | 149.22.95.183 |
| 92.35 | trojan | 269.2 | 2.1 | 21.55 | 14.92 | 8.39 | 12.88 | 18.44 | Au1rxx-base64 | 66.163.114.114 |
| 92.2 | trojan | 262.6 | 1.9 | 21.7 | 14.93 | 8.34 | 12.88 | 18.44 | Au1rxx-base64 | 66.163.114.126 |
| 92.09 | trojan | 270.4 | 1.7 | 21.52 | 14.94 | 8.39 | 12.88 | 18.44 | Au1rxx-base64 | 66.163.114.106 |
| 92.06 | trojan | 251.8 | 4.1 | 21.95 | 14.85 | 8.46 | 12.88 | 18.44 | Au1rxx-base64 | 66.163.112.76 |
| 91.93 | trojan | 244.5 | 0.2 | 22.12 | 14.99 | 7.0 | 12.88 | 18.44 | Au1rxx-base64 | 66.163.112.142 |
| 91.27 | vless | 217.2 | 1.9 | 22.75 | 14.93 | 8.65 | 7.5 | 18.44 | Au1rxx-base64 | 195.123.240.65 |
| 91.21 | trojan | 271.8 | 1.0 | 21.49 | 14.96 | 8.39 | 12.88 | 18.44 | Au1rxx-base64 | 66.163.114.166 |
| 90.79 | trojan | 272.0 | 7.1 | 21.48 | 14.73 | 8.45 | 12.88 | 18.44 | Au1rxx-base64 | 66.163.114.245 |
| 90.31 | trojan | 439.8 | 2.9 | 17.6 | 14.89 | 10.0 | 12.88 | 18.44 | Au1rxx-base64 | 167.88.61.175 |
| 90.28 | trojan | 181.4 | 2.6 | 23.58 | 14.9 | 10.0 | 12.88 | 18.44 | Au1rxx-base64 | 167.88.61.198 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.955 | 0.964 | 28 | 550 | prefer |
| Au1rxx-base64 | 0.878 | 0.81 | 336 | 1751 | prefer |
| Surfboard-tg-mixed | 0.722 | 0.644 | 135 | 7902 | prefer |
| mheidari-all | 0.65 | 0.571 | 91 | 34171 | observe |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4960 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10521 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5822 | observe |
| barry-far-vless | 0.255 | None | 0 | 5942 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4445 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 85 |
| geo | ClientOSError | - | 25 |
| 204 | ProxyError | - | 7 |
| 204 | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 5 |
| cn-block | TimeoutError | - | 4 |
| speed | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 4 |
| geo | ProxyError | - | 3 |
| speed | ProxyError | - | 2 |
| geo | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 107 | 96 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
