<p align="center">
  <a href="https://tools.video">
    <img src="assets/logo.png" alt="tools.video" width="120" />
  </a>
</p>

<h1 align="center">tools.video</h1>

<p align="center">
  <strong>免费、快速、隐私优先的浏览器端音视频工具。</strong><br>
  无需上传。无需注册。开箱即用。
</p>

<p align="center">
  <a href="README.md">English</a> •
  <strong>简体中文</strong> •
  <a href="README.ja.md">日本語</a> •
  <a href="README.es.md">Español</a>
</p>

<p align="center">
  <a href="https://tools.video">🌐 访问网站</a> •
  <a href="#工具列表">🛠 全部工具</a> •
  <a href="#产品特性">✨ 特性</a> •
  <a href="#隐私保护">🔒 隐私</a> •
  <a href="#技术栈">⚡ 技术</a>
</p>

---

## 什么是 tools.video？

**tools.video** 是一套 18 个免费在线音视频工具，**完全在浏览器中运行**。你的文件不会离开你的设备——所有处理都在本地完成，利用最前沿的 Web 技术。

访问 **[tools.video](https://tools.video)** 即可开始使用。就这么简单。

---

## 工具列表

### 视频工具

| 工具 | 功能 |
|------|------|
| **[视频压缩](https://tools.video/zh-CN/video-compress)** | 压缩视频最高减少 90% 体积，同时保持画质 |
| **[格式转换](https://tools.video/zh-CN/video-convert)** | 在 MP4、MKV、AVI、WebM、MOV 等 10+ 格式间互转 |
| **[视频裁剪](https://tools.video/zh-CN/video-trim)** | 可视化时间线，支持帧级精度剪辑 |
| **[变速处理](https://tools.video/zh-CN/video-speed)** | 0.25× 到 4× 变速，平滑调节 |
| **[画面裁切](https://tools.video/zh-CN/video-crop)** | 自由裁切，支持 13 种预设比例和自定义尺寸 |
| **[视频缩放](https://tools.video/zh-CN/video-resize)** | 缩放到任意分辨率——4K、1080p、720p 或自定义 |
| **[视频合并](https://tools.video/zh-CN/video-merge)** | 将多个片段合并为一个完整视频，支持拖拽排序 |
| **[视频旋转](https://tools.video/zh-CN/video-rotate)** | 旋转 90°/180°/270° 或水平/垂直翻转 |
| **[视频截图](https://tools.video/zh-CN/video-screenshot)** | 在任意时间点截取画面，支持逐帧浏览 |
| **[视频倒放](https://tools.video/zh-CN/video-reverse)** | 倒放视频，可选保留音频 |
| **[移除音轨](https://tools.video/zh-CN/video-mute)** | 一键去除视频中的音频 |
| **[视频转 GIF](https://tools.video/zh-CN/video-to-gif)** | 将视频片段转为 GIF 动图 |

### 音频工具

| 工具 | 功能 |
|------|------|
| **[音频提取](https://tools.video/zh-CN/audio-extract)** | 从视频中提取音频，支持 MP3、WAV、FLAC、AAC 等格式 |
| **[音频转换](https://tools.video/zh-CN/audio-convert)** | 在 16+ 种音频格式间互转 |
| **[音频裁剪](https://tools.video/zh-CN/audio-trim)** | 波形可视化编辑器，精准裁剪 |
| **[音频合并](https://tools.video/zh-CN/audio-merge)** | 将多个音频文件合并为一个 |
| **[音频变速](https://tools.video/zh-CN/audio-speed)** | 调整音频速度，支持音调调节 |

### 实用工具

| 工具 | 功能 |
|------|------|
| **[媒体信息](https://tools.video/zh-CN/media-info)** | 查看编解码器、比特率、分辨率、音视频流等详细信息 |

---

## 产品特性

### 📦 支持最大 50 GB 文件

4K 素材、8K RAW 导出、数小时录制——再大的文件都能处理。没有上传限制、没有服务器超时、没有画质损失。

### 🎞 支持几乎所有格式

**视频：** MP4、WebM、MKV、AVI、MOV、FLV、WMV、M4V、TS  
**音频：** MP3、WAV、FLAC、AAC、OGG、WMA、M4A、OPUS、AIFF、DTS、AC3、EAC3、APE、AMR、MKA  
完整支持多声道音频，包括 5.1 和 7.1 环绕声。

### ⚡ 极致快速

双引擎架构驱动：
- **MediaBunny** — 基于 WebCodecs API，硬件加速处理大文件
- **FFmpeg.wasm** — WebAssembly 编译，最大化格式兼容性

多线程处理，充分利用你设备的全部性能。

### 🔒 100% 隐私保护

你的文件**绝不会离开你的设备**。没有上传、没有服务器处理、没有进度条等待。你的数据只属于你。

### 🚀 零门槛使用

无需下载、无需安装、无需注册、无需账号。打开网页，拖入文件，即刻开始。

---

## 隐私保护

我们对隐私的承诺：

- **零上传** — 所有处理在浏览器中完成
- **无服务端处理** — 文件始终留在你的设备上
- **不追踪文件内容** — 我们从不查看或分析你的媒体文件
- **无需账号** — 所有工具匿名使用

---

## 技术栈

tools.video 使用现代 Web 技术构建：

- **[Next.js 15](https://nextjs.org/)** — 带 SSR 的 React 框架，优化 SEO
- **[MediaBunny](https://mediabunny.dev/)** — 基于 WebCodecs 的媒体处理引擎
- **[FFmpeg.wasm](https://ffmpegwasm.netlify.app/)** — FFmpeg 的 WebAssembly 编译版本
- **[SharedArrayBuffer](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/SharedArrayBuffer)** — 浏览器中的多线程处理
- **19 种语言** — 面向全球用户的本地化支持

---

## 相关链接

- 🌐 **网站：** [tools.video](https://tools.video)
- 📧 **联系：** [support@tools.video](mailto:support@tools.video)
- 🎬 **母产品：** [SubEasy.ai](https://www.subeasy.ai) — AI 转录、翻译与配音平台

---

## 许可

tools.video 是专有产品。本仓库仅包含文档说明。

© 2025 tools.video. 保留所有权利。
