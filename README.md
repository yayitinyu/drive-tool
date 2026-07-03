# LinkCanvas

一个零依赖的图片链接格式转换工具。支持 Google Drive 分享链接和任意 HTTP(S) 图片直链，并生成以下格式：

- URL
- Markdown
- HTML
- BBCode

## 功能

- 一键读取剪贴板并转换
- 自动识别 Google Drive 分享链接
- 任意图片直链格式化
- 浅色 / 深色主题并记忆用户选择
- 本地历史记录、恢复、单条删除和清空
- 响应式布局与键盘可访问性

## 使用

直接打开 `index.html` 即可。若要使用浏览器剪贴板读取功能，请通过 HTTPS 或 localhost 访问，例如：

```powershell
python -m http.server 8000
```

然后访问 `http://localhost:8000`。

所有转换和历史数据都只在当前浏览器中处理。
