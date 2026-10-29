# AutoNodes 每日报告

生成时间：2026-10-29 21:55:21

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/107 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 4/84 |
| 原始节点数 | 99300 |
| 去重后节点数 | 27781 |
| TCP 可达数 | 3000 |
| 真测通过数 | 484 |
| verified 输出数 | 71 |
| global 输出数 | 300 |
| all 输出数 | 27781 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 28.5 |
| fetch | 5.5 |
| generate | 11.2 |
| geo | 1.4 |
| probe | 80.0 |
| real_test | 84.3 |
| tcp | 88.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 22 | 1 | 95.7% |
| hysteria2 | 13 | 13 | 0 | 100.0% |
| shadowsocks | 162 | 136 | 26 | 84.0% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 156 | 132 | 24 | 84.6% |
| vless | 261 | 181 | 80 | 69.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 80 |
| geo:ClientOSError | 16 |
| cn-block:ClientOSError | 8 |
| 204:ProxyError | 7 |
| 204:TimeoutError | 6 |
| cn-block:TimeoutError | 4 |
| speed:ClientOSError | 3 |
| 204:ClientOSError | 3 |
| speed:ProxyError | 2 |
| geo:TimeoutError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6993 |
| ConnectionRefusedError | 1094 |
| gaierror | 241 |
| OSError | 237 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.94 | prefer | 23 | 0.957 | 510 |
| Au1rxx-base64 | 0.918 | prefer | 323 | 0.851 | 1722 |
| Surfboard-tg-mixed | 0.827 | prefer | 97 | 0.753 | 7837 |
| mheidari-all | 0.737 | prefer | 170 | 0.659 | 33474 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 6752 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 176 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5005 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2709 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10376 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 7 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-ShadowsocksM | 0.175 | observe | 0 | None | 0 | 2 |

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
| mheidari-all | 0.659 | 112 | 58 | 170 |
| Surfboard-tg-mixed | 0.753 | 73 | 24 | 97 |
| Au1rxx-base64 | 0.851 | 275 | 48 | 323 |
| ermaozi | 0.957 | 22 | 1 | 23 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 33474 | yes | 4.88 | 0 |
| SoliSpirit-all | 10376 | yes | 2.8 | 0 |
| Surfboard-tg-mixed | 7837 | yes | 2.96 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.53 | 0 |
| barry-far-vless | 6033 | yes | 1.36 | 0 |
| Surfboard-tg-vless | 5821 | yes | 3.16 | 0 |
| 10ium-ScrapeCategorize-Vless | 5005 | yes | 1.53 | 0 |
| mahdibland-V2RayAggregator | 4444 | yes | 2.35 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.8 | 0 |
| DeltaKronecker-all | 2709 | yes | 3.9 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| output_guard_preserved | output shrink guard preserved previous files |

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 80 |
| geo | 17 |
| 204 | 16 |
| cn-block | 13 |
| speed | 5 |
