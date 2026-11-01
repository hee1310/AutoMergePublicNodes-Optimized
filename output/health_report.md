# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-01 22:12:29 |
| 运行耗时 | 270.6s |
| 订阅源总数 | 111 |
| 健康订阅源 | 88 |
| 原始节点 | 82970 |
| 去重后节点 | 26794 |
| TCP 可达 | 3000 |
| 真实可用 | 462 |
| Verified 输出 | 72 |
| Global 输出 | 300 |
| All 输出 | 26794 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 10.0 |
| geo | 1.3 |
| tcp | 76.8 |
| probe | 72.3 |
| real_test | 77.0 |
| china_check | 24.0 |
| write_verified | 0.3 |
| generate | 9.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49352 |
| vmess | 13914 |
| trojan | 9094 |
| shadowsocks | 8624 |
| hysteria2 | 1508 |
| http | 207 |
| shadowsocksr | 156 |
| socks | 76 |
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
| 93.19 | shadowsocks | 235.2 | 1.4 | 22.33 | 14.95 | 10.0 | 12.99 | 16.92 | Au1rxx-base64 | 156.146.38.168 |
| 92.86 | shadowsocks | 246.5 | 3.2 | 22.07 | 14.88 | 10.0 | 12.99 | 16.92 | Au1rxx-base64 | 156.146.38.170 |
| 91.33 | trojan | 262.8 | 4.4 | 21.69 | 14.84 | 10.0 | 10.66 | 16.92 | Au1rxx-base64 | 66.163.114.45 |
| 91.25 | trojan | 263.3 | 3.6 | 21.68 | 14.87 | 9.85 | 10.66 | 16.92 | Au1rxx-base64 | 66.163.114.132 |
| 90.5 | shadowsocks | 313.5 | 4.1 | 20.52 | 14.85 | 10.0 | 12.99 | 16.92 | Au1rxx-base64 | 37.19.198.160 |
| 90.44 | trojan | 255.9 | 7.2 | 21.85 | 14.73 | 8.78 | 10.66 | 16.92 | Au1rxx-base64 | 216.152.155.59 |
| 90.29 | trojan | 262.6 | 4.2 | 21.7 | 14.84 | 8.67 | 10.66 | 16.92 | Au1rxx-base64 | 66.163.114.114 |
| 90.2 | trojan | 257.2 | 1.7 | 21.82 | 14.94 | 8.71 | 10.66 | 16.92 | Au1rxx-base64 | 66.163.114.166 |
| 89.98 | shadowsocks | 256.4 | 4.6 | 21.84 | 14.83 | 7.4 | 12.99 | 16.92 | Au1rxx-base64 | 156.146.38.169 |
| 89.94 | shadowsocks | 317.4 | 14.3 | 20.43 | 14.46 | 10.0 | 12.99 | 16.92 | Au1rxx-base64 | 37.19.198.243 |
| 89.67 | shadowsocks | 326.9 | 1.5 | 20.21 | 14.94 | 10.0 | 12.99 | 16.92 | Au1rxx-base64 | 37.19.198.244 |
| 89.64 | shadowsocks | 315.4 | 0.5 | 20.48 | 14.98 | 10.0 | 12.99 | 16.92 | Au1rxx-base64 | 185.230.230.18 |
| 89.0 | shadowsocks | 300.1 | 4.7 | 20.83 | 14.82 | 10.0 | 12.99 | 16.92 | Au1rxx-base64 | 37.19.198.236 |
| 88.6 | trojan | 270.3 | 0.6 | 21.52 | 14.98 | 7.02 | 10.66 | 16.92 | Au1rxx-base64 | 216.152.155.54 |
| 88.53 | trojan | 273.3 | 1.2 | 21.45 | 14.95 | 8.74 | 10.66 | 16.92 | Au1rxx-base64 | 66.163.114.245 |
| 88.09 | shadowsocks | 282.5 | 1.2 | 21.24 | 14.95 | 10.0 | 12.99 | 16.92 | Au1rxx-base64 | 95.215.201.18 |
| 88.06 | shadowsocks | 291.1 | 0.8 | 21.04 | 14.97 | 10.0 | 12.99 | 16.92 | Au1rxx-base64 | 173.244.56.6 |
| 88.04 | shadowsocks | 302.8 | 2.2 | 20.77 | 14.92 | 10.0 | 12.99 | 16.92 | Au1rxx-base64 | 45.86.51.18 |
| 87.6 | trojan | 297.3 | 0.8 | 20.9 | 14.97 | 8.69 | 10.66 | 16.92 | Au1rxx-base64 | 170.101.101.19 |
| 87.58 | shadowsocks | 303.6 | 1.4 | 20.75 | 14.95 | 10.0 | 12.99 | 16.92 | Au1rxx-base64 | 173.244.56.9 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.951 | 0.963 | 27 | 499 | prefer |
| mheidari-all | 0.937 | 0.875 | 40 | 15206 | prefer |
| zhangkai | 0.923 | 1.0 | 19 | 43 | prefer |
| Au1rxx-base64 | 0.913 | 0.845 | 322 | 1751 | prefer |
| Surfboard-tg-mixed | 0.768 | 0.691 | 152 | 8273 | prefer |
| DeltaKronecker-all | 0.48 | 1.0 | 4 | 3716 | observe |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4976 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10614 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5823 | observe |
| barry-far-vless | 0.255 | None | 0 | 5986 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4800 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 42 |
| geo | ClientOSError | - | 23 |
| 204 | ProxyError | - | 10 |
| cn-block | ClientOSError | - | 9 |
| cn-block | TimeoutError | - | 6 |
| cn-block | ProxyError | - | 4 |
| 204 | ClientOSError | - | 3 |
| 204 | TimeoutError | - | 2 |
| geo | ProxyError | - | 2 |
| geo | TimeoutError | - | 1 |
| 204 | ProxyConnectionError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 108 | 72 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
