# 压力粉碎机 / Stress Crusher

一款移动端解压小游戏PWA。点击/触摸屏幕上冒出的压力气泡，在60秒内疯狂粉碎生活中的各种压力。

A mobile-first stress relief PWA game. Tap the pressure bubbles that pop up on screen and crush life's stress in 60 seconds.

## 玩法 / How to Play

- 屏幕上会随机冒出压力气泡（996、内卷、房价、催婚、考研……）
- 点击或触摸气泡即可粉碎，获得分数
- 连续命中触发 Combo 加分，最高10倍
- 每轮60秒，越往后气泡出现越快
- 结算时随机展示一句暖心语录

- Pressure bubbles (996, overtime, rent, exams...) randomly appear on screen
- Tap or touch a bubble to smash it and earn points
- Consecutive hits trigger Combo multiplier, up to 10x
- Each round lasts 60 seconds, bubbles spawn faster as time goes on
- A random encouraging message is shown at the end

## 特性 / Features

- 纯前端实现，单HTML文件，无依赖 / Pure frontend, single HTML file, zero dependencies
- PWA 支持，可添加到主屏幕离线使用 / PWA ready, installable to home screen, works offline
- Web Audio API 音效，连击时音调逐渐升高 / Web Audio API sound effects, pitch rises with combo
- 粒子爆炸 + 飞分动画 / Particle explosions + floating score animations
- 移动端优先，支持触摸操作 / Mobile-first, touch-friendly
- 深色主题，赛博风格视觉 / Dark theme, cyberpunk-style visuals

## 运行 / Getting Started

直接用浏览器打开 `stress-relief-game.html`，或部署到任意静态服务器。

Open `stress-relief-game.html` in a browser, or deploy to any static server.

```bash
python3 -m http.server 8080
```

## 文件结构 / Project Structure

```
├── stress-relief-game.html   # 游戏主文件 / Main game file
├── manifest.json             # PWA 配置 / PWA manifest
├── sw.js                     # Service Worker（离线缓存）/ Service Worker (offline cache)
└── README.md
```
