# AutoNodes 每日报告

生成时间：2026-10-31 21:46:52

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/111 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 4/89 |
| 原始节点数 | 80847 |
| 去重后节点数 | 26339 |
| TCP 可达数 | 3000 |
| 真测通过数 | 487 |
| verified 输出数 | 106 |
| global 输出数 | 300 |
| all 输出数 | 26339 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 24.6 |
| fetch | 13.2 |
| generate | 14.6 |
| geo | 1.3 |
| probe | 96.2 |
| real_test | 84.6 |
| tcp | 75.1 |
| write_verified | 0.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 22 | 1 | 95.7% |
| hysteria2 | 16 | 15 | 1 | 93.8% |
| shadowsocks | 167 | 154 | 13 | 92.2% |
| trojan | 186 | 172 | 14 | 92.5% |
| vless | 222 | 126 | 96 | 56.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 61 |
| geo:ClientOSError | 29 |
| 204:ProxyError | 12 |
| cn-block:ClientOSError | 8 |
| 204:TimeoutError | 5 |
| geo:TimeoutError | 2 |
| 204:ClientOSError | 2 |
| cn-block:TimeoutError | 2 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |
| speed:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5774 |
| ConnectionRefusedError | 954 |
| OSError | 235 |
| gaierror | 204 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.925 | prefer | 322 | 0.857 | 1751 |
| zhangkai | 0.923 | prefer | 19 | 1.0 | 43 |
| Surfboard-tg-mixed | 0.919 | prefer | 60 | 0.85 | 7936 |
| mheidari-all | 0.743 | prefer | 203 | 0.665 | 14850 |
| DeltaKronecker-all | 0.4 | observe | 4 | 0.75 | 2848 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| ermaozi-get_subscribe | 0.328 | observe | 2 | 1.0 | 412 |
| peasoft-NoMoreWalls | 0.264 | observe | 1 | 1.0 | 227 |
| tg-oneclickvpnkeys | 0.259 | observe | 1 | 1.0 | 108 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4970 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| ALL | 0.025 | observe | 0 | None | 1 | 0 |
| ALL2 | 0.025 | observe | 0 | None | 1 | 0 |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| github_links | 0.025 | observe | 0 | None | 1 | 0 |
| non_github_links | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 520 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 411 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 406 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 289 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 267 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 266 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 258 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 236 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 231 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 155 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mahdibland-V2RayAggregator | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.665 | 135 | 68 | 203 |
| DeltaKronecker-all | 0.75 | 3 | 1 | 4 |
| Surfboard-tg-mixed | 0.85 | 51 | 9 | 60 |
| Au1rxx-base64 | 0.857 | 276 | 46 | 322 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| peasoft-NoMoreWalls | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 19 | 0 | 19 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14850 | yes | 6.8 | 0 |
| SoliSpirit-all | 10505 | yes | 4.07 | 0 |
| Surfboard-tg-mixed | 7936 | yes | 5.72 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.35 | 0 |
| barry-far-vless | 5849 | yes | 2.32 | 0 |
| Surfboard-tg-vless | 5636 | yes | 4.0 | 0 |
| 10ium-ScrapeCategorize-Vless | 4970 | yes | 2.56 | 0 |
| mahdibland-V2RayAggregator | 4635 | yes | 3.62 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.06 | 0 |
| DeltaKronecker-all | 2848 | yes | 6.16 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 61 |
| geo | 31 |
| 204 | 19 |
| cn-block | 12 |
| speed | 2 |
