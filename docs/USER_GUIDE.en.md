# Luma Companion User Guide

**Updated: October 25, 2026**

[简体中文](USER_GUIDE.zh-CN.md) · [Quick start](QUICKSTART.en.md) · [Features and requirements](FEATURES.md) · [Downloads](../DOWNLOADS.md)

Luma brings file-based tasks, conversations with AI characters, and desktop companionship into one application. Use the Workspace for focused work, or meet a character in the Office, prepare a work draft, and review it before submitting it to a model.

The interface and available capabilities depend on your version and service availability. See the [download page](../DOWNLOADS.md) for version access. Chinese interface labels are included where they help identify the controls precisely.

## 1. Before you begin

Version access and related instructions are listed on the [download page](../DOWNLOADS.md). Follow the instructions that correspond to the version you use.

Model features generally require a model service you are entitled to use and its API credentials. **Your Luma account and your model-provider account have different purposes.** One signs you into Luma; the other provides model access. Model calls may incur provider charges according to your account and plan. Luma does not promise unlimited or permanently free inference.

For your first task, prepare a dedicated folder containing a few non-sensitive example files. Start with a narrow request, inspect the result, and then expand your workflow.

## 2. Register, sign in, and keep your recovery code

When the account service is available, follow the startup screen to register or sign in. If an account-service connection is required, use the service instructions for your version. If the service is temporarily unavailable, wait for access to return; do not submit your password to an unfamiliar address.

To register:

1. Choose Register (`注册`) and enter a login account, password, and password confirmation.
2. The login account must be unique, contain 3–32 characters, start with an English letter, and otherwise use letters, numbers, or underscores. The password guidance is 15–128 characters, including Chinese text and spaces.
3. Select Register account (`注册账号`). After successful registration, save the recovery code somewhere only you can access. It is shown once.
4. Check “I have safely saved the recovery code” (`我已妥善保存恢复码`), then select “Saved, enter Luma” (`保存好了，进入 Luma`).

Existing users can enter their credentials and choose Sign in to Luma (`登录 Luma`). Remembered sign-in is intended for a computer you trust. Your public display name is separate from the unique login account: changing a display name does not change how you sign in.

An existing email-based account can use `已有邮箱账号` to verify the original email and set an account and password. Forgot password (`忘记密码`) uses your saved recovery code. A successful reset generates a replacement code and invalidates the previous one. Never publish passwords, verification codes, or recovery codes in issues, screenshots, or support messages.

## 3. Connect a model and understand charges

Open the user menu at the lower left, then Settings → Models (`设置 → 模型`):

1. Select Connect model API (`连接大模型 API`) and choose your provider.
2. Enter your API key and any required API address or model configuration. When editing an existing connection, follow the field guidance for retaining stored credentials.
3. For another compatible service, choose Custom API address (`自定义 API 地址`) and verify its protocol, address, provider identifier, and model IDs.
4. Save the connection, then choose an available model in the relevant conversation or task.

The catalog may combine built-in entries, provider discovery, and manual configuration. “API key configured” confirms stored credentials; “Directory synced” confirms a catalog read. **Neither proves that a model request has succeeded.** Availability also depends on protocol support, provider permissions, account balance, networking, and model capabilities.

Only declare image input when the provider confirms it. A model name alone does not establish vision support. Chat, tasks, screen observation, and media tools can have different model requirements. Keep keys out of chat prompts, public repositories, logs, and bug reports.

## 4. Complete a first task in the Workspace

Open Switch workbench (`切换工作台`) from the Luma menu at the upper left and choose Workspace (`纯净工作台`). Select a workspace or use Add workspace (`添加工作区`) to choose your example folder. Create a new session within it.

A workspace is the main file context for that task. A small dedicated folder is easier to review than an entire personal document collection. Describe the goal, inputs, expected output, and limits. For example:

> Read the three example notes in this workspace and create a Markdown checklist. Preserve the original notes and mark any decisions that need my confirmation.

Choose an available model and the appropriate permission mode, then send the request. Read any follow-up questions or approval requests before responding. A completed status should still be followed by opening the output and checking its content and saved location.

Open side panel (`打开右侧面板`) provides Changes, Terminal, Browser, Files, Side chat, and Results. Files can browse the workspace and preview text and common images. Changes helps review modifications. Results lists outputs and references; a reference link is not necessarily a downloaded local file.

Use the terminal for commands you deliberately intend to run. Switching tabs preserves the terminal; closing its tab ends that terminal. It is primarily a text interaction surface, so do not assume every full-screen terminal application is supported.

## 5. Talk to a character and prepare work

Expand the employee list in the Office and select a character, or open the relevant conversation in Messages (`消息`). On first use, read the chat-memory notice and select Confirm and continue chatting (`确认并继续聊天`). Use More → Select model (`更多 → 选择模型`) to review the character's bound model and the associated input and cost acknowledgement.

The Message purpose (`消息用途`) control offers Auto, Chat, and Work task (`自动`, `聊天`, `工作任务`). For file work, explicitly choose Work task or use More → Draft work task (`更多 → 拟定工作任务`). A normal conversation is not automatically a submitted work order.

To submit work:

