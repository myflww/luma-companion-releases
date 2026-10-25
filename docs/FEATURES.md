# 功能与使用条件 / Features and Requirements

**更新日期 / Updated: 2026-10-25**

[中文手册](USER_GUIDE.zh-CN.md) · [English guide](USER_GUIDE.en.md) · [下载页面 / Downloads](../DOWNLOADS.md)

Luma 将工作任务、角色交流与桌面陪伴连接起来。界面和可用能力以所用版本及服务状态为准，获取版本请见[下载页面](../DOWNLOADS.md)。

Luma connects work tasks, character conversations, and desktop companionship. The interface and available capabilities depend on your version and service availability. See the download page for version access.

| 功能 / Feature | 使用入口 / Where to find it | 使用条件与说明 / Requirements and notes |
| --- | --- | --- |
| 注册、登录与恢复 / Registration, sign-in, recovery | 启动登录页 / Startup sign-in screen | 账号服务可用时按页面注册或登录。登录账号与展示用户名分开；注册后保存只显示一次的恢复码。 / Follow the screen when the account service is available. Your login account and display name are separate. Save the recovery code shown once after registration. |
| 模型连接 / Model connections | 用户菜单 → 设置 → 模型 / User menu → Settings → Models | 使用你有权访问的模型 API 与凭据。密钥已配置、目录已同步与模型调用成功是不同状态；提供方可能计费。 / Use a model API and credentials you are entitled to access. Stored keys, catalog sync, and successful inference are different states. Provider charges may apply. |
| 工作区与会话 / Workspaces and sessions | 切换工作台 → 纯净工作台 / Switch workbench → Workspace | 选择或添加工作文件夹，创建会话，选择模型与适当权限。任务需要文件、模型和服务条件满足。 / Choose or add a work folder, create a session, and select a model and appropriate permissions. Required files, models, and services must be available. |
| 工作台侧边面板 / Workspace side panels | 打开右侧面板 / Open side panel | 变更、终端、浏览器、文件、侧边聊天、结果。文本和常见图片可预览；终端主要用于文本交互，关闭终端标签会结束对应终端。 / Changes, Terminal, Browser, Files, Side chat, and Results. Preview text and common images. The terminal primarily supports text interaction; closing its tab ends that terminal. |
| 角色聊天 / Character conversations | 办公室员工列表或消息 / Office employee list or Messages | 选择角色模型，阅读聊天记忆说明并确认模型输入与费用。普通聊天不直接发送图片或文件；附件放入工作草案。 / Select a character model and acknowledge chat memory, model input, and costs. Ordinary chat does not directly send images or files; add attachments to a work draft. |
| 工作草案与派发 / Work drafts and dispatch | 角色聊天 → 消息用途 → 工作任务；或更多 → 拟定工作任务 / Character chat → Message purpose → Work task; or More → Draft work task | 核对任务、模型与附件，勾选模型输入及费用确认后派发。草案准备与提交执行是两个步骤。 / Review the task, model, and attachments, then acknowledge model input and costs before confirming. Preparing a draft and dispatching work are separate steps. |
| 权限、审批与监督 / Permissions, approvals, supervision | 任务权限选择；原任务；角色页监督任务 / Task permission selector; original task; character-page supervision | 只读、工作区可写、完全访问、自定义按所需范围选择。完全访问有单独风险确认。等待审批或回答时处理原任务；状态不明先重新读取，避免重复提交。 / Choose Read only, Workspace write, Full access, or Custom according to scope. Full access has a separate risk acknowledgement. Handle approvals and questions in the original task; reread uncertain records before submitting again. |
| 办公室与桌宠 / Office and desktop pets | 切换工作台 → 办公室；员工抽屉；设置 → 角色表现 / Switch workbench → Office; employee drawer; Settings → Character presentation | 员工抽屉可外派或召回角色，并调整桌面大小。显示、声音与登录后启动依赖相应资源和系统条件。 / Dispatch or recall characters and adjust desktop size in the employee drawer. Display, sound, and launch-at-sign-in depend on the relevant resources and system support. |
| 屏幕陪伴 / Screen companionship | 设置 → 角色表现 → 屏幕陪伴 / Settings → Character presentation → Screen companionship | 需视觉模型、系统权限与明确开启。整屏发送给当前角色绑定模型，可能计费；截图不保存到磁盘。 / Requires a vision-capable model, system permission, and explicit enablement. Sends the whole screen to the character's bound model and may incur charges. Screenshots are not saved to disk. |
| 画布 / Canvas | 办公室导航 → 画布；或更多 → 画布 / Office navigation → Canvas; or More → Canvas | 可从画布进入模型设置，加载失败时可重新加载。模型操作需要对应连接与资源，具体工具和格式以所用版本为准。 / Open model settings from Canvas, or reload after a loading failure. Model operations require the relevant connections and resources. Specific tools and formats depend on your version. |
| 万象剧场 / Wanxiang Theater | 办公室导航 → 万象剧场；或更多 / Office navigation → Wanxiang Theater; or More | 故事体验使用相应模型连接及角色或故事资源。具体工具与内容以所用版本和服务状态为准。 / Story experiences use the relevant model connection and character or story resources. Specific tools and content depend on your version and service availability. |
| AI 创作群聊天备份 / AI creation-group chat backups | 创作群管理 → 导出聊天备份；消息添加菜单 → 导入创作群聊天备份 / Creation-group management → Export chat backup; Messages add menu → Import creation-group chat backup | 聊天备份不含工作文件正文。换设备需另行复制工作文件并重新关联；导入不会自动启动 AI 回复或任务。 / Chat backups exclude work-file contents. Copy and reassociate work files separately on another device. Importing does not automatically start AI replies or tasks. |
| 收藏、娱乐、商店与社区 / Collection, Entertainment, Store, Community | 办公室导航或更多 / Office navigation or More | 内容由账号、资源与服务条件决定。按页面的可用状态和确认信息操作。 / Content depends on account access, resources, and services. Follow each page's availability and confirmation details. |
| 个人资料与退出 / Profile and sign-out | 用户菜单 → 头像与头像框、账号与同步、退出登录 / User menu → Avatar and frame, Account and sync, Sign out | 展示用户名可修改，修改不会改变登录账号。退出登录保留本机作品；完全退出使用“退出 Luma”。 / You can change your display name without changing the login account. Sign-out retains local work; use Quit Luma to exit the application completely. |

## 数据与使用说明 / Data and Usage Notes

角色聊天、摘要和关系成长记录当前明文保存在本机，尚未加密。发送会向所选模型提供相关输入；正式工作任务不读取角色聊天记忆。本机保存不等于内容不会发送给模型。GitHub 私有源码同步用于保存开发代码，不代替聊天、素材、模型或工作文件备份。

Character chats, summaries, and relationship-growth records currently use local plaintext storage and are not yet encrypted. Sending supplies relevant input to the selected model; formal work tasks do not read character-chat memory. Local storage does not mean content is never sent to a model. Private GitHub source sync stores development code and does not replace backups of chats, media, models, or work files.

Luma 第一方源码保持私有；第三方组件、模型、素材与服务受各自许可或条款约束。参阅[许可说明 / Licensing](../LICENSING.md)。需要帮助时，请按[支持说明 / Support](../SUPPORT.md)反馈，并移除密钥、恢复码及私人内容。

Luma's first-party source remains private. Third-party components, models, artwork, and services retain their own licenses or terms. For help, follow the support instructions and remove keys, recovery codes, and private content from your report.
