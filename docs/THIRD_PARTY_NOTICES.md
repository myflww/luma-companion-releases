# 第三方组件与许可概览

[项目首页](../README.md) · [第一方许可状态](../LICENSING.md) · [发行准备](RELEASE_READINESS.md)

本页介绍主要组件来源。**准确版本、完整依赖范围与许可文件以实际制品及其随附资料为准。**

Luma 使用第三方框架、工具与独立引擎。第一方源码私有维护，并不改变第三方的版权、许可条款或适用的源码提供义务。组件是否被打包、经过什么修改、以何种方式组合与提供，都需按实际发行版本核对。

## 已记录的主要组件

下列版本为工程登记信息；每个发行版本按实际制品维护准确组件清单，包括被编译进界面的代码和其他传递依赖。

| 组件 | 已登记版本 / 范围 | 来源与许可记录 | 正式发行时需核对 |
| --- | --- | --- | --- |
| [Electron](https://github.com/electron/electron) | 43.4.1 | MIT；内含 Chromium 等独立声明 | Electron 许可、Chromium notices 及其他随附组件。 |
| [React / React DOM](https://github.com/facebook/react) | 19.2.8 | MIT | 实际编译包含项、版权与完整许可。 |
| [PixiJS](https://github.com/pixijs/pixijs) | 8.19.0 | MIT | 实际运行代码及传递依赖。 |
| [Lucide React](https://github.com/lucide-icons/lucide) | 1.33.0 | ISC，并保留 Feather MIT notice | 图标使用和原有声明。 |
| [Zod](https://github.com/colinhacks/zod) | 4.4.3 | MIT | 包内版本与许可。 |
| DeepSeek Harness | 已锁定的 rc.8 基础及 Luma 适配 | MIT，Copyright (c) 2026 DeepSeek | 原版权、完整许可及实际修改范围。 |
| [stream-json / stream-chain](https://github.com/uhop/stream-json) | 3.7.0 / 4.2.5 | BSD-3-Clause | 每个实际包含包的版权与完整许可。 |
| [Peekaboo](https://github.com/steipete/Peekaboo) | 本机工具集成 | MIT | 实际随包二进制、源版本、许可及声明。 |
| [FFmpeg](https://ffmpeg.org/legal.html) | 媒体工具，取决于构建配置 | 登记构建以 LGPL-2.1-or-later 为基础 | 最终构建选项、启用组件、许可、对应源码与构建资料。 |
| [react-bits](https://reactbits.dev/) | RippleDistortion、ShapeBlur、GlassSurface 适配 | 本地来源记录为 MIT + Commons Clause v1.0 | 精确来源许可全文、修改、组合及分发方式；不能只看 MIT 名称。 |
| [OGL](https://github.com/oframe/ogl) / [Three.js](https://github.com/mrdoob/three.js) | 外观组件相关依赖 | Unlicense / MIT | 是否实际进入制品及准确版本、许可。 |
| [SillyTavern](https://github.com/SillyTavern/SillyTavern) | 1.18.0；万象剧场引擎及本地适配 | AGPL-3.0；本地启动器/适配记录为 AGPL-3.0-only | 完整许可、修改记录、对应源码及实际分发/服务方式。 |

## 需要单独说明的边界

**万象剧场与 AGPL。** 角色卡、图片、故事和引擎不是同一种资产。SillyTavern 的原引擎与受其许可约束的适配保留原有许可，Luma 的第一方许可说明不将其转为专有许可。对应源码和其他适用义务按实际组合、分发及服务方式处理。

**媒体工具。** FFmpeg 的许可取决于实际构建配置和启用组件。登记过 LGPL 构建，不代表任意替换的二进制都有相同条件。最终文件必须能对应其版本、构建与许可资料。

**外观组件。** react-bits 的本地来源记录包含 Commons Clause 条件。商品化与分发安排按精确版本的完整条款核对，不能仅根据 MIT 名称判断其使用范围。

**图片、人物、字体、声音与模型。** 代码许可不自动赋予这些内容的使用权。它们需要独立核对来源、引用、改编及分发范围。本资料包中的卡通角色群像是本次重新绘制的宣传插画；原始立绘、运行时动作、办公室场景及角色应用图标不作为可复用源素材附送。生成与身份参考记录见 [媒体资料](MEDIA_KIT.md)，公开使用范围仍需与具体素材来源对应。

## 随附资料

随附资料应对应该版本实际组件，提供完整版权声明、LICENSE/NOTICE，以及适用时的源码和构建资料获取方式，并按相应许可要求组织。开发工具清单、源码依赖目录和最终用户制品分别管理。

组件来源或许可疑问请联系 **[1805680363@qq.com](mailto:1805680363@qq.com)**。这份概览不替代原始许可证，也不作为任何上游权利人出具的专有授权。

## English

Luma uses Electron, React, PixiJS, Lucide, Zod, DeepSeek Harness, streaming JSON libraries, native tools, appearance components and SillyTavern, among others. **Exact versions, the complete dependency scope and license files follow the actual artifact and its accompanying materials.** The table records engineering references; the artifact determines the release-specific component list.

Privately maintained first-party source does not override third-party licenses or source obligations. SillyTavern and its recorded AGPL adaptations retain their applicable terms; react-bits has recorded MIT + Commons Clause conditions; FFmpeg terms depend on the actual build. Artwork, fonts, voices, models and content have separate rights. Release materials must match the distributed components and include complete applicable notices and required source/build-material access. Original licenses govern their respective components.
