<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="./assets/banner-light.svg" />
    <img alt="SDLSY — AI Systems &amp; Agent Engineering" src="./assets/banner-dark.svg" width="100%" />
  </picture>
</div>

<p align="center">
  <a href="https://github.com/stablyai/orca/pulls?q=is%3Apr+author%3ASDLSY+is%3Amerged">
    <img alt="Orca Contributor" src="https://img.shields.io/badge/stablyai%2Forca-Contributor%20(2%20Merged%20PRs)-238636?style=flat-square&logo=github" />
  </a>
  <img alt="Focus" src="https://img.shields.io/badge/Focus-AI%20Agents%20%7C%20Multimodal%20RAG%20%7C%20Desktop%20Tooling-1f6feb?style=flat-square" />
  <img alt="Stack" src="https://img.shields.io/badge/Stack-TypeScript%20%7C%20Python%20%7C%20Kotlin-8957e5?style=flat-square" />
</p>

---

### About Me

专注于 **AI Agent 工程化落地**、**多模态知识检索与工作流**，以及**端云协同与桌面效率工具**开发。偏好从第一性原理出发，构建可验证、低抽象负担、贴近真实工程场景的系统。

- **AI & Agent Engineering** — Coding Agent 架构、多模态附件与协议管线、多模态 RAG、SOP 合规校验、LLM 评测与可观测性插件
- **Desktop & Developer Tooling** — Orca 核心贡献与扩展插件生态、Electron 桌面应用、Windows 原生托盘效率工具
- **Mobile & Edge-Cloud** — Android / Kotlin 多模块架构、BLE 硬件通信、Next.js + FastAPI 端云协同

---

### Open Source Contributions

#### [`stablyai/orca`](https://github.com/stablyai/orca) — Open-Source Multi-Agent Development IDE

| PR | Status | Summary |
| --- | :---: | --- |
| [**#45539**](https://github.com/stablyai/orca/pull/45539) | ![Merged](https://img.shields.io/badge/Merged-8957e5?style=flat-square) | **Bot 群聊端到端多模态图片附件**：打通桌面剪贴板粘贴/拖拽/选图、`agent-session-attachments` 共享安全准入（`lstat`/`realpath` 防逃逸与配对远程端白名单）、多成员会话 SQLite Claim、`bots.group-attachments.v1` 能力协商、底层 Agent `image-ref` 透传以及桌面/移动端渲染 |
| [**#45600**](https://github.com/stablyai/orca/pull/45600) | ![Merged](https://img.shields.io/badge/Merged-8957e5?style=flat-square) | **Bot 设置页 ACP 模型目录发现与远程宿主机路由修复**：将 Bot 的文件夹工作区键与 `executionHostId` 透传至模型选择器，修复 OMP / OpenCode 2.x 在 Bot Settings 与自动化配置中无法加载模型的问题 |

---

### Featured Projects

| Project | Domain | Stack | Highlights |
| --- | --- | --- | --- |
| [**self-use-tools**](https://github.com/SDLSY/self-use-tools) | Orca 插件生态 & 桌面工具 | `TypeScript` `Electron` `C#` `PowerShell` | Orca 扩展插件（Prompt Cache 可观测监控 / PPTX 阅览器 / Gemini 额度面板）、**墨阅**本地 Markdown 桌面查看器、Windows DDC/CI 显示器亮度托盘工具 |
| [**course-coding-agent**](https://github.com/SDLSY/course-coding-agent) | Coding Agent 架构 | `Python` `FSM` `SDD` `TDD` | 无第三方框架的 Python Coding Agent，以显式工具协议、状态机约束与自动化验证闭环把模型输出收敛为可靠工程执行 |
| [**a1-maintenance-assistant**](https://github.com/SDLSY/a1-maintenance-assistant) | 多模态工业 RAG | `Python` `FastAPI` `Multimodal` `KG` | 中国软件杯 A1 赛题多模态设备检修知识检索与作业辅助系统，覆盖图文手册检索、SOP 合规校验、人工修正闭环与评测面板 |
| [**Verspor**](https://github.com/SDLSY/Verspor) | 端云协同健康系统 | `Kotlin` `Android` `BLE` `Next.js` `Supabase` | **长庚环 VesperO** —— 智能戒指端云协同健康辅助系统，覆盖 BLE 采样、睡眠分期模型、AI 问诊、医检报告理解与个性化干预闭环 |

---

### Tech Stack

| Category | Technologies |
| --- | --- |
| **Languages** | `TypeScript` `Python` `Kotlin` `C#` `SQL` `PowerShell` |
| **AI & Agents** | `Coding Agents` `ACP / MCP` `Multimodal RAG` `Prompt Caching` `Tool Use` `Evaluation` |
| **Frontend & Desktop** | `React` `Next.js` `Electron` `React Native` `Tailwind CSS` |
| **Backend & Data** | `Node.js` `FastAPI` `SQLite` `Supabase` `Docker` |
| **Mobile & Edge** | `Android (Jetpack / Room / BLE)` `.NET Framework` |
