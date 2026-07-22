[English](./README_EN.md) | 中文

---

# scroll-world-planner

> 🎬 沉浸式着� �页的 PM 规划器 — 品牌故事 → 场 景设计 → 导演脚本

[![GitHub](https: //img.shields.io/badge/GitHub-100000?style=fo r-the-badge&logo=github&logoColor=white)](htt ps://github.com/Erich956389473/scroll-world-p lanner)
[![License: MIT](https://img.shields. io/badge/License-MIT-yellow.svg)](https://ope nsource.org/licenses/MIT)

## ✨ 功能特� �

- 📖 **品牌故事线设计** — 构� �沉浸式叙事结构
- 🎨 **场景序列� ��划** — 自动规划滚动场景
- 🎯 * *调性适配** — 支持 4 种视觉调性� ��专业、活力、优雅、科技）
- 📝  **导演脚本输出** — 可直接交付� �发的详细脚本

## 🚀 快速开始

## # 作为 Agent Skill 使用

在任何支持  SKILL.md 的 Agent 中使用：

```
scroll-w orld-planner
  brand: 你的品牌名
  indus try: 行业
  pitch: 核心卖点
  scenes: 4 
  tone: professional
```

### 参数说明

 | 参数 | 类型 | 必填 | 说明 |
|------ |------|------|------|
| `brand` | `string` |  ✅ | 品牌名称 |
| `industry` | `string`  | ✅ | 所属行业 |
| `pitch` | `string`  | ✅ | 核心卖点/价值主张 |
| `scenes ` | `int` | ❌ | 场景数量（默认 4）  |
| `tone` | `string` | ❌ | 视觉调性（ 默认 professional） |

### 调性选项

-  `professional` — 专业感（适合 B2B、 金融、科技）
- `energetic` — 活力� �（适合运动、娱乐、社交）
- `eleg ant` — 优雅感（适合奢侈品、时尚 、艺术）
- `tech` — 科技感（适合  AI、SaaS、创新产品）

## 📖 输出� �例

```markdown
## scroll-world 导演脚� �

**品牌:** 鲜直达（生鲜电商）
** 调性:** 专业感
**场景数:** 4 + CTA

# ## 场景1（源头）
**镜头:** 俯瞰产� �� → 飞越田间 → 菜品特写
**文案 :** 从田间到餐桌，新鲜直达
**时� �:** 3s

### 场景2（配送）
**镜头:**  城市 → 配送员 → 社区
**文案:** 3 0分钟极速配送
**时长:** 3s

### 场� �3（餐桌）
**镜头:** 窗外 → 厨房  → 餐桌
**文案:** 为家人准备一顿� ��食
**时长:** 3s

### 场景4（APP）
** 镜头:** 手机 → APP界面 → 交互演� ��
**文案:** 一键下单，新鲜到家
** 时长:** 3s

### CTA
**文案:** 立即体� �
**按钮:** 下载 APP
```

## 🔗 相关� ��目

- [scroll-world](https://github.com/os o95/scroll-world) — 滚动穿越 3D 着陆� ��生成器
- [Skill Compass](https://github. com/Erich956389473/skill-compass) — Agent S kill 生态导航

## 📦 技术栈

- **类 型:** Agent Skill (Markdown)
- **格式:** S KILL.md
- **兼容:** Claude Code, Cursor, Co pilot 等 AI Agent

## 📄 License

MIT Lice nse - 详见 [LICENSE](LICENSE)

---

**Autho r:** Erich Lee | [GitHub](https://github.com/ Erich956389473)
 