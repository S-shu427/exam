# 小苏题库 - 汽车网联在线考试系统 🚗

> 一个轻量、高效的汽车网联技术在线学习与考试平台。
> 基于纯前端 SPA 架构，零后端依赖，开箱即用。

[![GitHub Pages](https://img.shields.io/badge/demo-online-brightgreen?logo=github)](https://S-shu427.github.io/exam/)
[![PWA](https://img.shields.io/badge/PWA-ready-blueviolet)](https://developer.mozilla.org/zh-CN/docs/Web/Progressive_web_apps)
[![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)
[![HTML](https://img.shields.io/badge/HTML-5-orange?logo=html5)](https://developer.mozilla.org/zh-CN/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?logo=javascript)](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript)

---

## 📋 项目简介 | About

专为 **汽车网联技术** 领域打造的一款在线考试练习系统，涵盖 **416 道专业题目**，包含单选题和多选题，覆盖车联网协议、通信标准、智能驾驶、网络安全等核心知识领域。

### 适用人群

- 汽车网联行业从业者 & 工程师
- 车联网 / V2X / 智能驾驶学习者
- 车企面试准备者
- 对汽车电子与通信技术感兴趣的开发者

### 技术特点

- ✅ 纯前端 SPA，无需后端服务器，开箱即用
- ✅ PWA 支持，可添加到手机桌面，离线可用
- ✅ 全量题目答案与详细解析
- ✅ 训练模式：分批刷题 + 掌握度追踪
- ✅ 随机组卷模考，模拟真实考试
- ✅ 错题本功能，自动记录 + 手动管理
- ✅ localStorage 持久化学习数据
- ✅ 移动端适配，手机 / 平板 / PC 全兼容

---

## 🚀 在线体验 | Live Demo

👉 **[https://S-shu427.github.io/exam/](https://S-shu427.github.io/exam/)**

点击即用，无需安装任何依赖。

> 💡 推荐使用 Chrome 或 Edge 浏览器，并允许"添加到桌面"以获得最佳 PWA 体验。

---

## 🧩 功能特性 | Features

### 📝 考试模式

| 功能 | 说明 |
|------|------|
| 随机组卷 | 从题库中随机抽取题目，模拟真实考试 |
| 自动判分 | 提交后即时评分，显示正误与得分 |
| 答案解析 | 每题附带详细解析，知其然更知其所以然 |
| 答题回顾 | 考试结束后可逐题回顾，查漏补缺 |

### 🎯 训练模式

支持按题型分批刷题，实时追踪掌握度，针对性强化薄弱环节。

### 📚 错题本

- 考试中答错的题目自动收录
- 支持手动加入 / 移出错题
- 可单独练习错题，重点攻克

### 📊 学习统计

- 答题总数与正确率
- 各题型掌握度可视化
- 学习进度追踪

### 📱 PWA 特性

- 支持添加到手机桌面，像原生 App 一样使用
- 离线缓存，无网络也可继续练习
- 沉浸式全屏体验

---

## 🛠 技术栈 | Tech Stack

| 技术 | 用途 |
|------|------|
| **HTML5** | 语义化页面结构 |
| **CSS3** | 现代化界面布局与动效 |
| **Vanilla JavaScript (ES6+)** | 核心业务逻辑，零框架依赖 |
| **localStorage** | 用户学习数据持久化 |
| **PWA (Service Worker)** | 离线缓存与桌面端安装 |
| **GitHub Pages** | 零成本部署与持续集成 |

> 🚫 零外部依赖，无需 Node.js / npm / 构建工具，直接修改 `index.html` 即可。

---

## 📦 本地开发 | Local Development

```bash
# 克隆仓库
git clone https://github.com/S-shu427/exam.git

# 进入目录
cd exam

# 直接用浏览器打开
# open index.html 或双击 index.html
```

修改 `index.html` 中的 `questions` 数组即可增删题目。

---

## 📚 题库内容 | Question Bank

| 题型 | 数量 | 覆盖领域 |
|------|------|----------|
| **单选题** | 278 题 | 车联网通信协议、V2X、CAN/LIN 总线、车载以太网 |
| **多选题** | 138 题 | 智能驾驶、传感器融合、网络安全、OTA 升级 |
| **合计** | **416 题** | 全面覆盖汽车网联核心技术 |

---

## 📄 许可 | License

本项目基于 MIT 许可协议开源 — 详见 [LICENSE](LICENSE) 文件。

---

## 🤝 贡献指南 | Contributing

欢迎提交 Issue 或 PR！

- 🐛 **发现 Bug** → 请提 [Issue](https://github.com/S-shu427/exam/issues)
- 💡 **建议新功能** → 欢迎讨论
- 📝 **补充题目** → Fork 后修改 `index.html` 的 `questions` 数组并提交 PR

---

## 📬 联系方式 | Contact

- GitHub: [@S-shu427](https://github.com/S-shu427)
- 项目: [github.com/S-shu427/exam](https://github.com/S-shu427/exam)

---

*Made with ❤️ for the automotive networking community — 让车联网学习更简单*
