# AutoNodes 每日报告

生成时间：2026-11-05 07:07:18

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 90/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 4/88 |
| 原始节点数 | 233613 |
| 去重后节点数 | 63394 |
| TCP 可达数 | 3000 |
| 真测通过数 | 408 |
| verified 输出数 | 91 |
| global 输出数 | 300 |
| all 输出数 | 63394 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 26.5 |
| fetch | 120.0 |
| generate | 19.3 |
| geo | 1.7 |
| probe | 73.0 |
| real_test | 78.4 |
| tcp | 185.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 1 | 1 | 50.0% |
| http | 44 | 29 | 15 | 65.9% |
| hysteria2 | 14 | 12 | 2 | 85.7% |
| shadowsocks | 207 | 194 | 13 | 93.7% |
| socks | 26 | 11 | 15 | 42.3% |
| trojan | 101 | 78 | 23 | 77.2% |
| vless | 160 | 104 | 56 | 65.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 60 |
| 204:ProxyError | 33 |
| 204:ClientOSError | 8 |
| cn-block:TimeoutError | 5 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 4 |
| speed:TimeoutError | 3 |
| speed:ClientOSError | 3 |
| speed:ProxyError | 2 |
| 204:TimeoutError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15857 |
| ConnectionRefusedError | 2651 |
| gaierror | 956 |
| OSError | 478 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.931 | prefer | 20 | 0.95 | 555 |
| mheidari-all | 0.93 | prefer | 105 | 0.857 | 14576 |
| Au1rxx-base64 | 0.864 | prefer | 246 | 0.797 | 1751 |
| Surfboard-tg-mixed | 0.847 | prefer | 131 | 0.771 | 8675 |
| ALL | 0.5 | observe | 48 | 0.417 | 115536 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 6752 |
| ermaozi-get_subscribe | 0.269 | observe | 1 | 1.0 | 351 |
| chromego_merge | 0.264 | observe | 1 | 1.0 | 228 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5005 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2526 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| ALL2 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 423 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 418 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 301 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 279 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 278 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 270 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 248 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 243 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 167 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 154 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ALL | 0.417 | 20 | 28 | 48 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.771 | 101 | 30 | 131 |
| Au1rxx-base64 | 0.797 | 196 | 50 | 246 |
| mheidari-all | 0.857 | 90 | 15 | 105 |
| ermaozi | 0.95 | 19 | 1 | 20 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| chromego_merge | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| ALL | 115536 | yes | 9.24 | 0 |
| github_links | 35748 | yes | 7.47 | 0 |
| mheidari-all | 14576 | yes | 3.6 | 0 |
| SoliSpirit-all | 10857 | yes | 3.19 | 0 |
| Surfboard-tg-mixed | 8675 | yes | 2.75 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.48 | 0 |
| barry-far-vless | 6243 | yes | 0.55 | 0 |
| Surfboard-tg-vless | 6030 | yes | 2.57 | 0 |
| 10ium-ScrapeCategorize-Vless | 5005 | yes | 1.53 | 0 |
| mahdibland-V2RayAggregator | 4612 | yes | 1.89 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| output_guard_preserved | output shrink guard preserved previous files |

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 60 |
| 204 | 43 |
| cn-block | 13 |
| speed | 8 |
| geo | 1 |
