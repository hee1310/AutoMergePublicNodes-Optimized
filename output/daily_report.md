# AutoNodes 每日报告

生成时间：2026-10-30 22:32:37

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/111 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 3/90 |
| 原始节点数 | 80873 |
| 去重后节点数 | 26300 |
| TCP 可达数 | 3000 |
| 真测通过数 | 523 |
| verified 输出数 | 52 |
| global 输出数 | 300 |
| all 输出数 | 26300 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 38.8 |
| fetch | 14.2 |
| generate | 14.5 |
| geo | 1.3 |
| probe | 95.9 |
| real_test | 89.9 |
| tcp | 74.8 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 29 | 29 | 0 | 100.0% |
| hysteria2 | 13 | 12 | 1 | 92.3% |
| shadowsocks | 180 | 163 | 17 | 90.6% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 162 | 155 | 7 | 95.7% |
| vless | 266 | 162 | 104 | 60.9% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 44 |
| geo:ClientOSError | 43 |
| cn-block:ClientOSError | 11 |
| 204:ProxyError | 9 |
| 204:TimeoutError | 8 |
| 204:ClientOSError | 5 |
| cn-block:TimeoutError | 4 |
| cn-block:ProxyError | 3 |
| speed:ClientOSError | 1 |
| speed:TimeoutError | 1 |
| geo:ProxyError | 1 |
| geo:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5718 |
| ConnectionRefusedError | 939 |
| gaierror | 251 |
| OSError | 234 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.99 | prefer | 29 | 1.0 | 550 |
| Au1rxx-base64 | 0.927 | prefer | 348 | 0.859 | 1751 |
| Surfboard-tg-mixed | 0.842 | prefer | 170 | 0.765 | 7917 |
| mheidari-all | 0.678 | observe | 105 | 0.6 | 14611 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| ermaozi-get_subscribe | 0.328 | observe | 2 | 1.0 | 430 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4960 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2724 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10557 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| ALL | 0.025 | observe | 0 | None | 1 | 0 |
| ALL2 | 0.025 | observe | 0 | None | 1 | 0 |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| github_links | 0.025 | observe | 0 | None | 1 | 0 |
| non_github_links | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 517 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 408 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 403 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 286 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 264 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 263 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 255 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 233 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 228 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 152 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.6 | 63 | 42 | 105 |
| Surfboard-tg-mixed | 0.765 | 130 | 40 | 170 |
| Au1rxx-base64 | 0.859 | 299 | 49 | 348 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 2 | 0 | 2 |
| ermaozi | 1.0 | 29 | 0 | 29 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14611 | yes | 5.23 | 0 |
| SoliSpirit-all | 10557 | yes | 3.14 | 0 |
| Surfboard-tg-mixed | 7917 | yes | 4.42 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.15 | 0 |
| barry-far-vless | 6013 | yes | 1.27 | 0 |
| Surfboard-tg-vless | 5777 | yes | 3.84 | 0 |
| 10ium-ScrapeCategorize-Vless | 4960 | yes | 1.57 | 0 |
| mahdibland-V2RayAggregator | 4459 | yes | 3.44 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.95 | 0 |
| DeltaKronecker-all | 2724 | yes | 5.93 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 45 |
| test_one_timeout | 44 |
| 204 | 22 |
| cn-block | 18 |
| speed | 2 |
