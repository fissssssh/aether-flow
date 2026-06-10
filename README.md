# Aether Flow — Interactive Fluid Art

基于 [Pavel Dobryakov 的 WebGL 流体模拟](https://github.com/PavelDoGreat/WebGL-Fluid-Simulation) 进行创意改造的互动流体艺术体验。

## ✨ 新特性

- **🌌 6 种视觉模式** — Cosmic（宇宙）、Fire（火焰）、Ocean（海洋）、Aurora（极光）、Neon（霓虹）、Smoke（烟雾），每种模式拥有不同的颜色方案和物理参数
- **✨ 深空星云主题** — 动态星空背景、暗角效果、微妙的扫描线纹理
- **🎮 增强交互** — 滚轮调整笔刷大小、双击爆发效果、右键清除画布
- **⏱ 实时 HUD** — FPS 计数器、当前模式、笔刷大小显示
- **💤 空闲自动播放** — 5 秒无操作后自动生成柔和的流体动画
- **⌨ 完整快捷键** — 数字键 1-6 切换模式、H 帮助面板、C 清除、R 重置、F 全屏
- **📱 移动端适配** — 响应式 UI，支持多点触控

## 🎹 快捷键

| 按键 | 功能 |
|------|------|
| `1` - `6` | 切换视觉模式 |
| `H` | 显示/隐藏帮助面板 |
| `P` | 暂停/播放 |
| `C` | 清除画布 |
| `Space` | 在鼠标位置产生随机流体 |
| `R` | 重置当前模式参数 |
| `F` | 切换全屏 |
| `Scroll` | 调整笔刷大小 |
| `Double Click` | 爆发效果 |
| `Right Click` | 清除画布 |

## 🚀 运行

直接在浏览器中打开 `index.html` 即可（需要 WebGL 支持）。

或使用本地服务器：

```bash
# Python 3
python -m http.server 8080

# Node.js
npx serve .
```

## 🔗 参考

- 原始项目：[PavelDoGreat/WebGL-Fluid-Simulation](https://github.com/PavelDoGreat/WebGL-Fluid-Simulation)
- 在线演示：[GitHub Pages](https://blankscreen-exe.github.io/webGL-fluid-simulation/)

## 📄 许可

MIT License — 原始流体引擎版权归 Pavel Dobryakov (2017) 所有。
