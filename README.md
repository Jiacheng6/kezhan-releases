# 课泊 · Windows 下载

当前稳定版：**0.7.2**。Windows 10 / 11，64 位；自带网页引擎，无需另开浏览器。

| 版本 | 下载 |
| --- | --- |
| 安装版 | [Kebo-0.7.2-Setup.exe](https://github.com/Jiacheng6/kezhan-releases/releases/download/v0.7.2/Kebo-0.7.2-Setup.exe) |
| 免安装 ZIP | [Kebo-0.7.2-win-x64.zip](https://github.com/Jiacheng6/kezhan-releases/releases/download/v0.7.2/Kebo-0.7.2-win-x64.zip) |

[国内下载](https://cnb.cool/kezhan-app/kezhan-releases/-/releases/tag/latest) · [最新发布](https://github.com/Jiacheng6/kezhan-releases/releases/latest) · [更新说明](docs/releases/0.7.2.md) · [源码与使用说明](https://github.com/Jiacheng6/kezhan)

免安装版请完整解压后运行“课泊.exe”。


- 修复截图后卡在旧 AI 发送记录的问题，持续保存正式会话地址，并尝试找回原回答。
- 统一普通开始与待审续跑：失效会话最多重新提问一次，保留已答内容；内部自动重启不重复发送。
- 改善恢复阶段的日志提示，区分找回原回答和重新提问。

已完成真实豆包单题上传、发送及读取验证；千问、DeepSeek、API 通过模拟回归。连续多题真实流程仍待实测。


支持学习通、智慧树、U校园 AI 版的课程管理，具体任务能力以平台和软件设置为准。AI 网页额度和人工验证以平台提示为准。

更新默认优先连接国内 CNB，失败后尝试 GitHub，也可导入安装包与配套 release-manifest.json。旧版无法联网更新时，可下载新版安装包覆盖升级。免安装版通过内置安装入口更新会切换为安装版。

发布包不包含个人账号、课程数据、Cookie 或测试记录。下载仓库地址保持兼容，避免中断旧版更新。
