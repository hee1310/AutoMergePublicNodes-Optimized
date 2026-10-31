# AutoNodes 每日报告

生成时间：2026-10-31 12:46:48

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/111 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 3/90 |
| 原始节点数 | 80704 |
| 去重后节点数 | 26392 |
| TCP 可达数 | 3000 |
| 真测通过数 | 373 |
| verified 输出数 | 77 |
| global 输出数 | 300 |
| all 输出数 | 26392 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 25.2 |
| fetch | 11.0 |
| generate | 8.7 |
| geo | 1.2 |
| probe | 70.5 |
| real_test | 79.1 |
| tcp | 76.3 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 16 | 13 | 3 | 81.2% |
| shadowsocks | 97 | 87 | 10 | 89.7% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 156 | 117 | 39 | 75.0% |
| vless | 236 | 136 | 100 | 57.6% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 78 |
| geo:ClientOSError | 20 |
| 204:TimeoutError | 14 |
| cn-block:TimeoutError | 11 |
| 204:ProxyError | 10 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| speed:ProxyError | 3 |
| geo:TimeoutError | 3 |
| cn-block:ClientOSError | 2 |
| speed:TimeoutError | 2 |
| speed:ClientOSError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5867 |
| ConnectionRefusedError | 969 |
| OSError | 234 |
| gaierror | 199 |
| SSRFBlocked | 4 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.923 | prefer | 19 | 1.0 | 43 |
| Au1rxx-base64 | 0.851 | prefer | 304 | 0.783 | 1751 |
| DeltaKronecker-all | 0.725 | prefer | 19 | 0.684 | 2848 |
| mheidari-all | 0.638 | observe | 163 | 0.558 | 14723 |
| Surfboard-tg-mixed | 0.515 | observe | 16 | 0.5 | 7861 |
| ermaozi | 0.314 | observe | 2 | 1.0 | 79 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 6752 |
| ermaozi-get_subscribe | 0.271 | observe | 1 | 1.0 | 412 |
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
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 519 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 410 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 405 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 288 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 266 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 265 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 257 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 235 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 230 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 154 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.5 | 8 | 8 | 16 |
| mheidari-all | 0.558 | 91 | 72 | 163 |
| DeltaKronecker-all | 0.684 | 13 | 6 | 19 |
| Au1rxx-base64 | 0.783 | 238 | 66 | 304 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| ermaozi | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 19 | 0 | 19 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14723 | yes | 2.76 | 0 |
| SoliSpirit-all | 10576 | yes | 1.87 | 0 |
| Surfboard-tg-mixed | 7861 | yes | 2.25 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.58 | 0 |
| barry-far-vless | 5912 | yes | 0.39 | 0 |
| Surfboard-tg-vless | 5698 | yes | 1.93 | 0 |
| 10ium-ScrapeCategorize-Vless | 4970 | yes | 0.72 | 0 |
| mahdibland-V2RayAggregator | 4635 | yes | 1.74 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.79 | 0 |
| DeltaKronecker-all | 2848 | yes | 3.26 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 78 |
| 204 | 28 |
| geo | 24 |
| cn-block | 16 |
| speed | 7 |
