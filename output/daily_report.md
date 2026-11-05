# AutoNodes 每日报告

生成时间：2026-11-05 00:10:07

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/110 |
| 清理建议：禁用/降权 | 18/1 |
| 清理建议：优先/观察 | 3/88 |
| 原始节点数 | 233568 |
| 去重后节点数 | 63768 |
| TCP 可达数 | 3000 |
| 真测通过数 | 427 |
| verified 输出数 | 91 |
| global 输出数 | 300 |
| all 输出数 | 63768 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 21.1 |
| fetch | 120.0 |
| generate | 32.8 |
| geo | 1.8 |
| probe | 98.9 |
| real_test | 103.5 |
| tcp | 202.7 |
| write_verified | 0.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 91 | 37 | 54 | 40.7% |
| hysteria2 | 15 | 13 | 2 | 86.7% |
| shadowsocks | 222 | 202 | 20 | 91.0% |
| socks | 21 | 13 | 8 | 61.9% |
| trojan | 33 | 32 | 1 | 97.0% |
| vless | 354 | 161 | 193 | 45.5% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 148 |
| 204:ProxyError | 40 |
| speed:ClientOSError | 30 |
| geo:ClientOSError | 16 |
| 204:TimeoutError | 11 |
| 204:ClientOSError | 6 |
| cn-block:ClientOSError | 6 |
| cn-block:TimeoutError | 6 |
| speed:TimeoutError | 5 |
| cn-block:ProxyError | 4 |
| geo:TimeoutError | 4 |
| geo:ProxyError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 17304 |
| ConnectionRefusedError | 2540 |
| gaierror | 494 |
| OSError | 259 |
| SSRFBlocked | 4 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.952 | prefer | 167 | 0.886 | 1751 |
| zhangkai | 0.923 | prefer | 19 | 1.0 | 43 |
| Surfboard-tg-mixed | 0.904 | prefer | 66 | 0.833 | 8651 |
| mheidari-all | 0.617 | observe | 378 | 0.537 | 14725 |
| ALL | 0.41 | observe | 95 | 0.326 | 115838 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5005 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2526 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10844 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6015 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| ALL2 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| tg-oneclickvpnkeys | 0.133 | observe | 1 | 0.0 | 0 | 139 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 7 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 422 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 417 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 300 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 278 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 277 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 269 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 247 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 242 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 166 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 153 | 连续死亡次数 >= 2 |
| downweight | xiaoji235-airport-v2ray-all | 0.249 | 10 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.2 | 2 | 8 | 10 |
| ALL | 0.326 | 31 | 64 | 95 |
| mheidari-all | 0.537 | 203 | 175 | 378 |
| Surfboard-tg-mixed | 0.833 | 55 | 11 | 66 |
| Au1rxx-base64 | 0.886 | 148 | 19 | 167 |
| zhangkai | 1.0 | 19 | 0 | 19 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| ALL | 115838 | yes | 14.63 | 0 |
| github_links | 35748 | yes | 12.36 | 0 |
| mheidari-all | 14725 | yes | 5.96 | 0 |
| SoliSpirit-all | 10844 | yes | 3.27 | 0 |
| Surfboard-tg-mixed | 8651 | yes | 5.49 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.96 | 0 |
| barry-far-vless | 6228 | yes | 1.1 | 0 |
| Surfboard-tg-vless | 6015 | yes | 3.75 | 0 |
| 10ium-ScrapeCategorize-Vless | 5005 | yes | 0.82 | 0 |
| mahdibland-V2RayAggregator | 4612 | yes | 3.41 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 148 |
| 204 | 57 |
| speed | 36 |
| geo | 21 |
| cn-block | 16 |
