# HiAuRo.WebTools

HiAuRo 的独立静态网页工具集合。

当前包含：

- `editor.html`：树形轴编辑器
- `axflow-editor.html`：Flow 轴编辑器
- `fact-editor.html`：事实轴编辑器
- `combat-recorder.html`：Combat Recorder 阅读器

这些页面设计为脱离宿主 WebUI 独立运行：

- 轴编辑器通过手动导入本地 `trigger-catalog.json` 使用
- 录制阅读器通过本地文件选择打开日志

不包含宿主在线控制面板页面：

- `main.html`
- `jobview.html`
- `qt.html`
- `hotkey.html`
- `app.js`

