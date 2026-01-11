# chatgpt-virtual-scrollGPT-
Fix ChatGPT web lag on long conversations using smart virtual scrolling. 解决 ChatGPT 网页长对话卡顿的虚拟滚动引擎,GPT网页版优化工具
# ChatGPT Virtual Scroll Engine

Fix ChatGPT web lag on long conversations using smart virtual scrolling.  
解决 ChatGPT 网页长对话卡顿的虚拟滚动引擎。

---

## 🚀 What is this?

When ChatGPT conversations become very long, the web page becomes slow, freezes, or crashes.  
This happens because **thousands of message DOM nodes remain in memory at once**.

This project solves that by introducing:

**Virtual Scrolling for ChatGPT Web UI**  
Only the messages near your screen are kept in memory.  
Old messages are safely compressed into placeholders and restored when you scroll back.

Result:  
✔ Smooth scrolling  
✔ Low memory usage  
✔ No data loss  
✔ Unlimited long conversations  

---

## 🇨🇳 这是什么？

当你和 ChatGPT 聊天记录非常长时，网页会越来越卡，甚至崩溃。  
原因是：**浏览器一次性加载了几千条对话 DOM 节点，占满了内存。**

这个插件通过“虚拟滚动引擎”解决这个问题：

只保留当前屏幕附近的对话  
自动压缩屏幕外的历史消息  
需要时再无损恢复  

效果：  
✔ 不再卡顿  
✔ 内存稳定  
✔ 可以无限长聊  
✔ 不丢任何内容  

---

## 🧠 Key Features

- Smart virtual scrolling (auto hide far messages)
- Real-time DOM & memory monitor
- iOS-style Performance / Balanced / Conservative modes
- Safe restore of old messages
- No network, no tracking, no data upload
- Works on ChatGPT Web (chat.openai.com / chatgpt.com)

---

## 🖥️ Live Dashboard

The plugin shows a small floating indicator near the ChatGPT model switch:

- 🟢 Green = healthy  
- 🟡 Yellow = heavy  
- 🔴 Red = memory danger  

Click it to see:

- DOM node count  
- JS memory usage  
- Virtualized messages  
- Conversation turns  
- Recommended remaining turns  

---

## ⚙️ Modes

| Mode | Description |
|------|------------|
| **Performance** | Maximum memory saving, minimal history kept |
| **Balanced** | Best for daily use |
| **Conservative** | Keeps more history for reading old messages |

You can switch modes live with an iOS-style segmented control.

---

## 📦 Installation

This is a UserScript.

1. Install a userscript manager  
   - Tampermonkey (Chrome / Edge)  
   - Violentmonkey (Firefox)

2. Install this script  
   Copy the script from this repository and paste it into Tampermonkey.

3. Open  
   https://chat.openai.com  
   or  
   https://chatgpt.com  

The floating dashboard will appear automatically.

---

## 🔐 Privacy & Security

This script:

- Runs 100% locally
- Sends NO data anywhere
- Reads only ChatGPT page DOM
- Does not track, log or store your conversations

It is safe for work, study, and private usage.

---

## ❤️ Support the Author

If this tool helps you work faster or prevents losing conversations, you can support development:

- GitHub ⭐ Star  
- GitHub Issues / Suggestions  
- WeChat / Alipay donation (QR code in repo)

Your support keeps this project alive.

---

## 🧩 License

MIT License  
Free to use, modify, distribute, and include in commercial products.  
Attribution appreciated.

---

## 📌 Roadmap

Planned:

- One-click export + open new chat
- Edge / Chrome packaged extension
- Mobile-friendly dashboard
- More memory diagnostics
- Auto-backup before danger level

---

Made with ❤️ for everyone who lives in long ChatGPT conversations.
