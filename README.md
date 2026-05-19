# js版文曲星nc1020模拟器
## 网页版文曲星nc1020[模拟器](https://leoncoolmoon.github.io/jswqx/) <br>

基于 JavaScript 的文曲星 NC1020 模拟器，从原基础上修改增加了现代化的图形界面。

![screenshot](./nc1020.png)

### 功能特点
- **高度还原的 UI**: 精心设计的硬件外壳界面，支持硬件精度的 LCD 指示器（三角标）。
- **移动端优化**: 自适应布局，支持触摸屏操作，横屏模式自动优化。
- **持久化存储**: 自动保存 NOR Flash 和 RAM 状态到浏览器 `localStorage`，确保进度不丢失。
- **PWA 支持**: 支持离线使用，可作为桌面或移动端应用安装。
- **多主题支持**: 内置深色和浅色模式，并可随系统自动切换。
- **全屏模式**: 支持全屏体验，在桌面端可单独全屏 LCD 显示区域。
- **高性能**: 优化的 6502 CPU 仿真和 LCD 渲染。

### 历史与致谢
- Original: http://bbs.emsky.net/viewthread.php?tid=33474
- 2018.09.11 Dr.Quest 优化版：压缩 ROM 到 10M ZIP 文件，添加了手机触摸屏支持。
- 2023.12.24 leoncoolmoon 修改了 UI，增加 Ctrl 为跳出键。
- 2026.05.17 leoncoolmoon 修复了 Flash 存储，可以在浏览器内永久化保存。
- 2026.05.19 升级为 PWA，支持离线访问，移除对本地 Python 服务器的依赖。

### 使用说明
直接在支持现代 Web 标准的浏览器中打开 `index.html` 即可。由于使用了 Service Worker 和 Web Worker (可能)，建议通过 Web 服务器访问（如 GitHub Pages）。

目前已在 Chrome 和 iOS Safari 上进行过测试。
