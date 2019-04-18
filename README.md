# Github Markdown 主题（中文修正版）

参考来源：
<https://github.com/mjbvz/vscode-github-markdown-preview-style/blob/master/github-markdown.css>

## 更改内容

添加 `"Microsoft YaHei"` 一项

```css
.vscode-body{
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", "Microsoft YaHei", Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
}
```

## 使用方式

在 `setting.json` 中添加

```json
"markdown.styles": [
    "/path/to/github-markdown.css"
]
```

或

```json
"markdown.styles": [
    "https://cosmolin.github.io/vscode-github-markdown-style/github-markdown.css"
]
```