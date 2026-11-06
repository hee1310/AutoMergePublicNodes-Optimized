# AutoNodes 每日报告

生成时间：2026-11-06 07:08:32

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 90/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 4/88 |
| 原始节点数 | 232447 |
| 去重后节点数 | 63660 |
| TCP 可达数 | 3000 |
| 真测通过数 | 407 |
| verified 输出数 | 79 |
| global 输出数 | 300 |
| all 输出数 | 63660 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 34.4 |
| fetch | 120.0 |
| generate | 26.4 |
| geo | 1.6 |
| probe | 87.5 |
| real_test | 77.5 |
| tcp | 201.6 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 157 | 119 | 38 | 75.8% |
| hysteria2 | 13 | 11 | 2 | 84.6% |
| shadowsocks | 189 | 176 | 13 | 93.1% |
| socks | 23 | 6 | 17 | 26.1% |
| trojan | 34 | 24 | 10 | 70.6% |
| vless | 142 | 95 | 47 | 66.9% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 43 |
| 204:ProxyError | 37 |
| 204:TimeoutError | 14 |
| 204:ClientOSError | 6 |
| cn-block:ProxyError | 5 |
| cn-block:TimeoutError | 5 |
| cn-block:ClientOSError | 4 |
| geo:ProxyError | 4 |
| geo:ClientOSError | 3 |
| speed:ProxyError | 2 |
| speed:TimeoutError | 2 |
| geo:TimeoutError | 1 |
| cn-block:ServerDisconnectedError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 17660 |
| ConnectionRefusedError | 2536 |
| gaierror | 287 |
| OSError | 259 |
| SSRFBlocked | 4 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 1.0 | prefer | 101 | 1.0 | 639 |
| Surfboard-tg-mixed | 0.959 | prefer | 56 | 0.893 | 8762 |
| Au1rxx-base64 | 0.889 | prefer | 125 | 0.824 | 1751 |
| mheidari-all | 0.85 | prefer | 194 | 0.773 | 14233 |
| ALL | 0.397 | observe | 80 | 0.312 | 113829 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5039 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2653 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| ALL2 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 7 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 425 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 420 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 303 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 281 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 280 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 272 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 250 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 245 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 169 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 156 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ALL | 0.312 | 25 | 55 | 80 |
| mheidari-all | 0.773 | 150 | 44 | 194 |
| Au1rxx-base64 | 0.824 | 103 | 22 | 125 |
| Surfboard-tg-mixed | 0.893 | 50 | 6 | 56 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| ermaozi | 1.0 | 101 | 0 | 101 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| ALL | 113829 | yes | 12.01 | 0 |
| github_links | 35748 | yes | 11.16 | 0 |
| mheidari-all | 14233 | yes | 3.04 | 0 |
| SoliSpirit-all | 10891 | yes | 2.94 | 0 |
| Surfboard-tg-mixed | 8762 | yes | 4.64 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.03 | 0 |
| barry-far-vless | 6478 | yes | 1.22 | 0 |
| Surfboard-tg-vless | 6268 | yes | 3.72 | 0 |
| 10ium-ScrapeCategorize-Vless | 5039 | yes | 1.4 | 0 |
| mahdibland-V2RayAggregator | 4703 | yes | 2.54 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 57 |
| test_one_timeout | 43 |
| cn-block | 15 |
| geo | 8 |
| speed | 4 |
