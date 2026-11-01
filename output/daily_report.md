# AutoNodes 每日报告

生成时间：2026-11-01 13:38:31

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/111 |
| 清理建议：禁用/降权 | 17/0 |
| 清理建议：优先/观察 | 5/89 |
| 原始节点数 | 81865 |
| 去重后节点数 | 26805 |
| TCP 可达数 | 3000 |
| 真测通过数 | 517 |
| verified 输出数 | 108 |
| global 输出数 | 300 |
| all 输出数 | 26805 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 27.9 |
| fetch | 11.8 |
| generate | 11.1 |
| geo | 1.2 |
| probe | 77.6 |
| real_test | 107.6 |
| tcp | 79.6 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 74 | 72 | 2 | 97.3% |
| hysteria2 | 13 | 10 | 3 | 76.9% |
| shadowsocks | 162 | 141 | 21 | 87.0% |
| trojan | 209 | 149 | 60 | 71.3% |
| vless | 283 | 144 | 139 | 50.9% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 121 |
| geo:ClientOSError | 44 |
| 204:ProxyError | 15 |
| cn-block:TimeoutError | 10 |
| 204:TimeoutError | 9 |
| cn-block:ClientOSError | 6 |
| cn-block:ProxyError | 5 |
| geo:ProxyError | 4 |
| 204:ClientOSError | 3 |
| geo:TimeoutError | 2 |
| speed:ProxyError | 2 |
| speed:TimeoutError | 2 |
| speed:ClientOSError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6087 |
| ConnectionRefusedError | 963 |
| OSError | 237 |
| gaierror | 169 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.985 | prefer | 55 | 0.982 | 499 |
| zhangkai | 0.877 | prefer | 19 | 0.947 | 43 |
| DeltaKronecker-all | 0.868 | prefer | 31 | 0.806 | 3716 |
| Au1rxx-base64 | 0.846 | prefer | 311 | 0.778 | 1751 |
| Surfboard-tg-mixed | 0.784 | prefer | 96 | 0.708 | 8063 |
| mheidari-all | 0.553 | observe | 224 | 0.473 | 14747 |
| xiaoji235-airport-v2ray-all | 0.32 | observe | 4 | 0.5 | 6752 |
| ermaozi | 0.314 | observe | 2 | 1.0 | 79 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4976 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |

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
| disable | tg-Letiranbreath | 0.0 | 0 | None | 413 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 408 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 291 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 269 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 268 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 260 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 238 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 233 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 157 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 144 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.473 | 106 | 118 | 224 |
| xiaoji235-airport-v2ray-all | 0.5 | 2 | 2 | 4 |
| Surfboard-tg-mixed | 0.708 | 68 | 28 | 96 |
| Au1rxx-base64 | 0.778 | 242 | 69 | 311 |
| DeltaKronecker-all | 0.806 | 25 | 6 | 31 |
| zhangkai | 0.947 | 18 | 1 | 19 |
| ermaozi-get_subscribe | 0.982 | 54 | 1 | 55 |
| ermaozi | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14747 | yes | 4.46 | 0 |
| SoliSpirit-all | 10600 | yes | 0.49 | 0 |
| Surfboard-tg-mixed | 8063 | yes | 3.24 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.61 | 0 |
| barry-far-vless | 5850 | yes | 0.67 | 0 |
| Surfboard-tg-vless | 5660 | yes | 3.05 | 0 |
| 10ium-ScrapeCategorize-Vless | 4976 | yes | 1.81 | 0 |
| mahdibland-V2RayAggregator | 4680 | yes | 2.33 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.66 | 0 |
| DeltaKronecker-all | 3716 | yes | 4.48 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 121 |
| geo | 50 |
| 204 | 27 |
| cn-block | 21 |
| speed | 6 |
