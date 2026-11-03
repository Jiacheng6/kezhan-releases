# 课泊 · Windows 下载

当前稳定版：**0.7.1**。Windows 10 / 11，64 位；自带网页引擎，无需另开浏览器。

| 版本 | 下载 |
| --- | --- |
| 安装版 | [Kebo-0.7.1-Setup.exe](https://github.com/Jiacheng6/kezhan-releases/releases/download/v0.7.1/Kebo-0.7.1-Setup.exe) |
| 免安装 ZIP | [Kebo-0.7.1-win-x64.zip](https://github.com/Jiacheng6/kezhan-releases/releases/download/v0.7.1/Kebo-0.7.1-win-x64.zip) |

[国内下载](https://cnb.cool/kezhan-app/kezhan-releases/-/releases/tag/latest) · [最新发布](https://github.com/Jiacheng6/kezhan-releases/releases/latest) · [更新说明](docs/releases/0.7.1.md) · [源码与使用说明](https://github.com/Jiacheng6/kezhan)

免安装版请完整解压后运行“课泊.exe”。


- 修复豆包人工验证后的续传请求被误判为新提问，导致已有回答无法读取的问题。
- 修复仅引号辅助字体加载失败时，题干可读却仍被禁止自动回填的问题；保留题干字体异常保护。
- 细化回答关联失败的日志原因，便于排查。

已验证真实豆包单题回答恢复读取，以及截图、关联和失败题重试的回归测试。连续多题课程流程尚未完成真实验收，本版供继续实测。


支持学习通、智慧树、U校园 AI 版的课程管理，具体任务能力以平台和软件设置为准。AI 网页额度和人工验证以平台提示为准。

更新默认优先连接国内 CNB，失败后尝试 GitHub，也可导入安装包与配套 release-manifest.json。旧版无法联网更新时，可下载新版安装包覆盖升级。免安装版通过内置安装入口更新会切换为安装版。

发布包不包含个人账号、课程数据、Cookie 或测试记录。下载仓库地址保持兼容，避免中断旧版更新。
