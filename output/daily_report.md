# AutoNodes 每日报告

生成时间：2026-11-01 22:12:44

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/111 |
| 清理建议：禁用/降权 | 17/0 |
| 清理建议：优先/观察 | 5/89 |
| 原始节点数 | 82970 |
| 去重后节点数 | 26794 |
| TCP 可达数 | 3000 |
| 真测通过数 | 462 |
| verified 输出数 | 72 |
| global 输出数 | 300 |
| all 输出数 | 26794 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 24.0 |
| fetch | 10.0 |
| generate | 9.3 |
| geo | 1.3 |
| probe | 72.3 |
| real_test | 77.0 |
| tcp | 76.8 |
| write_verified | 0.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 46 | 45 | 1 | 97.8% |
| hysteria2 | 17 | 16 | 1 | 94.1% |
| shadowsocks | 173 | 163 | 10 | 94.2% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 114 | 110 | 4 | 96.5% |
| vless | 213 | 128 | 85 | 60.1% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 42 |
| geo:ClientOSError | 23 |
| 204:ProxyError | 10 |
| cn-block:ClientOSError | 9 |
| cn-block:TimeoutError | 6 |
| cn-block:ProxyError | 4 |
| 204:ClientOSError | 3 |
| 204:TimeoutError | 2 |
| geo:ProxyError | 2 |
| geo:TimeoutError | 1 |
| 204:ProxyConnectionError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5850 |
| ConnectionRefusedError | 955 |
| OSError | 238 |
| gaierror | 203 |
| SSRFBlocked | 6 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.951 | prefer | 27 | 0.963 | 499 |
| mheidari-all | 0.937 | prefer | 40 | 0.875 | 15206 |
| zhangkai | 0.923 | prefer | 19 | 1.0 | 43 |
| Au1rxx-base64 | 0.913 | prefer | 322 | 0.845 | 1751 |
| Surfboard-tg-mixed | 0.768 | prefer | 152 | 0.691 | 8273 |
| DeltaKronecker-all | 0.48 | observe | 4 | 1.0 | 3716 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4976 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10614 |

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
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 414 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 409 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 292 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 270 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 269 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 261 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 239 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 234 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 158 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 145 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.691 | 105 | 47 | 152 |
| Au1rxx-base64 | 0.845 | 272 | 50 | 322 |
| mheidari-all | 0.875 | 35 | 5 | 40 |
| ermaozi-get_subscribe | 0.963 | 26 | 1 | 27 |
| xiaoji235-airport-v2ray-all | 1.0 | 2 | 0 | 2 |
| DeltaKronecker-all | 1.0 | 4 | 0 | 4 |
| zhangkai | 1.0 | 19 | 0 | 19 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15206 | yes | 3.47 | 0 |
| SoliSpirit-all | 10614 | yes | 2.55 | 0 |
| Surfboard-tg-mixed | 8273 | yes | 2.9 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 0.92 | 0 |
| barry-far-vless | 5986 | yes | 0.17 | 0 |
| Surfboard-tg-vless | 5823 | yes | 2.2 | 0 |
| 10ium-ScrapeCategorize-Vless | 4976 | yes | 1.52 | 0 |
| mahdibland-V2RayAggregator | 4800 | yes | 1.28 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.45 | 0 |
| DeltaKronecker-all | 3716 | yes | 3.12 | 0 |

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
| test_one_timeout | 42 |
| geo | 26 |
| cn-block | 19 |
| 204 | 16 |
