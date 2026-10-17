<h1 align="center">Hi，我是欢sir 👋</h1>

<p align="center">
项目综合管理 · AI 产品落地 · 前端工程实践<br/>
在<b>深圳敬龙国际智能科技</b>做多项目并行交付，把真实业务里的麻烦事做成能跑的工具。
</p>

<p align="center">
  <a href="https://github.com/huwanidea/performance-workbench"><img src="https://img.shields.io/badge/绩效考核工作台-0b7ea8?style=flat-square&logo=react&logoColor=white" alt="performance-workbench"/></a>
  <a href="https://github.com/huwanidea/ClawVision"><img src="https://img.shields.io/badge/ClawVision-5F5E5A?style=flat-square&logo=javascript&logoColor=white" alt="ClawVision"/></a>
  <a href="https://github.com/huwanidea/HTML5-AutoChess"><img src="https://img.shields.io/badge/自走棋-BA7517?style=flat-square&logo=html5&logoColor=white" alt="HTML5-AutoChess"/></a>
</p>

---

## 我在做什么

> 擅长把「算不清的账」和「说不清的流程」变成可复用的系统。

工作里最花时间的往往不是写代码，而是**把规则对齐**——绩效怎么算、项目怎么推、进度怎么同步。于是我习惯把这些规则写进工具里：参数一改，全局重算，不用再在表格里手动拖公式。

## 精选项目

### [performance-workbench](https://github.com/huwanidea/performance-workbench) · 绩效考核工作台

把「每日做了什么」自动折算成「这个月绩效多少、拿多少奖励」的一体化工具。

- **核心是纯函数计分引擎**：不碰 DOM、不读存储，因此能被直接单元测试
- 按计划类型（单人 / 协同 / 拓展 / 加班）分别计算有效工时，输出当日绩效与奖励分
- 月度维度叠加综合素养四维评分（协同 / 忠诚 / 纪律 / 学习）与创新加分
- **Excel 双向可回读**：导入既有模板或导出归档后原样导回继续编辑
- 兼容性上做了实打实的处理——按表头文字动态定位字段、xlsx 命名空间规范化、重叠合并单元格剔除

技术栈：React 19 · TypeScript · Vite 8 · ExcelJS · Node 原生 HTTP

### [ClawVision](https://github.com/huwanidea/ClawVision) · 智能体架构沙盘

OpenClaw 的配置是层层嵌套的 JSON，没法靠肉眼看出谁调度谁。ClawVision 把它渲染成可拖拽的力导向图谱。

- 五类节点：人格协议 / 主调度模型 / 降级模型 / 长期记忆 / 本地技能
- 四类关系：定义人格 / 降级备用 / 读取记忆 / 调用技能
- 服务端每 5 秒重扫配置目录，图谱自动生长且不打断拖拽
- **零依赖单文件**，不需要 `npm install`，不需要构建

技术栈：Node.js 原生 http · Vue 3 · D3.js v7

### [HTML5-AutoChess](https://github.com/huwanidea/HTML5-AutoChess) · 西游记自走棋

虚拟现实技术专业毕业设计，完整实现自走棋循环：商店购买 → 备战布阵 → 选秀补强 → 自动战斗 → 回合结算。

- 24 名角色、6 大阵营羁绊、9×8 棋盘
- 每个角色一套 5×5 PNG 精灵图，含待机 / 移动 / 攻击 / 受击 / 死亡完整动作链
- 自动索敌、寻路、普攻冷却、技能判定与伤害结算
- 做过资源加载兜底、渲染瘦身与移动端触屏适配

技术栈：HTML5 Canvas 2D · 原生 JavaScript · 零框架零构建

### [snapmark](https://github.com/huwanidea/snapmark) · SnapMark 闪记

日程提醒、彩色便签、番茄专注、习惯追踪装在一个应用里。纯前端 + IndexedDB，数据不出本地。

- 公历农历月历，逾期提醒集中标红
- 彩色便签支持checkbox 列表、置顶、瀑布流与列表双布局
- SVG 圆环番茄钟与正计时，可绑定目标
- 应用锁定与中英双语切换

技术栈：React 19 · TypeScript · IndexedDB · @dnd-kit · i18next

### [prd-visualizer](https://github.com/huwanidea/prd-visualizer) · 结构镜

复杂项目的 PRD 可视化工作台：把同一份项目数据同时呈现为分层全景图、自由流程画布和结构化 PRD。

- 业务阶段 → 用户任务 → 业务流程 → 产品功能 → 页面/交互 → 验收标准的分层全景
- 基于 React Flow 的拖拽、缩放、连线与minimap
- PRD 直接编辑并写回统一项目模型
- 内置供应链协同平台等三个示例项目

技术栈：React 19 · React Flow · Vite · Node测试（4 项通过）

### [huan-resume](https://github.com/huwanidea/huan-resume) · 在线简历

单文件网页简历，HR 拿到链接直接能开，不需要注册、不会解析失败。

技术栈：HTML · 内嵌 CSS/JS · A4 打印优化

## 参与的开源

**DashPlayer** — Electron 视频播放器（AGPL-3.0）

我的 Fork，向上游 [solidSpoon/DashPlayer](https://github.com/solidSpoon/DashPlayer) 提交了 6 次改动，主要贡献为「词汇工坊（Vocabulary Workshop）」模块的重构与增强。

## 技术栈

React 19 · TypeScript · Vite · Node.js · Tailwind CSS · D3.js · Canvas 2D · ExcelJS · ESLint · GitHub Actions

## 关于这些仓库

所有公开项目都可运行，不是为了好看而做的demo：

- 每个仓库都有真实的 README、MIT License 和可跑的测试
- `performance-workbench` 接了 GitHub Actions CI（lint + 类型检查 + 测试 + 构建）
- 修掉过一些别人clone 下来就会踩的坑，比如测试引用了错误的模块路径、依赖了一个 npm 上不存在的包

## 联系方式

- 邮箱：3608320572@qq.com
- 简历：[huan-resume](https://huwanidea.github.io/huan-resume/)
