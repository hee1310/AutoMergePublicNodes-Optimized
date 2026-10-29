# AutoNodes 每日报告

生成时间：2026-10-29 22:11:16

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/111 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 3/89 |
| 原始节点数 | 99369 |
| 去重后节点数 | 27785 |
| TCP 可达数 | 3000 |
| 真测通过数 | 478 |
| verified 输出数 | 90 |
| global 输出数 | 300 |
| all 输出数 | 27785 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 25.5 |
| fetch | 14.9 |
| generate | 18.8 |
| geo | 1.4 |
| probe | 109.3 |
| real_test | 82.9 |
| tcp | 86.6 |
| write_verified | 0.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 22 | 1 | 95.7% |
| hysteria2 | 14 | 13 | 1 | 92.9% |
| shadowsocks | 167 | 149 | 18 | 89.2% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 154 | 132 | 22 | 85.7% |
| vless | 251 | 162 | 89 | 64.5% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 73 |
| geo:ClientOSError | 14 |
| 204:ProxyError | 10 |
| cn-block:ClientOSError | 8 |
| 204:TimeoutError | 7 |
| cn-block:TimeoutError | 7 |
| speed:ClientOSError | 3 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 3 |
| geo:ProxyError | 2 |
| speed:TimeoutError | 1 |
| geo:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6820 |
| ConnectionRefusedError | 1101 |
| gaierror | 272 |
| OSError | 238 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.94 | prefer | 23 | 0.957 | 510 |
| Au1rxx-base64 | 0.923 | prefer | 327 | 0.856 | 1722 |
| Surfboard-tg-mixed | 0.853 | prefer | 95 | 0.779 | 7837 |
| mheidari-all | 0.696 | observe | 162 | 0.617 | 33474 |
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
| mheidari-all | 0.617 | 100 | 62 | 162 |
| Surfboard-tg-mixed | 0.779 | 74 | 21 | 95 |
| Au1rxx-base64 | 0.856 | 280 | 47 | 327 |
| ermaozi | 0.957 | 22 | 1 | 23 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 33474 | yes | 7.96 | 0 |
| SoliSpirit-all | 10376 | yes | 3.86 | 0 |
| Surfboard-tg-mixed | 7837 | yes | 5.03 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.42 | 0 |
| barry-far-vless | 6033 | yes | 1.64 | 0 |
| Surfboard-tg-vless | 5821 | yes | 4.03 | 0 |
| 10ium-ScrapeCategorize-Vless | 5005 | yes | 1.98 | 0 |
| mahdibland-V2RayAggregator | 4444 | yes | 3.68 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 2.08 | 0 |
| DeltaKronecker-all | 2709 | yes | 7.55 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| output_guard_preserved | output shrink guard preserved previous files |

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 73 |
| 204 | 20 |
| cn-block | 18 |
| geo | 17 |
| speed | 4 |
