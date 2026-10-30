# AutoNodes 每日报告

生成时间：2026-10-30 13:09:48

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/111 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 3/89 |
| 原始节点数 | 100337 |
| 去重后节点数 | 27803 |
| TCP 可达数 | 3000 |
| 真测通过数 | 439 |
| verified 输出数 | 96 |
| global 输出数 | 300 |
| all 输出数 | 27803 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 21.6 |
| fetch | 14.6 |
| generate | 15.3 |
| geo | 1.3 |
| probe | 96.3 |
| real_test | 79.3 |
| tcp | 87.8 |
| write_verified | 0.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 28 | 27 | 1 | 96.4% |
| hysteria2 | 13 | 11 | 2 | 84.6% |
| shadowsocks | 147 | 130 | 17 | 88.4% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 157 | 131 | 26 | 83.4% |
| vless | 247 | 140 | 107 | 56.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 85 |
| geo:ClientOSError | 25 |
| 204:ProxyError | 7 |
| 204:TimeoutError | 7 |
| cn-block:ClientOSError | 6 |
| 204:ClientOSError | 5 |
| cn-block:TimeoutError | 4 |
| speed:TimeoutError | 4 |
| cn-block:ProxyError | 4 |
| geo:ProxyError | 3 |
| speed:ProxyError | 2 |
| geo:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6947 |
| ConnectionRefusedError | 1102 |
| gaierror | 249 |
| OSError | 244 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.955 | prefer | 28 | 0.964 | 550 |
| Au1rxx-base64 | 0.878 | prefer | 336 | 0.81 | 1751 |
| Surfboard-tg-mixed | 0.722 | prefer | 135 | 0.644 | 7902 |
| mheidari-all | 0.65 | observe | 91 | 0.571 | 34171 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4960 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10521 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5822 |
| barry-far-vless | 0.255 | observe | 0 | None | 5942 |

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
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 516 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 407 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 402 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 285 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 263 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 262 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 254 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 232 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 227 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 151 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.571 | 52 | 39 | 91 |
| Surfboard-tg-mixed | 0.644 | 87 | 48 | 135 |
| Au1rxx-base64 | 0.81 | 272 | 64 | 336 |
| ermaozi | 0.964 | 27 | 1 | 28 |
| xiaoji235-airport-v2ray-all | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 34171 | yes | 7.03 | 0 |
| SoliSpirit-all | 10521 | yes | 2.41 | 0 |
| Surfboard-tg-mixed | 7902 | yes | 4.45 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.5 | 0 |
| barry-far-vless | 5942 | yes | 1.13 | 0 |
| Surfboard-tg-vless | 5822 | yes | 4.65 | 0 |
| 10ium-ScrapeCategorize-Vless | 4960 | yes | 1.51 | 0 |
| mahdibland-V2RayAggregator | 4445 | yes | 3.41 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.24 | 0 |
| DeltaKronecker-all | 2724 | yes | 7.29 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 85 |
| geo | 29 |
| 204 | 19 |
| cn-block | 14 |
| speed | 6 |
