# 功能模块截图指引

官网「功能模块详解」章节已重排为 **图集 + 图文说明**：每个模块都预留了图片位，
把对应截图放进 `docs/img/`（本仓库）或 `src/website/public/img/`（官网源），命名如下即可自动显示，无需改代码。

> 截图建议：在桌面程序里打开对应模块，截一张能体现该模块核心功能的界面图
> （窗口越大越清晰越好，宽度建议 ≥ 1000px）。PNG 格式，文件名严格对应下表。

| 文件名 | 模块 | 建议截取内容 |
| --- | --- | --- |
| `mod-home.png` | 🏠 今日 · 生活仪表盘 | 首页 widget 网格全貌 |
| `mod-travel.png` | 🗺️ 旅行 | 行程列表 / 单个行程详情 |
| `mod-todo.png` | 📋 待办 | 多视图任务列表 + 今日总览 |
| `mod-calendar.png` | 📅 日历 | 月历网格（带圆点聚合） |
| `mod-timer.png` | ⏰ 定时 | 健康定时任务 + 闹钟 |
| `mod-plan.png` | 🎯 规划 | 年度目标 / 心愿清单 |
| `mod-courses.png` | 🎓 课程表 | 周课表 |
| `mod-diary.png` | 📖 日记 | 日记列表 / 编辑器 |
| `mod-finance.png` | 💰 记账 | 汇总卡 + 图表 |
| `mod-books.png` | 📚 读书 | 读书状态页签 / 书架 |
| `mod-knowledge.png` | 🧠 知识库 | 笔记网格 / Markdown 编辑 |
| `mod-notes.png` | 📝 便签 | 桌面/内置便签 |
| `mod-habit.png` | ✅ 习惯 | 习惯卡片 + 每周概览矩阵 |
| `mod-album.png` | 🖼️ 相册 | 时间线 / 相册视图 |
| `mod-quickops.png` | 🚀 快捷操作 | 瀑布流 / 分块布局 |
| `mod-tools.png` | 🧰 工具 | 工具网格 + 某工具界面 |
| `mod-vault.png` | 🔐 密码库 | 密码列表（可打码） |
| `mod-clipboard.png` | 📋 剪贴板 | 快速面板 / 列表 |
| `mod-screenshot.png` | 📷 截图 | 标注编辑器 / 网格浏览 |
| `mod-relax.png` | 🐟 摸鱼 | 某款小游戏 |

## 放置位置

- **线上站（GitHub Pages，仓库 `xiaoya-doc`）**：把图片放到 `xiaoya-doc/docs/img/`。
- **官网源（`src/website`）**：把图片放到 `src/website/public/img/`，`pnpm build` 会自动随产物输出。

两个目录放一份即可（线上以 `xiaoya-doc/docs/img/` 为准）。放好后刷新页面，图廊缩略图与每模块说明处的截图位会自动显示；
点击任意截图可放大查看（再次点击空白 / 按 Esc 关闭）。
