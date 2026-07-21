# scroll-world-planner

**沉浸式着陆页的 PM 规划器。**

[scroll-world](https://github.com/oso95/scroll-world) 是开发用的 Agent Skill，生成炫酷的滚动穿越3D着陆页。
scroll-world-planner 是 PM 侧的规划层——品牌故事线、场景设计、信息层级规划好，开发照着做就行。

## 输出示例

```
## scroll-world 导演脚本

品牌：鲜直达（生鲜电商）
调性：专业感
场景数：4 + CTA

场景1（源头）：俯瞰产地→飞入田间→菜品特写
场景2（配送）：城市→配送员→社区
场景3（餐桌）：窗外→厨房→餐桌
场景4（APP）：手机→APP界面→交互演示
CTA：立即体验
```

## 使用

在任何支持 SKILL.md 的 Agent 中使用：

```
scroll-world-planner
  brand: 你的品牌名
  industry: 行业
  pitch: 核心卖点
  scenes: 4
  tone: professional
```
