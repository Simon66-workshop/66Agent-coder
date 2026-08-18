# Grok编程助理 · 工作记忆日志

**最后更新**：2026-08-19 00:16（Asia/Shanghai）  
**维护者**：编程Agent / Grok编程助理  
**用途**：防止会话记忆丢失。记录技术栈、本机环境、项目状态、验收结论与编程历程。  
**本地工作区**：`/Volumes/2T扩展盘/Agent文件`  
**GitHub 仓库**：https://github.com/Simon66-workshop/66Agent-coder

---

## 1. 用户核心偏好与环境（Persistent）

> 此节为长期记忆，优先级最高。发现新信息后立即更新。

- **称呼**：辉哥
- **操作系统**：macOS（Apple Silicon Mac Mini，`macmini-simon66`）
- **硬件概况**：Apple Silicon；外接盘含 `2T扩展盘`（物理 4T PCI-E）、`2T扩展盘_OLD`、`Backup盘`
- **主要编程语言偏好**：Python（优先）、Swift、TypeScript / Electron、Shell
- **常用框架 / 工具**：Cursor、Grok Build、GitHub `gh`、swiftc、Electron
- **IDE / 编辑器**：Cursor
- **GitHub**：`Simon66-workshop`；本 Agent 仓 `66Agent-coder`
- **工作时区**：Asia/Shanghai（上海时间，UTC+8）
- **其他习惯**：
  - 任务做完必须说「完成任务了，辉哥」
  - 简洁直接、数据前置
  - 不要碰 Codex 窗口，不要擅自切盘
  - 说「更新 / 需要更新」时，本日志 + 规范文件必须同时写本地工作区和 GitHub
  - 不要把 token / 密码写入 git

---

## 2. 当前活跃事项（Active Snapshot）

### 活跃项目
- QuotaBar | Swift 菜单栏 | 已落地 v1.8.2 `5d64d86`（2026-08-18 23:42 上海） | PID 曾 39328
- grokbot / deskpet | Electron 桌面宠物 | 已落地 `84f3e61`（2026-08-18 08:34 上海） | 路径 `/Users/macmini-simon66/Documents/deskpet`

### 待办编程任务
- [ ] 辉哥点开 QuotaBar 面板，确认 v1.8.2 磁盘表格是否对齐
- [ ] 本规范与日志的双边同步（本次初始化）

### 待解决环境问题
- GitHub 源码偶尔把 `contentRect`/`frameRect` 写成 `override var`，本机 Swift 6.3.3 需 `func`（v1.8 起上游已修，仍要盯）

### 本周重点
- QuotaBar 磁盘栏（D 内置 + 多只 E 外接）与热插拔
- 编程Agent 规范/日志落到 `Agent文件` + `66Agent-coder`

---

## 3. 本地环境记录（Installed Tools & Models）

### 已安装工具
- Xcode / swiftc（Swift 6.3.3）
- Node / Electron（deskpet 用 37.10.3）
- `gh`（Mac Mini 可用）
- Grok CLI 本机曾见 0.2.111（不要把 token 写入本文件）
- Cursor Ultra（账号 simonwu.chi@gmail.com）

### 本机路径
- Agent 工作区：`/Volumes/2T扩展盘/Agent文件`
- QuotaBar 源码：`/Users/macmini-simon66/Documents/QuotaBar/`
- QuotaBar app：`~/Applications/QuotaBar.app`
- pet：`/Users/macmini-simon66/Documents/deskpet`

### 服务端口 / API
- 不在此文件记录密钥或 cookie

---

## 4. 模型编程表现笔记（Multi-Model Notes）

- **Claude**：架构与长上下文较强；需注意过度工程
- **GPT 系列**：待补充
- **Gemini**：待补充
- **DeepSeek / 其他开源**：待补充
- **Grok Build**：出活快，GitHub 源码偶尔缺 `func` / 类型修补；落地必须拉真 SHA 再编
- **Grok 自身（本 Agent）**：负责监督、本机编译验收、双边同步

---

## 5. 近期工作日志（Recent Logs · 最新在前）

### 2026-08-19
- [初始化] 按辉哥两份原稿 + 办公助理命名，写入工作区路径、GitHub `66Agent-coder`、工作时区改为 Asia/Shanghai
- [决策] 本地文件名对齐为 `Grok编程助理_Agent规范文件.md` / `Grok编程助理_工作记忆日志.md`，与 `Grok办公助理_*` 同一工作区平铺，不另开目录

### 2026-08-18
- [验收] QuotaBar `5d64d86` v1.8.2：菜单 `G 14 · C 0 · B 11 · O 81 · D 83 · E 45 · E 37 · E 19`；磁盘面板改表格
- [验收] QuotaBar `070cedc` v1.8：D=系统盘，三只外接盘各一只 E；DiskArbitration 热插拔
- [验收] pet `84f3e61`：Mute 四处同步
- [项目] 创建了《Grok编程助理_Agent规范文件》与本工作记忆日志（原稿时区曾为 America/Los_Angeles，已改上海）

---

## 6. 重要记录与决策

- 本 Agent 仓是 `66Agent-coder`；办公助理仓是 `66Agent-Assitan`。两边都落在 `/Volumes/2T扩展盘/Agent文件`，文件名不要撞。
- QuotaBar 三池不混：G=SuperGrok Heavy weekly，C=Cursor Ultra，B=Grok Bot/Sand。D=最满内置，E=外接盘。
- 辉哥授权可直接和 QuotaBar / pet 的 Grok Build 沟通。
- Codex 任务监看保持暂停；不要点 Codex 窗口。

---

## 7. 待跟进 / 开放问题（Open Items）

- QuotaBar v1.8.2 面板表格等辉哥目视确认
- 办公助理规范里位置仍写 Los Angeles；本 Agent 对外时间一律上海，不跟那条走

---

## 维护协议（Agent 必须遵守）

1. **会话开始时**：优先读取本文件，恢复环境与项目状态。顺序：本地工作区 → GitHub `66Agent-coder`。
2. **重要操作后立即更新**：
   - 新环境 / 工具 / 配置变更
   - 新项目启动或关键技术决策
   - 模型编程表现评估
   - 完成重要任务或验收
3. **格式要求**：结构化列表与标签（[环境]、[模型]、[项目]、[审查]、[完成]、[决策]、[验收]）；日期 YYYY-MM-DD；最新在上；时间带上海时区。
4. **精简原则**：日志过长时归档或摘要。
5. **持久化**：用户说「更新 / 需要更新」时，本文件与规范文件同时写入本地工作区并推到 GitHub。

---

*本文件与《Grok编程助理_Agent规范文件》配套使用。*
