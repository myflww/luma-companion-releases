# 数据与隐私说明

[项目首页](../README.md) · [使用手册](USER_GUIDE.zh-CN.md) · [支持](../SUPPORT.md) · [安全报告](../SECURITY.md)

本说明介绍 Luma 的主要数据流程。**具体处理以所用版本、连接服务与随附政策为准。** 选择模型或启用相关功能前，请同时阅读对应服务的条款与数据处理说明。

## 本机保存的内容

角色聊天消息、聊天摘要和关系状态保存在本机。**这些内容当前以明文保存，未在应用层加密**，不能将“保存在本机”理解为“只有你能够解密”。能够访问相关本机文件或备份的人，可能读取这些内容；操作系统的磁盘保护也不能代替应用本身的数据加密说明。

任务记录、创作资料与工作文件按各自模块处理，其数据范围、保留方式和删除入口应分别核对。

## 使用模型时会发生什么

当你使用角色对话时，为生成回复，相关消息、角色设定和检索到的相关记忆可能被发送给你选择的模型服务。服务提供者对请求的接收、处理和保留，受其自身条款、账号设置与实际接口行为影响。模型调用可能产生费用；有可用模型名称不表示已包含额度或免费服务。

正式工作流程与角色聊天上下文分开。**工作任务不读取角色聊天记忆**；这不表示工作请求完全离线，也不表示工作中没有数据发送。任务输入、你选择的文件和获准使用的工具可能形成模型请求或工具操作，发送和访问范围取决于实际任务与权限。

创作功能是否向外部模型发送素材，取决于你启动的功能和所选模型。上传含个人、业务或第三方内容的资料前，应先核对该请求需要的范围与服务条件。

## 屏幕陪伴

屏幕陪伴由用户开启。启用后，功能会把**整屏截图**发送给已绑定、支持视觉的模型，供其理解屏幕内容；发送范围不只限于 Luma 窗口。当前该功能截图不落盘保存。

不落盘不等于不对外发送，也不等于模型服务一定不保留请求。整屏可能包括其他应用、消息、姓名、私人文件或凭据。开启前应先整理屏幕内容；不希望继续发送时关闭该功能。未来版本如改变截图范围、频率、保存或服务方式，应同步更新说明。

## 备份的边界

创作群的聊天备份不包含工作文件正文。**聊天导出或聊天备份不能替代工作文件备份**；完整恢复需分别保存需要的文件与数据，并在使用前核对备份内容。

开发者将筛选后的作者源码同步到私有 GitHub 仓库。这是源码版本管理，**不是用户数据备份服务**，不代表角色聊天、数据库、素材、工作文件或你的电脑内容已备份到 GitHub。公开项目仓库也不接收这些资料。

## 反馈与联系

GitHub Issue 是公开内容。提交问题前应移除密钥、密码、会话令牌、私人对话、完整数据库、私人链接和无关个人信息；截图还需检查整屏中的其他应用。

普通反馈见 [支持说明](../SUPPORT.md)。涉及数据泄露或安全问题，请按 [安全报告](../SECURITY.md) 私下联系 **[1805680363@qq.com](mailto:1805680363@qq.com)**，先说明情况，再确定必要资料。

## 版本与服务差异

所用版本及随附政策应说明具体的数据类别、用途、外部接收方、保留与删除方式、用户操作入口、账号及云端流程和反馈资料处理。连接其他服务时，请同时核对其实际权限、账号设置和保留规则；不能由“本机保存”推导所有请求都离线，也不能由一次聊天备份推导所有工作文件都已备份。

## English

This overview describes Luma's main data flows. The version in use, connected services and accompanying policies determine the specific handling. Review provider terms and data practices when selecting a model or enabling a feature.

- Character conversations, summaries and relationship state are stored locally in **plaintext without application-level encryption**.
- Character requests may send messages, character settings and relevant retrieved memories to the selected model provider. Provider terms and account settings govern its handling; calls may cost money.
- Work tasks do **not** read character-chat memories. They may still send task input and authorized file or tool context to a model or use authorized tools.
- User-enabled screen companionship sends **full-screen screenshots** to its bound vision-capable model. These screenshots are not saved to disk by the feature; this does not mean they are not transmitted or that the provider never retains them.
- Creative-group chat backups do not include work-file bodies. Chat backups do not replace file backups.
- The developer's private GitHub source repository is version control, **not a user-data backup service**. Public Issues must not contain secrets, private conversations or unredacted screenshots.

Consult the version's accompanying policies for specific data categories, providers, retention, deletion and user controls. For sensitive concerns, use [Security reporting](../SECURITY.md).
