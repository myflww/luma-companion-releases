# 常见问题 / FAQ

[项目首页](../README.md) · [使用手册](USER_GUIDE.zh-CN.md) · [反馈](../SUPPORT.md)

## 从哪里获取软件与账号说明？

获取方式、安装文件和版本说明统一见 [获取 Luma](../DOWNLOADS.md) 与 Releases。账号按所用版本的登录页与服务提示操作；Luma 账号和模型服务账号分别管理。

## 现在的宣传图是软件截图吗？

不是。四张宣传图是重新绘制的卡通角色群像，用来表达工作、创作与陪伴的气氛。它们以当前角色造型作为身份参考完整重绘，没有剪贴原始立绘或使用私人聊天截图。操作界面和步骤请阅读用户手册。

## Luma 登录账号和模型账号是一回事吗？

不是。Luma 账号用于进入相应产品服务；模型 API 由提供方管理。你需要具备相应模型的访问条件，调用可能计费。保存了 API 密钥或同步到模型目录，不等于真实调用一定成功。

## 和角色聊天就会自动执行工作吗？

普通聊天和工作任务分开处理。要工作时先拟定任务草案，核对内容、模型、附件和费用确认，再明确提交。角色普通聊天当前不直接接收文件附件，工作文件应放入任务草案。

## 任务为什么停在等待状态？

先查看是否在等待审批、回答、模型响应或预约时段。打开原任务，阅读实际提示，再决定批准、拒绝或补充。更大的权限不等于更好的结果，初次使用可从只读或明确需要的工作区可写开始。

## 所有信息都只留在本地吗？

不能这样概括。角色聊天、摘要与关系记录目前以明文保存在本机；发送时相关消息、角色设定和记忆可能交给所选模型。主动开启屏幕陪伴后，整屏画面会发送给绑定且支持视觉的模型，可能计费；该截图不落盘。详见 [数据流说明](PRIVACY.md)。

## GitHub 同步会减少电脑的内存占用吗？

不会直接减少运行内存 RAM。Luma、浏览器、模型或其他进程运行时需要的内存，取决于它们自己的加载与运行方式。

GitHub 主要保存源码版本。它也不会自动删除本地文件；本地同步副本和 Git 历史还会占用磁盘。磁盘空间可以通过核对后清理可重建的缓存、构建副本和过期备份来回收，但这与运行内存是两回事。

## 源码上 GitHub 后，可以删除本地素材和聊天吗？

不能把源码同步当成这些资料的备份。当前快照排除了大型素材、模型、原生游戏归档、运行时、聊天记录、数据库和完整安装恢复资料。清理前仍需要独立核对实际依赖、可恢复来源和用户数据备份。

## 聊天备份包括我的工作文件吗？

创作群的聊天备份包含群聊记录与 AI 名单，不包含工作文件正文。工作文件要单独复制，在新设备上重新关联。退出登录也不等于删除本机作品和数据。

## 是否免费、开源或需要激活码？

第一方应用源码私有维护，第三方组件按各自许可证处理。免费或收费条件、授权期限、使用范围及激活安排，以所用版本的使用许可和发行说明为准。请阅读 [许可说明](../LICENSING.md)。

## 画布、剧场或某个服务打不开怎么办？

先看具体版本和界面提示；入口存在不代表所有服务可用。画布可尝试“重新加载画布”，并确认模型连接和服务状态。仍有问题时按 [支持说明](../SUPPORT.md) 提交最小复现信息。

## English summary

- **Getting Luma:** use the download page and Releases for installation files and version notes. Follow the account-service prompts in your version.
- **Artwork:** the four promotional images are newly drawn cute cartoon ensembles, not application screenshots.
- **Accounts and cost:** a Luma account is separate from a model-provider account. API access may incur provider charges; saved settings do not guarantee a successful call.
- **Chat and work:** work begins through an explicit reviewed task draft. Ordinary character chat currently does not accept file attachments directly.
- **Waiting tasks:** inspect the actual approval, question, scheduling, or model status in the original task.
- **Data:** local storage does not mean every operation stays local. Selected inputs may be sent to a model; screen companionship can send the entire screen when enabled.
- **RAM and disk:** GitHub source versioning does not reduce running memory or automatically remove local files. Local Git copies consume some disk space too.
- **Backups:** source snapshots are not backups of chat records, models, artwork, native archives, runtime resources, or all recovery inputs. Group-chat exports do not include work-file contents.
- **License and activation:** first-party source is private. Usage, pricing, duration, and activation follow the applicable version's license and release notes. Third-party licenses remain applicable.
- **Unavailable modules:** follow the actual build's status and report a minimal, sanitized reproduction through [Support](../SUPPORT.md).
