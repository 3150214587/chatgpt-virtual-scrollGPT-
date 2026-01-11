# 🚀 **ChatGPT Virtual Scroll Engine**  
### **ChatGPT 网页长对话虚拟滚动引擎**
link：https://openuserjs.org/scripts/Mr._K,_The_Creator/Better_ChatGPT_Assistant%EF%BC%88%E6%9B%B4%E5%A5%BD%E7%9A%84ChatGPT%E7%BD%91%E9%A1%B5%E7%89%88%E5%A4%9A%E5%8A%9F%E8%83%BD%E5%A2%9E%E5%BC%BA%E5%B0%8F%E5%8A%A9%E6%89%8B%EF%BC%89
**Below is the bilingual introduction in Chinese and English:**  
**以下为中英文双语介绍：**

Fix ChatGPT web lag on long conversations using smart virtual scrolling.  
使用智能虚拟滚动技术，解决 ChatGPT 网页版长对话卡顿问题。

---

# 🚀 **What is this? | 这是什么？**

When ChatGPT conversations become very long, the web page becomes slow, freezes, or crashes.  
This happens because **thousands of message DOM nodes stay in memory at the same time**.

当你在 ChatGPT 网页版中进行超长对话时，页面会越来越卡，甚至崩溃。  
这是因为 **成千上万条消息 DOM 节点被同时加载进内存**。

This project introduces a **Virtual Scroll Engine** for ChatGPT Web UI.  
It only keeps messages near your screen, and safely compresses everything else.

本项目为 ChatGPT 网页端提供了一套 **虚拟滚动引擎**：  
只保留当前屏幕附近的对话内容，远处的历史消息自动压缩，在需要时无损恢复。

**Result / 效果：**

- Smooth scrolling  
- Stable memory  
- Unlimited conversation length  

- 滚动流畅  
- 内存稳定  
- 可无限长对话  

---

# 🧠 **Key Features | 核心功能**

- Smart virtual scrolling for long conversations  
- Real-time DOM & memory monitor  
- Performance / Balanced / Conservative modes  
- iOS-style floating dashboard  
- No network, no tracking, no data upload  

- 智能虚拟滚动，解决长对话卡顿  
- 实时 DOM 与内存监控  
- 三种性能模式（性能 / 平衡 / 保守）  
- iOS 风格悬浮仪表盘  
- 本地运行，无联网、无追踪、无上传  

---

# 🖥️ **Live Dashboard | 实时仪表盘**

A small floating indicator is shown near the ChatGPT model switch.  
在 ChatGPT 模型切换按钮旁边，会显示一个小状态指示器。

**Status Colors | 状态灯：**

- 🟢 Green = Healthy  
- 🟡 Yellow = Heavy  
- 🔴 Red = Danger  

- 🟢 绿色 = 状态良好  
- 🟡 黄色 = 负载偏高  
- 🔴 红色 = 内存危险  

**Click to view | 点击后可查看：**

- DOM node count（DOM 节点数）  
- JS heap memory（JS 内存）  
- Virtualized messages（已虚拟化消息数）  
- Conversation turns（对话轮数）  
- Recommended remaining turns（推荐剩余可聊轮数）  

---

# ⚙️ **Modes | 性能模式**

| Mode | Description | 说明 |
|------|-------------|------|
| **Performance** | Maximum memory saving | 最省内存，最激进虚拟化 |
| **Balanced** | Best for daily use | 推荐模式，平衡性能与可读性 |
| **Conservative** | Keeps more history | 保留更多历史，适合查旧内容 |

You can switch modes in real time using the iOS-style segmented control.  
你可以用 iOS 风格的滑动按钮随时切换模式。

---

# 📦 **Installation | 安装方法**
  方法1：https://openuserjs.org/scripts/Mr._K,_The_Creator/Better_ChatGPT_Assistant%EF%BC%88%E6%9B%B4%E5%A5%BD%E7%9A%84ChatGPT%E7%BD%91%E9%A1%B5%E7%89%88%E5%A4%9A%E5%8A%9F%E8%83%BD%E5%A2%9E%E5%BC%BA%E5%B0%8F%E5%8A%A9%E6%89%8B%EF%BC%89
浏览器点击链接安装油猴脚本，前提是你有油猴插件

  方法2：
This is a UserScript.  
这是一个油猴脚本。

1. **Install a userscript manager | 安装脚本管理器**
   - Tampermonkey (Chrome / Edge)  
   - Violentmonkey (Firefox)

2. **Install this script | 安装脚本**  
   复制本仓库中的脚本代码，粘贴到 Tampermonkey 中保存。

3. **Open ChatGPT | 打开**  
   https://chat.openai.com  
   or  
   https://chatgpt.com  

The dashboard will appear automatically.  
仪表盘会自动显示。

---

# 🔐 **Privacy & Security | 隐私与安全**

This script:

- Runs 100% locally  
- Sends no data anywhere  
- Does not record or upload conversations  

本脚本：

- 完全本地运行  
- 不向任何服务器发送数据  
- 不记录、不上传你的聊天内容  

Safe for personal and professional use.  
可安全用于学习、工作和私人对话。

---

# 📖 **How to Use | 使用教程**

### **1️⃣ After Installation | 安装完成后**
打开 ChatGPT 后，你会在模型切换按钮旁边看到一个小圆点（状态灯）。

### **2️⃣ Dot Colors | 小圆点含义**
🟢 正常 🟡 偏高 🔴 危险

### **3️⃣ Click to open panel | 点击打开面板**
查看 DOM、内存、对话轮数与推荐剩余。

### **4️⃣ Choose Mode | 选择模式**
性能 / 平衡 / 保守，可随时切换。

### **5️⃣ Pause or Enable | 暂停或启用**
暂停显示全部历史，启用则节省内存更流畅。

### **6️⃣ Red Warning | 红色怎么办**
点击 **强制清理** 立刻释放内存。

### **7️⃣ Ctrl + F**
搜索时自动恢复所有历史，搜索完自动继续加速。

### **8️⃣ Pin & Drag | 钉住拖动**
📌 可拖到屏幕边缘自动隐藏。

### **9️⃣ When to start new chat | 何时新开**
长期红色或黄色 → 备份 → 新对话。

---

# ❤️ **Support the Author | 支持作者**

If this tool helps you, you can support development by:

如果这个工具帮到了你，你可以通过以下方式支持作者：

- GitHub Star ⭐  
- Submitting issues or suggestions  
- Donation (WeChat / Alipay QR code in repo)  

---

# 🧩 **License | 开源协议**

MIT License – Free to use, modify and distribute.  
MIT 开源协议，可自由使用与修改。

---

# 📌 **Roadmap | 开发计划**

- One-click export & new chat  
- Edge / Chrome extension  
- Automatic memory cleanup  
- Mobile-friendly UI  

---

## ☕ **Buy Me a Coffee | 微信赞赏**

If this project helps you, consider supporting the author ❤️  
如果这个项目帮到了你，欢迎支持作者喝杯咖啡 ❤️  
paypal：https://paypal.me/DKW3588
<p align="center">
  <img src="./donate-wechat.png" width="460" alt="WeChat Donate QR">
</p>

**Your support keeps this project alive and improving.**  
**你的支持将帮助这个项目持续维护与进化。**

Thank you for your kindness 🙏  
感谢你的善意  

---
