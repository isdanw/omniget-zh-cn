# OmniGet 简体中文汉化（补译版）

OmniGet 是一款开源的跨平台下载工具（支持 1800+ 站点下载、网课平台内容提取与内置学习工具），原作者为 **OpenSelena**，原项目地址：https://github.com/OpenSelena/omniget （GPL-3.0）。

上游自带的简体中文语言包 `src/lib/i18n/zh.json` 并不完整：5760 个条目中约三分之一仍是英文，另有一部分回退成了葡萄牙语。本仓库是 **isdanw（张丹枫）** 对该语言包的补译成果：

- 补译 **3344 条**未翻译条目（英文／葡语回退 → 简体中文）
- 122 条按规则保留原文（品牌名、格式名、纯占位符、语言本名等）
- 全部条目通过占位符一致性校验（0 差错），键集与上游完全一致

## 下载汉化版安装包（macOS）

编译好的汉化版安装包在 **Releases** 里（不在上面的文件列表里）：

👉 [v0.14.0-zh-cn 发布页](https://github.com/isdanw/omniget-zh-cn/releases/tag/v0.14.0-zh-cn) — 下载 `OmniGet-0.14.0-zh-cn-mac-arm64.zip`（约 46MB，Apple Silicon），解压后把 OmniGet-汉化版.app 拖进「应用程序」即可。本包为自编译未签名版本，首次打开如被系统拦截，按发布页说明执行 `xattr -cr` 放行。

## 文件

- `zh.json` — 补译后的完整语言包，可直接替换上游 `src/lib/i18n/zh.json` 使用

本汉化成果已同步向上游提交 Pull Request。

## 许可

与原项目一致，GPL-3.0。原项目版权归 OpenSelena 所有；本仓库仅包含语言包的补译成果。
