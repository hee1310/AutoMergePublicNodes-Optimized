# AutoNodes 每日报告

生成时间：2026-11-06 19:40:03

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 4/88 |
| 原始节点数 | 231414 |
| 去重后节点数 | 63717 |
| TCP 可达数 | 3000 |
| 真测通过数 | 367 |
| verified 输出数 | 48 |
| global 输出数 | 300 |
| all 输出数 | 63717 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 29.7 |
| fetch | 120.0 |
| generate | 21.2 |
| geo | 1.7 |
| probe | 71.3 |
| real_test | 73.3 |
| tcp | 204.1 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 104 | 47 | 57 | 45.2% |
| hysteria2 | 13 | 12 | 1 | 92.3% |
| shadowsocks | 204 | 187 | 17 | 91.7% |
| socks | 14 | 8 | 6 | 57.1% |
| trojan | 69 | 38 | 31 | 55.1% |
| vless | 152 | 97 | 55 | 63.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 63 |
| test_one_timeout:15.0s | 50 |
| 204:TimeoutError | 19 |
| 204:ClientOSError | 10 |
| cn-block:ProxyError | 10 |
| cn-block:ClientOSError | 5 |
| cn-block:TimeoutError | 4 |
| geo:ProxyError | 3 |
| geo:TimeoutError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 17575 |
| ConnectionRefusedError | 2563 |
| gaierror | 508 |
| OSError | 260 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.992 | prefer | 33 | 1.0 | 513 |
| mheidari-all | 0.922 | prefer | 55 | 0.855 | 14184 |
| Au1rxx-base64 | 0.829 | prefer | 222 | 0.761 | 1751 |
| Surfboard-tg-mixed | 0.811 | prefer | 158 | 0.734 | 8758 |
| ALL | 0.344 | observe | 85 | 0.259 | 113013 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 179 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4934 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10962 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| ALL2 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 426 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 421 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 304 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 282 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 281 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 273 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 251 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 246 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 170 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 157 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.0 | 0 | 1 | 1 |
| ALL | 0.259 | 22 | 63 | 85 |
| Surfboard-tg-mixed | 0.734 | 116 | 42 | 158 |
| Au1rxx-base64 | 0.761 | 169 | 53 | 222 |
| mheidari-all | 0.855 | 47 | 8 | 55 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| ermaozi | 1.0 | 33 | 0 | 33 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| ALL | 113013 | yes | 8.09 | 0 |
| github_links | 30750 | yes | 9.67 | 0 |
| mheidari-all | 14184 | yes | 2.75 | 0 |
| SoliSpirit-all | 10962 | yes | 2.0 | 0 |
| Surfboard-tg-mixed | 8758 | yes | 2.46 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.53 | 0 |
| barry-far-vless | 6479 | yes | 0.49 | 0 |
| Surfboard-tg-vless | 6135 | yes | 1.97 | 0 |
| 10ium-ScrapeCategorize-Vless | 4934 | yes | 1.31 | 0 |
| mahdibland-V2RayAggregator | 4703 | yes | 0.59 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 92 |
| test_one_timeout | 50 |
| cn-block | 19 |
| geo | 5 |
| speed | 1 |
