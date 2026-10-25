# 版本发行核对清单

[项目首页](../README.md) · [获取 Luma](../DOWNLOADS.md) · [许可说明](../LICENSING.md)

每个发行版本使用同一组核对项，将功能说明、文件身份、数据处理、许可与实际交付内容保持一致。完成情况以对应版本的记录为准。

## 产品与说明

- [ ] 固定发行版本、文件身份与该版本实际包含的功能。
- [ ] 说明功能范围、适用条件与已知问题。
- [ ] 验证新用户从获取、安装、首次配置到核心操作的完整流程。
- [ ] 按实际支持的平台与架构验证，公布真实系统要求；不将开发机配置写成最低要求。
- [ ] 手册中的菜单、权限、模型配置、费用提示、错误恢复与该版本一致。
- [ ] 区分角色宣传插画与实机截图，清除截图中的隐私内容。

## 数据、权限与安全

- [ ] 复核聊天、摘要、记忆、关系状态、任务和创作资料的存储与发送范围。
- [ ] 说明本机明文保存现状，以及外部模型请求、服务条件与可能费用。
- [ ] 对屏幕陪伴的用户开启、整屏发送、关闭及截图处理完成验证并说明。
- [ ] 验证工具权限、敏感操作提示、任务停止与异常恢复，保留用户未完成的工作。
- [ ] 按不同数据类型验证导出、删除、备份及恢复；聊天备份不冒充工作文件备份。
- [ ] 审查打包内容、示例、日志和公开文档，排除密钥、用户数据、私人地址与内部服务信息。
- [ ] 确认安全问题联系渠道与实际可承担的维护安排。

## 使用许可与第三方组件

- [ ] 确定适用于该版本的第一方使用许可，明确提供者、使用范围、费用条件、更新和支持等内容。
- [ ] 按实际发行闭包登记组件、版本、来源、修改、版权和完整 LICENSE/NOTICE。
- [ ] 单独核对 AGPL、LGPL、Commons Clause 等实际适用条件及需要的源码、构建资料或声明。
- [ ] 如包含 SillyTavern 及其适配，完成对应源码与许可义务安排；第一方私有维护不替代这些安排。
- [ ] 检查每项实际随包的人物、场景、字体、声音、模型、游戏及其他资源的公开分发权利。
- [ ] 软件 UI、包内文件和公开页面提供相互一致、用户可访问的许可与隐私说明。

组件范围和许可线索见 [第三方组件概览](THIRD_PARTY_NOTICES.md)，具体内容与对应制品核对。

## 文件与交付

- [ ] 在干净测试环境验证安装、启动、必要运行库、卸载与数据保留方式。
- [ ] 完成目标平台所需的签名、信任与完整性检查，准确说明剩余限制。
- [ ] 验证更新和回滚不会丢失用户资料；未实现自动升级时明确说明。
- [ ] 为每个正式文件记录平台、架构、文件名、大小和 SHA-256；校验值来自最终文件。
- [ ] 一并准备变更说明、适用许可、第三方声明、已知限制和支持方式。
- [ ] 获得明确的发行决定后，再创建正式 Release 并上传经核对的文件。
- [ ] 从对外入口回读下载文件与校验值，确认链接、版本和包内内容一致。

下载入口、版本说明和最终文件校验信息在 [下载与版本](../DOWNLOADS.md) 中统一组织。

## English

Each release uses this checklist to align user journeys, supported platforms, manuals and limitations, permissions, privacy, backup and recovery, first-party terms, component-specific notices and source obligations, asset rights, installation and updates, final-file checksums and the release decision. Completion is recorded for the corresponding version. Download links and version details are organized through [Downloads and versions](../DOWNLOADS.md).