1. Describe the goal and select Draft task (`拟定任务`).
2. Review the task name and instructions, then choose its work model.
3. Drag images or files into Work attachments (`工作附件`). Check the filenames and remove anything unnecessary.
4. Check the acknowledgement permitting the selected model to receive the work input and confirming awareness of possible charges.
5. Select Confirm task (`确认任务`) and read the reception status. If uncertain, use Read task records again (`重新读取任务记录`) rather than repeatedly submitting.

Drafting prepares the request; confirmation dispatches it. Ordinary character chat currently does not send image or file attachments directly. Add them to a work draft instead. Newly dispatched work permits writes in the employee's workspace; broader access needs separate confirmation.

A new task outside working hours may be scheduled for the next work period, as shown by the confirmation screen. Existing work is not automatically cancelled because the Office is off duty, a character moves to the desktop, or you switch pages. Inspect the original task instead of creating another request to guess its progress.

## 6. Permissions, approvals, and supervision

Permission choices include Read only (`只读`), Workspace write (`工作区可写`), Full access (`完全访问`), and Custom (`自定义`). Read only suits inspection. Workspace write allows creating and modifying files inside the workspace. Start with the scope your task actually needs.

Full access reduces step-by-step confirmation and permits more sensitive operations, file changes, or external commands. It has a separate risk acknowledgement. It should not be a required first-use step.

When a task is waiting for approval or an answer, open the original task and review the proposed action, target, and consequences. Character pages provide Supervise task (`监督任务`); the Workspace also lets you inspect the task. Approval of an individual step does not replace checking the final result.

If delivery or status is uncertain, read the existing record again. A connection failure does not prove that a request never reached a model. Repeated submission can duplicate work or charges. Keep the record and consult [support](../SUPPORT.md) if the state cannot be resolved.

## 7. Office characters and desktop companionship

Return through Switch workbench → Office (`办公室`). In the employee drawer, Send to desktop (`外派到桌面`) moves the character to the desktop; Recall to app (`召回应用`) brings them back. Display adjustments → Desktop size (`显示与调整 → 桌面大小`) changes the size.

The user menu's Settings → Character presentation (`设置 → 角色表现`) includes the default conversation character, edge appearance, screen companionship, temporary cache, and display/audio settings. Current controls include enabling desktop pets, playing character sounds, and launching pets after computer sign-in. Available controls may vary with the build and resources.

**Screen companionship sends the whole screen to the speaking character's currently bound, vision-capable model and may incur charges. Screenshots are not saved to disk.** Read the disclosure before enabling it and follow any application and system permission prompts. Close content you do not want sent to a model. Ordinary character chat does not imply that screen observation is enabled.

Temporary cache cleanup is not deletion of formal chat history. Hiding or dispatching a character is not deletion of their conversations and does not stop their tasks.

## 8. Canvas, Wanxiang Theater, and other destinations

The Office navigation includes Canvas (`画布`) and Wanxiang Theater (`万象剧场`). If an entry is absent from the frequent-use rail, open More (`更多`), find it there, and optionally pin it.

Canvas provides a creation-space entry point. Its model-management action returns to the application's model settings, and a failed load offers Reload canvas (`重新加载画布`). Wanxiang Theater is a separate story-experience destination.

Available tools, models, and import formats depend on the version you use. Check their model and resource requirements before proceeding. Collection, Store, Community, and Entertainment also depend on service availability, account access, and resources. Follow any unavailable-feature messages. Review the specific content and confirmation details before making a purchase or another external change.

## 9. Local data, privacy, and backups

Current character chats, summaries, and relationship-growth records are stored locally in plaintext and are not yet encrypted. They support character conversations; formal work tasks do not read character-chat memory. Sending a chat supplies the selected model with the character setting, relevant memory, and message. Local storage does not mean the content is never transmitted to a model.

AI creation-group conversations are stored locally. Their group-management screen offers Export chat backup (`导出聊天备份`). On another device, the Messages add menu provides Import creation-group chat backup (`导入创作群聊天备份`). **A chat backup does not contain work-file contents.** Copy those files separately and associate them again on the new device. Importing a backup does not automatically start AI replies or tasks.

Work outputs, conversations, model settings, and application installers are different backup concerns. A private GitHub source repository stores development code; it is not an application-data backup or a complete computer backup. Do not delete local conversations, media, models, work files, or unique recovery materials because source code was pushed. Archiving chat also does not mean its disk space has been released.

## 10. Sign out, quit, and request help

Sign out (`退出登录`) ends the current account state while retaining local work. Closing the main window, closing all pets, and Quit Luma (`退出 Luma`) are separate actions. To exit completely, use Quit Luma in the application or menu-bar menu. Check running work and preserve necessary content first; a closed window does not mean a task finished.

For an unavailable model, review the selection, configuration, provider access, and network. For uncertain task state, reread the original record first. A useful support report includes the version, steps, expected outcome, actual outcome, and a redacted error screenshot. Never send keys, passwords, recovery codes, full private chats, or sensitive files. See [support instructions](../SUPPORT.md).

Luma's first-party source remains private. See the [licensing information](../LICENSING.md) for usage and distribution conditions. Third-party components, models, artwork, and services have their own licenses or terms. This guide does not grant permission to publish, modify, or redistribute the source code.
