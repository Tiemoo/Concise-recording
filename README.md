# Concise Recording
一个轻量级、极致低占用 Windows 屏幕录制工具。 
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
python Concise-recording_tips.py
```
---
## 一键打包单文件
### 1.打包exe
```bash
pyinstaller -F -w -i logo.ico Concise-recording_tips.py
```
生成的 exe 在 dist/ 目录。


其中添加了打赏作者功能，如果不需要可以去掉打赏部分的代码。

---
## MIT许可证

版权所有（c）2025 Tiemoo

特此向任何人免费授予获取本软件及相关文档文件副本的权限（“软件”），不受限制地处理软件，包括但不限于使用、复制、修改、合并、发布、分发、再许可和/或出售软件副本的权利，以及允许软件提供给的人这样做的权利，但须符合下列条件：

1. 上述版权声明和本许可声明应包含在本软件的所有副本或主要部分中。

2. 用于接收付款的嵌入式Base64编码的微信和支付宝QR码，以及其任何复制或衍生物，均明确排除在上述许可之外。 未经版权保持器持有人事先书面同意，严禁使用、复制或分发这些QR码，无论是原始形式还是修改形式。

本软件按“原样”提供，不提供任何明示或暗示得担保，包括但不限于对适销性，特定用途得适用性与非侵权性得担保. 在任何情况下，作者或版权所有者均不对任何索赔、损害或其他责任负责，无论是合同诉讼、侵权行为还是其他，这些索赔、损害或其他责任是由本软件或本软件的使用或其他交易引起的、与之相关的。
