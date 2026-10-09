# rules-public

个人自用规则集，整理自 [blackmatrix7/ios_rule_script](https://github.com/blackmatrix7/ios_rule_script)（2026-10-09）。

## 目录结构

```
rules/
  surge/         80 个 · Surge / Loon 格式（.list）
    ai/           9 个 · AI 服务
    去广告/       2 个 · 广告过滤
    国内社交/     1 个 · 国内社交应用
    国外社交/    19 个 · 国外社交应用
    微软服务/     4 个 · 微软相关服务
    游戏平台/    23 个 · 游戏平台
    苹果服务/     1 个 · 苹果相关服务
    视频媒体/    17 个 · 视频流媒体
    谷歌服务/     2 个 · 谷歌相关服务
    通用代理/     2 个 · 通用代理 / 直连
  clash/         80 个 · Clash / Stash 格式（.yaml）
    （分类同上）
```

## 使用方法

Surge / Loon 直接引用 `.list` 文件：

```
https://raw.githubusercontent.com/baynidn/rules-public/main/rules/surge/去广告/Advertising.list
```

Clash / Stash 引用 `.yaml` 文件：

```
https://raw.githubusercontent.com/baynidn/rules-public/main/rules/clash/去广告/Advertising.yaml
```

## 更新

每日自动从上游同步。
