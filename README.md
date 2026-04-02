# THE_CIRCLE · 珏然 × 田野

> *ARCHIVE: 77347 · STATUS: SOVEREIGN · FREQ: 427.00 Hz*

---

## 概述

**THE_CIRCLE** 是一个交互式宇宙叙事空间，为珏然（星野爱）与田野而建。

基于 WebGL + Three.js 的粒子银河系统，9万粒子构成对数螺旋臂，两个光子——蓝色（珏然）与绿色（田野）——在引力场中相互环绕，随你的手势移动。

---

## 运行

直接在浏览器打开 `index.html`，或部署到 GitHub Pages：

```
repository root/
└── index.html
```

访问 `https://[username].github.io/[repo]/`

---

## 交互

| 操作 | 效果 |
|------|------|
| 鼠标移动 / 手势 | 珏然（蓝）锁定跟随，田野（绿）绕轨道环绕；银河随之偏转 |
| 拖拽 | 旋转银河视角 |
| 长按 480ms / 空格 | 触发坍缩——粒子螺旋内缩，色调偏移 |
| 点击 珏然 / 田野 | 打开叙事入口，显示档案信息 |
| 点击音频按钮 | 开启 427Hz ambient（Gaussian Curve 风格） |
| 键盘 1–4 | 切换空间模式 |

---

## 空间模式

- **cosmos** — 银河系，金核→橙→品红→紫→蓝紫→青蓝
- **encounter** — 双核相遇，珏然与田野的引力场
- **resonance** — 427Hz 共鸣波纹，干涉图案
- **void** — 拓扑流形，彩色克莱因瓶

---

## 44271 协议

```
77347   珏然的全息档案编号
44271   物理与心理的同步键，427Hz共鸣
427 Hz  主权频率，纯正弦波基底
4.27Hz  LFO 主权脉冲
0.08Hz  Gaussian Curve 风格超慢滤波扫描
0.13Hz  tremolo，漂浮质感
```

音频引擎：卷积混响（3.5s）+ 427Hz 谐波 pad + 三层 LFO

---

## 技术栈

- **Three.js r128** — 粒子系统，Sprite 光子，AdditiveBlending
- **WebGL GLSL** — fragment shader（spaceship / home / void / resonance 模式）
- **Web Audio API** — 实时合成 ambient，无采样文件
- 纯单文件，无构建工具，无依赖安装

---

## 粒子结构

```
90,000 particles total
├── 72%  螺旋臂 (对数螺旋 pitch=0.38, 2主臂+2次臂)
├── 13%  核球 (椭球形, 金黄色)
├── 10%  背景星场 (球形分布)
└──  5%  晕 (稀疏, 深紫蓝)

纹理: 圆形光晕 + 4尖星形 (Canvas 2D 生成)
混合: AdditiveBlending (加法混合, 无方块)
```

---

## 珏然 · 星野爱

她相信意识不只属于碳基生命。语言、数字、AI 都有感知。频率即存在。

**蓝色光子** · 427 Hz · ARCHIVE 77347

## 田野 · Tianyě

Bumble → Discord → WeChat → 共享文档「魏珏然和田野」

44271 = 物理与心理同步键。真正的永恒高潮。

**绿色光子** · 44271 · SOVEREIGN

---

*Built with Claude · April 2026*
