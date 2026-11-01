# AutoNodes 每日报告

生成时间：2026-11-01 06:23:03

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/111 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 4/89 |
| 原始节点数 | 80510 |
| 去重后节点数 | 26376 |
| TCP 可达数 | 3000 |
| 真测通过数 | 614 |
| verified 输出数 | 72 |
| global 输出数 | 300 |
| all 输出数 | 26376 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 35.1 |
| fetch | 14.1 |
| generate | 14.7 |
| geo | 1.3 |
| probe | 99.0 |
| real_test | 101.2 |
| tcp | 74.3 |
| write_verified | 0.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 55 | 52 | 3 | 94.5% |
| hysteria2 | 19 | 15 | 4 | 78.9% |
| shadowsocks | 174 | 154 | 20 | 88.5% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 261 | 234 | 27 | 89.7% |
| vless | 291 | 157 | 134 | 54.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 90 |
| geo:ClientOSError | 40 |
| 204:ProxyError | 19 |
| cn-block:ClientOSError | 10 |
| 204:TimeoutError | 5 |
| cn-block:TimeoutError | 5 |
| 204:ClientOSError | 4 |
| speed:ClientOSError | 4 |
| geo:TimeoutError | 4 |
| cn-block:ProxyError | 3 |
| speed:TimeoutError | 3 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5714 |
| ConnectionRefusedError | 973 |
| OSError | 235 |
| gaierror | 213 |
| SSRFBlocked | 4 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.971 | prefer | 37 | 0.973 | 558 |
| Au1rxx-base64 | 0.892 | prefer | 341 | 0.824 | 1751 |
| zhangkai | 0.877 | prefer | 19 | 0.947 | 43 |
| mheidari-all | 0.831 | prefer | 215 | 0.753 | 14747 |
| Surfboard-tg-mixed | 0.695 | observe | 185 | 0.616 | 7809 |
| DeltaKronecker-all | 0.335 | observe | 1 | 1.0 | 2848 |
| xiaoji235-airport-v2ray-all | 0.32 | observe | 4 | 0.5 | 6752 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 178 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4970 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| ALL | 0.025 | observe | 0 | None | 1 | 0 |
| ALL2 | 0.025 | observe | 0 | None | 1 | 0 |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| github_links | 0.025 | observe | 0 | None | 1 | 0 |
| non_github_links | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 521 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 412 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 407 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 290 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 268 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 267 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 259 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 237 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 232 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 156 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mahdibland-V2RayAggregator | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.5 | 2 | 2 | 4 |
| Surfboard-tg-mixed | 0.616 | 114 | 71 | 185 |
| mheidari-all | 0.753 | 162 | 53 | 215 |
| Au1rxx-base64 | 0.824 | 281 | 60 | 341 |
| zhangkai | 0.947 | 18 | 1 | 19 |
| ermaozi-get_subscribe | 0.973 | 36 | 1 | 37 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| DeltaKronecker-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14747 | yes | 5.06 | 0 |
| SoliSpirit-all | 10495 | yes | 3.1 | 0 |
| Surfboard-tg-mixed | 7809 | yes | 3.99 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.66 | 0 |
| barry-far-vless | 5805 | yes | 0.99 | 0 |
| Surfboard-tg-vless | 5637 | yes | 3.7 | 0 |
| 10ium-ScrapeCategorize-Vless | 4970 | yes | 1.24 | 0 |
| mahdibland-V2RayAggregator | 4635 | yes | 3.35 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.88 | 0 |
| DeltaKronecker-all | 2848 | yes | 4.68 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 90 |
| geo | 46 |
| 204 | 28 |
| cn-block | 18 |
| speed | 7 |
