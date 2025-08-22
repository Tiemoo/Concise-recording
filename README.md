# Concise Recording
一个轻量级、无广告的 Windows 屏幕录制工具。  
基于 Python + PyQt6 + OpenCV，单文件即可运行，不写注册表、不留垃圾。

---

## 功能
- 区域/全屏录制
- 实时帧率选择
- 开始 <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>R</kbd>
- 暂停 <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>P</kbd>
- 停止 <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>S</kbd>
- 录制完成后自动保存为 `mp4`，文件名带时间戳
- 支持打包为exe

---

## 快速开始

### 1. 直接运行源码
```bash
git clone https://github.com/Tiemoo/Concise-recording.git
cd Concise-recording
pip install -r requirements.txt
python Concise-recording.py
```
---
## 一键打包单文件
### 1.安装开发依赖
```bash
pyinstaller -F -w -i logo.ico Concise-recording.py
```
生成的 exe 在 dist/ 目录。


其中添加了打赏作者功能，如果不需要可以去掉打赏部分的代码。

---

