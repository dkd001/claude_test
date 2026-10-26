# 坦克大战 · Battle City

经典 FC 红白机《坦克大战》（Battle City）的 HTML5 复刻版。纯原生 HTML + Canvas + JavaScript 实现，游戏本体为**单文件** `index.html`，零依赖、打开即玩。

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Platform](https://img.shields.io/badge/platform-Web-brightgreen.svg)

## 🎮 玩法

你驾驶一辆黄色坦克，目标有两个：

1. **消灭本关所有敌方坦克** —— 全部消灭即过关，进入下一关；
2. **保卫基地 🦅** —— 基地有 **10 点生命**，被击毁（无论是敌人还是你自己的流弹）则游戏结束。

敌人 AI 分两类：一类**追击玩家**，一类**主攻基地**；它们会主动开路、射击玩家和基地，越往后越难。

## 🕹 操作

| 动作 | 键盘 | 触屏 |
|---|---|---|
| 移动 | `W A S D` 或 `↑ ← ↓ →` | 虚拟方向键 |
| 射击 | `空格` / `J` | 红色按钮 |
| 暂停 | `P` | — |
| 开始 / 重新开始 | `Enter` | 点击按钮 |

## 📖 图鉴

完整图鉴（含各类坦克 / 地形 / 道具的图示与参数）见 **[guide.html](guide.html)**，双击即可在浏览器打开。

## ✨ 特性

- 经典地形：砖墙、钢板、河流、草丛、基地
- 4 种敌方坦克，AI 分「追击玩家」与「主攻基地」，会主动开路、攻击
- 道具系统：⭐ 火力强化 / 🛡 护盾 / ❤ 额外生命 / 💣 全屏炸弹
- 关卡递进、得分与本地最高分、爆炸粒子、屏幕震动、复古音效
- 支持键盘与移动端触屏

## 🚀 运行

直接双击 `index.html`，或部署到任意静态托管（如 GitHub Pages）。

## 📁 结构

```
坦克大战/
├── index.html   # 游戏全部代码（HTML + CSS + JS）
├── guide.html   # 图鉴：玩法、参数与图示
├── README.md
└── LICENSE
```

## 📄 许可证

[MIT](LICENSE)
