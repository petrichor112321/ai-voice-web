
###  英文口语对话功能，是我目前认为实时语音最有意义的功能，如果遇不到一个口语标准的英语老师的话，可以和她对话，我测试后的感觉是，沉浸式真人对话体验，一点不夸张。

###  实时语音模型就我目前了解来看主要分 端到端 和 语音合成 两大类，两种都体验了下，肯定还是端到端的效果要好一些的，但语音合成的也还是不错的。

###  本项目旨在将ai实时语音对话能力快速接入到你的项目。官方前端有react版本，本项目基于官方示例实现，并在其基础上扩展了多角色功能。有其他需求的欢迎交流，希望能应用到一些实际生活中。

###  已实现将后端服务、web部署服务器，python版本3.11，，基本按照教程走没有什么太大问题，主要有问题的是ios移动浏览器端偶尔无法正常播放返回的TTS语音，待解决。

<p align="center">
  <img src="/role.png" alt="角色页" width="45%" style="margin-right: 10px;" />
  <img src="/chat.png" alt="聊天页" width="45%" />
</p>

## 🎬 演示视频

👉 [点击观看演示视频](https://aceiteach.hk/uploads/film/ai_voice.mp4)


本项目的整体流程架构如下：
![img.png](/img.png)


---
## 📦 技术栈

- **前端框架**：Vue 2  后续将更新vue3版本，因为官方没有react版本，飞书群也基本没人回复。。
- **后端框架**：python  具体使用方法见火山引擎官方文档
- **音频处理**：Web Audio API
- **通信协议**：WebSocket（支持 PCM 音频推送）
- **AI 模型**：豆包（Doubao），后续支持 GPT-4、Claude、百川等

---
## 🔍 项目简介

**AI Voice Web** 是一个专注于**实时语音交互体验**的 Web 前端项目，集成语音识别、实时 WebSocket 通信、语音合成播放等能力，适用于多种 AI 对话场景，如：

- 智能助理
- 教育问答
- 多模态客服
- AI 陪聊机器人

> 当前版本已对接 **字节跳动豆包模型（Doubao）**，未来将支持 GPT-4、Claude、Gemini 等主流大模型接口的灵活切换。

---

## ✨ 功能亮点

- 🎤 实时麦克风录音 + 波形可视化（支持移动端）
- 🔁 WebSocket 双向流式音频通信
- 🧠 AI 实时语音识别 + 文本生成
- 🔊 语音合成播放（支持 AudioContext 兼容性）
- 💬 字幕 / 消息记录模式切换
- 📱 移动端 iOS 浏览器兼容优化

---


## 🚧 未来规划

- ✅ 多模型适配（GPT / Claude / 百川 / 通义）
- ✅ 语音中断、打断重问机制
- ⏳ 多角色支持 

---
## 环境准备

- Poetry 1.6.1 版本
- Python 版本要求大于等于 3.8，小于 3.12
- Node 18.0 或以上版本 
- PNPM 8.10 或以上版本
- 获取语音技术产品的 APP ID 和 Access Token，获取方式参见【附录】
- 火山方舟 API KEY [参考文档](https://www.volcengine.com/docs/82379/1298459#api-key-%E7%AD%BE%E5%90%8D%E9%89%B4%E6%9D%83)
- 火山引擎 AK SK [参考文档](https://www.volcengine.com/docs/6291/65568)
- 创建 Doubao-Pro 32K 的endpoint [参考文档](https://www.volcengine.com/docs/82379/1099522)


商务合作请联系，有更多想法的开发者也可以分享想法，看有没有机会落地实现。
联系方式：
<p align="center">
  <img src="/code.jpg" alt="code" width="45%"  />
</p>





