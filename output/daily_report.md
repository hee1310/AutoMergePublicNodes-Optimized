# AutoNodes 每日报告

生成时间：2026-11-05 20:13:53

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 90/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 4/88 |
| 原始节点数 | 232567 |
| 去重后节点数 | 63837 |
| TCP 可达数 | 3000 |
| 真测通过数 | 353 |
| verified 输出数 | 101 |
| global 输出数 | 300 |
| all 输出数 | 63837 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 25.4 |
| fetch | 120.0 |
| generate | 27.1 |
| geo | 1.7 |
| probe | 86.7 |
| real_test | 66.8 |
| tcp | 201.2 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 94 | 66 | 28 | 70.2% |
| hysteria2 | 14 | 13 | 1 | 92.9% |
| shadowsocks | 204 | 182 | 22 | 89.2% |
| socks | 24 | 6 | 18 | 25.0% |
| trojan | 47 | 31 | 16 | 66.0% |
| vless | 97 | 65 | 32 | 67.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 37 |
| test_one_timeout:15.0s | 34 |
| 204:ClientOSError | 14 |
| 204:TimeoutError | 9 |
| cn-block:ClientOSError | 5 |
| geo:TimeoutError | 5 |
| cn-block:ProxyError | 4 |
| speed:ClientOSError | 3 |
| geo:ProxyError | 2 |
| geo:ClientOSError | 2 |
| cn-block:TimeoutError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 17542 |
| ConnectionRefusedError | 2538 |
| gaierror | 395 |
| OSError | 260 |
| SSRFBlocked | 2 |
| UnicodeError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.993 | prefer | 63 | 0.984 | 593 |
| mheidari-all | 0.926 | prefer | 160 | 0.85 | 14461 |
| Surfboard-tg-mixed | 0.894 | prefer | 57 | 0.825 | 8690 |
| Au1rxx-base64 | 0.799 | prefer | 138 | 0.732 | 1751 |
| tg-LonUp_M | 0.365 | observe | 3 | 1.0 | 177 |
| DeltaKronecker-all | 0.335 | observe | 1 | 1.0 | 2653 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| ALL | 0.287 | observe | 56 | 0.196 | 114168 |
| peasoft-NoMoreWalls | 0.259 | observe | 1 | 1.0 | 96 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5039 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| ALL2 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 6 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 424 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 419 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 302 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 280 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 279 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 271 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 249 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 244 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 168 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 155 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ALL | 0.196 | 11 | 45 | 56 |
| Au1rxx-base64 | 0.732 | 101 | 37 | 138 |
| Surfboard-tg-mixed | 0.825 | 47 | 10 | 57 |
| mheidari-all | 0.85 | 136 | 24 | 160 |
| ermaozi | 0.984 | 62 | 1 | 63 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| peasoft-NoMoreWalls | 1.0 | 1 | 0 | 1 |
| DeltaKronecker-all | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| ALL | 114168 | yes | 12.04 | 0 |
| github_links | 35709 | yes | 12.5 | 0 |
| mheidari-all | 14461 | yes | 5.28 | 0 |
| SoliSpirit-all | 10977 | yes | 4.29 | 0 |
| Surfboard-tg-mixed | 8690 | yes | 4.27 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.6 | 0 |
| barry-far-vless | 6358 | yes | 0.7 | 0 |
| Surfboard-tg-vless | 6065 | yes | 3.37 | 0 |
| 10ium-ScrapeCategorize-Vless | 5039 | yes | 0.49 | 0 |
| mahdibland-V2RayAggregator | 4612 | yes | 2.56 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 60 |
| test_one_timeout | 34 |
| cn-block | 10 |
| geo | 9 |
| speed | 4 |
