# 🎆 2026 跨年手势交互倒计时

一个充满仪式感的跨年倒计时网页，结合个人回忆照片、震撼的粒子特效和手势交互，打造浪漫、唯美、酷炫的跨年体验。

## 🎬 演示视频

[![演示视频](https://img.shields.io/badge/🎬-观看演示-brightgreen)](https://github.com/wangyiyong/NewYearMagicNum/releases/download/demo-video/demo.mp4)

**[点击观看完整演示视频](https://github.com/wangyiyong/NewYearMagicNum/releases/download/demo-video/demo.mp4)** 🎆

*或在 Releases 页面下载：[demo-video](https://github.com/wangyiyong/NewYearMagicNum/releases/tag/demo-video)*

## ✨ 功能特性

### 📸 阶段一：记忆相机
- 拍立得风格的相机界面，上传 3 张以上照片
- 星空呼吸背景 + 流星划过 + 极光效果
- 拍立得照片展示动画

### ⏰ 阶段二：粒子倒计时
- 五彩缤纷的粒子倒计时（10 → 1）
- 粒子汇聚成 "2026" 字样
- 大量烟花发射 + 满屏流星雨 + 红包雨

### 🎊 阶段三：手势交互
- 实时手势识别（基于 MediaPipe）
- 握拳抓取红包，张开手掌查看内容
- 随机展示你的照片 + 网络热门祝福语
- 金色福字红包飘落效果

## 🚀 快速开始

### 在线体验
直接用浏览器打开 `NewYearMagicNum.html` 即可体验

### 本地运行
```bash
# 克隆项目
git clone <your-repo-url>

# 用浏览器打开
open NewYearMagicNum.html
# 或双击文件在浏览器中打开
```

### 使用说明
1. 点击快门上传 3 张以上照片
2. 等待拍立得照片展示完成
3. 欣赏 10 秒倒计时 + 烟花表演
4. 握拳抓取红包，张开手掌查看祝福

## 🛠️ 技术栈

- **纯 HTML5 + JavaScript** - 无需构建，打开即用
- **Canvas API** - 粒子特效、烟花、星空
- **MediaPipe Hands** - 实时手势识别
- **Camera Utils** - 摄像头调用

## 📦 项目结构

```
.
├── NewYearMagicNum.html    # 主程序
├── README.md                # 项目说明
└── 需求说明.md              # 需求文档
```

## 🎨 视觉效果

- ⭐ 星空呼吸闪烁
- 🌠 流星划过天际
- 🌌 极光流动效果
- 🎆 五彩缤纷烟花
- 🧧 金色福字红包
- ✨ 粒子倒计时特效

## 📝 祝福语

内置 50+ 条 2025 年网络热门祝福语，包括：
- "和自己和解，允许一切发生"
- "人生是旷野，不是轨道"
- "愿你被这个世界温柔以待"
- "生活原本沉闷，但跑起来就有风"
- ...

## 🌐 浏览器兼容性

- Chrome / Edge (推荐)
- Safari
- Firefox

需要支持：
- Canvas API
- WebRTC (摄像头访问)
- ES6+

## ⚠️ 注意事项

1. **摄像头权限**：首次打开需要允许摄像头访问（用于手势识别）
2. **HTTPS**：在非 localhost 环境下需要 HTTPS 协议才能访问摄像头
3. **移动端**：建议在手机端横屏体验效果更佳

## 📸 社交分享

体验完成后，可以截图或录屏分享到：
- 抖音 / 小红书
- 朋友圈
- 微博

带上标签：`#跨年倒计时` `#仪式感` `#2026跨年`

## 🎯 未来计划

- [ ] 添加更多烟花形状（心形、星形）
- [ ] 支持自定义祝福语
- [ ] 添加背景音乐
- [ ] 支持保存倒计时视频

## 📄 开源协议

MIT License

---

**🎉 愿你的 2026，万物皆可期待！**
