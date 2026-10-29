# AutoNodes 每日报告

生成时间：2026-10-29 22:03:36

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/111 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 4/88 |
| 原始节点数 | 99370 |
| 去重后节点数 | 27785 |
| TCP 可达数 | 3000 |
| 真测通过数 | 484 |
| verified 输出数 | 60 |
| global 输出数 | 300 |
| all 输出数 | 27785 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 30.2 |
| fetch | 10.9 |
| generate | 9.6 |
| geo | 1.3 |
| probe | 74.9 |
| real_test | 85.8 |
| tcp | 88.2 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 22 | 21 | 1 | 95.5% |
| hysteria2 | 15 | 12 | 3 | 80.0% |
| shadowsocks | 160 | 146 | 14 | 91.2% |
| trojan | 158 | 143 | 15 | 90.5% |
| vless | 264 | 162 | 102 | 61.4% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 81 |
| geo:ClientOSError | 16 |
| 204:ProxyError | 9 |
| cn-block:ClientOSError | 9 |
| 204:TimeoutError | 5 |
| cn-block:ProxyError | 4 |
| cn-block:TimeoutError | 4 |
| 204:ClientOSError | 4 |
| speed:ClientOSError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7136 |
| ConnectionRefusedError | 1088 |
| OSError | 236 |
| gaierror | 189 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.937 | prefer | 22 | 0.955 | 510 |
| Au1rxx-base64 | 0.901 | prefer | 320 | 0.834 | 1722 |
| Surfboard-tg-mixed | 0.9 | prefer | 98 | 0.827 | 7837 |
| mheidari-all | 0.72 | prefer | 176 | 0.642 | 33474 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 6752 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 176 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5005 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2709 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10376 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| ALL | 0.025 | observe | 0 | None | 1 | 0 |
| ALL2 | 0.025 | observe | 0 | None | 1 | 0 |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| github_links | 0.025 | observe | 0 | None | 1 | 0 |
| non_github_links | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 7 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 514 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 405 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 400 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 283 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 261 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 260 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 252 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 230 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 225 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 149 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.642 | 113 | 63 | 176 |
| Surfboard-tg-mixed | 0.827 | 81 | 17 | 98 |
| Au1rxx-base64 | 0.834 | 267 | 53 | 320 |
| ermaozi | 0.955 | 21 | 1 | 22 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 33474 | yes | 3.64 | 0 |
| SoliSpirit-all | 10376 | yes | 2.15 | 0 |
| Surfboard-tg-mixed | 7837 | yes | 2.0 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.02 | 0 |
| barry-far-vless | 6033 | yes | 0.43 | 0 |
| Surfboard-tg-vless | 5821 | yes | 2.87 | 0 |
| 10ium-ScrapeCategorize-Vless | 5005 | yes | 0.6 | 0 |
| mahdibland-V2RayAggregator | 4444 | yes | 1.73 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.06 | 0 |
| DeltaKronecker-all | 2709 | yes | 3.66 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| output_guard_preserved | output shrink guard preserved previous files |

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 81 |
| 204 | 18 |
| cn-block | 17 |
| geo | 16 |
| speed | 3 |
