# AutoNodes 每日报告

生成时间：2026-10-31 05:57:37

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/111 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 4/89 |
| 原始节点数 | 80805 |
| 去重后节点数 | 26598 |
| TCP 可达数 | 3000 |
| 真测通过数 | 617 |
| verified 输出数 | 95 |
| global 输出数 | 300 |
| all 输出数 | 26598 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 30.5 |
| fetch | 10.9 |
| generate | 8.9 |
| geo | 1.3 |
| probe | 69.8 |
| real_test | 93.6 |
| tcp | 80.0 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 93 | 92 | 1 | 98.9% |
| hysteria2 | 15 | 14 | 1 | 93.3% |
| shadowsocks | 166 | 155 | 11 | 93.4% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 182 | 173 | 9 | 95.1% |
| vless | 274 | 183 | 91 | 66.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 59 |
| geo:ClientOSError | 32 |
| 204:TimeoutError | 6 |
| cn-block:ClientOSError | 5 |
| speed:ClientOSError | 4 |
| cn-block:TimeoutError | 3 |
| 204:ClientOSError | 2 |
| speed:TimeoutError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6031 |
| ConnectionRefusedError | 949 |
| OSError | 245 |
| gaierror | 168 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 1.0 | prefer | 94 | 0.989 | 622 |
| Au1rxx-base64 | 0.952 | prefer | 354 | 0.884 | 1751 |
| mheidari-all | 0.903 | prefer | 111 | 0.829 | 14594 |
| Surfboard-tg-mixed | 0.772 | prefer | 170 | 0.694 | 7827 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4960 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2724 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10524 |

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
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 518 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 409 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 404 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 287 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 265 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 264 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 256 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 234 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 229 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 153 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.694 | 118 | 52 | 170 |
| mheidari-all | 0.829 | 92 | 19 | 111 |
| Au1rxx-base64 | 0.884 | 313 | 41 | 354 |
| ermaozi | 0.989 | 93 | 1 | 94 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14594 | yes | 3.09 | 0 |
| SoliSpirit-all | 10524 | yes | 1.78 | 0 |
| Surfboard-tg-mixed | 7827 | yes | 2.2 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.16 | 0 |
| barry-far-vless | 5895 | yes | 0.41 | 0 |
| Surfboard-tg-vless | 5680 | yes | 1.92 | 0 |
| 10ium-ScrapeCategorize-Vless | 4960 | yes | 0.74 | 0 |
| mahdibland-V2RayAggregator | 4635 | yes | 1.76 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 0.63 | 0 |
| DeltaKronecker-all | 2724 | yes | 1.97 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 59 |
| geo | 32 |
| 204 | 8 |
| cn-block | 8 |
| speed | 6 |
