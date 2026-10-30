# AutoNodes 每日报告

生成时间：2026-10-30 06:02:05

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 86/111 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 3/89 |
| 原始节点数 | 99867 |
| 去重后节点数 | 27982 |
| TCP 可达数 | 3000 |
| 真测通过数 | 490 |
| verified 输出数 | 107 |
| global 输出数 | 300 |
| all 输出数 | 27982 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 19.8 |
| fetch | 14.1 |
| generate | 15.3 |
| geo | 1.3 |
| probe | 87.0 |
| real_test | 90.6 |
| tcp | 88.1 |
| write_verified | 0.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 0 | 1 | 0.0% |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 14 | 13 | 1 | 92.9% |
| shadowsocks | 165 | 147 | 18 | 89.1% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 175 | 151 | 24 | 86.3% |
| vless | 318 | 159 | 159 | 50.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 114 |
| geo:ClientOSError | 39 |
| cn-block:ClientOSError | 10 |
| speed:ClientOSError | 10 |
| 204:ProxyError | 9 |
| cn-block:TimeoutError | 7 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 2 |
| speed:TimeoutError | 2 |
| 204:TimeoutError | 2 |
| geo:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7015 |
| ConnectionRefusedError | 1105 |
| gaierror | 241 |
| OSError | 237 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.975 | prefer | 20 | 1.0 | 515 |
| Au1rxx-base64 | 0.922 | prefer | 345 | 0.855 | 1735 |
| Surfboard-tg-mixed | 0.701 | prefer | 143 | 0.622 | 7756 |
| mheidari-all | 0.542 | observe | 182 | 0.462 | 34034 |
| xiaoji235-airport-v2ray-all | 0.349 | observe | 3 | 0.667 | 6752 |
| DeltaKronecker-all | 0.335 | observe | 1 | 1.0 | 2709 |
| ninja-vless | 0.327 | observe | 1 | 1.0 | 1791 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5005 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10500 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| ALL | 0.025 | observe | 0 | None | 1 | 0 |
| ALL2 | 0.025 | observe | 0 | None | 1 | 0 |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| github_links | 0.025 | observe | 0 | None | 1 | 0 |
| non_github_links | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 515 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 406 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 401 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 284 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 262 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 261 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 253 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 231 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 226 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 150 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.462 | 84 | 98 | 182 |
| Surfboard-tg-mixed | 0.622 | 89 | 54 | 143 |
| xiaoji235-airport-v2ray-all | 0.667 | 2 | 1 | 3 |
| Au1rxx-base64 | 0.855 | 295 | 50 | 345 |
| DeltaKronecker-all | 1.0 | 1 | 0 | 1 |
| ninja-vless | 1.0 | 1 | 0 | 1 |
| ermaozi | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 34034 | yes | 6.99 | 0 |
| SoliSpirit-all | 10500 | yes | 4.76 | 0 |
| Surfboard-tg-mixed | 7756 | yes | 5.33 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.12 | 0 |
| barry-far-vless | 5941 | yes | 2.95 | 0 |
| Surfboard-tg-vless | 5729 | yes | 3.97 | 0 |
| 10ium-ScrapeCategorize-Vless | 5005 | yes | 2.71 | 0 |
| mahdibland-V2RayAggregator | 4444 | yes | 1.11 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 3.01 | 0 |
| DeltaKronecker-all | 2709 | yes | 6.11 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| anytls | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 114 |
| geo | 42 |
| cn-block | 20 |
| 204 | 15 |
| speed | 12 |
