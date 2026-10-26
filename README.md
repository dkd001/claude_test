# 坦克大战 · Battle City

经典 FC 红白机《坦克大战》（Battle City）的 HTML5 复刻版，纯原生 HTML + Canvas + JavaScript 实现，**单文件**，无需任何依赖，打开即可游玩。

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Platform](https://img.shields.io/badge/platform-Web-brightgreen.svg)

## 🎮 玩法

保卫画面底部的**基地（鹰）**不被敌方坦克摧毁，消灭关卡内所有敌方坦克即可过关。基地一旦被击毁（无论是敌人还是你自己的流弹）游戏即结束。

- 移动：`W A S D` 或方向键 `↑ ← ↓ →`
- 射击：`空格` 或 `J`
- 暂停：`P`
- 开始 / 重新开始：`Enter`

移动端会自动显示虚拟摇杆与开火按钮。

## ✨ 特性

- 经典玩法：砖墙、钢板、河流、草丛、基地等多种地形
  - 砖墙可被子弹摧毁；钢板只有强化火力才能击穿
  - 河流阻挡坦克但子弹可穿过；草丛会隐藏坦克
- 4 种敌方坦克：普通、快速、强力、装甲（3 点生命）
- 道具系统：⭐ 火力强化 / 🛡 护盾 / ❤ 额外生命 / 💣 全屏炸弹
- 关卡递进、得分与本地最高分记录、爆炸粒子与屏幕震动、复古音效

## 🚀 运行

直接双击打开 `index.html`，或部署到任意静态托管服务（如 GitHub Pages）。

## 📁 结构

```
坦克大战/
├── index.html    # 游戏全部代码（HTML + CSS + JS）
└── README.md
```

## 📄 许可证

[MIT](LICENSE)
