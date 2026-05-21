# Telegram 过滤词

自用 TG 群组/频道过滤词库，适用于 NagramX 等客户端的自动过滤功能。

## 文件说明

`filters/` 目录下每个文件是一个完整的正则表达式（单行），可直接用于屏蔽规则：

| 文件 | 说明 |
|------|------|
| `ads_combined.txt` | 广告推广（电商、返利、营销话术等） |
| `adult_combined.txt` | 成人色情内容 |
| `gambling_combined.txt` | 赌博博彩 |
| `scam_combined.txt` | 诈骗（杀猪盘、传销、贷款、刷单、假冒官方等） |
| `vpn_combined.txt` | VPN/翻墙/机场推广 |
| `all_combined.txt` | 以上全部类别的合集 |

## 使用方式

在 NagramX 等客户端中将文件内容粘贴到过滤规则输入框即可。每个文件已包含 `(?i)` 不区分大小写标记。
