# AutoNodes 每日报告

生成时间：2026-11-04 23:56:18

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/107 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 4/85 |
| 原始节点数 | 81907 |
| 去重后节点数 | 26702 |
| TCP 可达数 | 3000 |
| 真测通过数 | 448 |
| verified 输出数 | 33 |
| global 输出数 | 300 |
| all 输出数 | 26702 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 29.2 |
| fetch | 7.0 |
| generate | 14.7 |
| geo | 1.3 |
| probe | 98.2 |
| real_test | 74.9 |
| tcp | 75.9 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 20 | 19 | 1 | 95.0% |
| hysteria2 | 15 | 14 | 1 | 93.3% |
| shadowsocks | 228 | 207 | 21 | 90.8% |
| socks | 10 | 7 | 3 | 70.0% |
| trojan | 73 | 73 | 0 | 100.0% |
| vless | 200 | 135 | 65 | 67.5% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 56 |
| 204:ProxyError | 9 |
| 204:TimeoutError | 6 |
| 204:ClientOSError | 6 |
| cn-block:ProxyError | 3 |
| cn-block:ClientOSError | 3 |
| cn-block:TimeoutError | 3 |
| speed:ClientOSError | 2 |
| geo:ClientOSError | 1 |
| geo:ProxyError | 1 |
| geo:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5953 |
| ConnectionRefusedError | 999 |
| gaierror | 248 |
| OSError | 232 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.968 | prefer | 87 | 0.897 | 8651 |
| zhangkai | 0.923 | prefer | 19 | 1.0 | 43 |
| Au1rxx-base64 | 0.893 | prefer | 241 | 0.826 | 1751 |
| mheidari-all | 0.879 | prefer | 197 | 0.802 | 14725 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5005 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2526 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10844 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6015 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.802 | 158 | 39 | 197 |
| Au1rxx-base64 | 0.826 | 199 | 42 | 241 |
| Surfboard-tg-mixed | 0.897 | 78 | 9 | 87 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 19 | 0 | 19 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14725 | yes | 5.48 | 0 |
| SoliSpirit-all | 10844 | yes | 1.86 | 0 |
| Surfboard-tg-mixed | 8651 | yes | 3.97 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.14 | 0 |
| barry-far-vless | 6228 | yes | 1.15 | 0 |
| Surfboard-tg-vless | 6015 | yes | 3.67 | 0 |
| 10ium-ScrapeCategorize-Vless | 5005 | yes | 1.39 | 0 |
| mahdibland-V2RayAggregator | 4612 | yes | 3.38 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.93 | 0 |
| DeltaKronecker-all | 2526 | yes | 6.4 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 56 |
| 204 | 21 |
| cn-block | 9 |
| geo | 3 |
| speed | 2 |
