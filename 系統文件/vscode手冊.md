# vscode 配置手冊

* 空格顯示打開
    1. F1 輸入 usersetting 打開偏好設定.
    1. 搜尋框中輸入 'renderWhitespace', 選擇all, 即可顯示空格.

* 切換 sideBar 到右邊
    1. F1 輸入 sidebarposition, 按下後就切換到另一側.

* 使用繁中介面
    1. F1 輸入 display, 選擇 'Configure Display Language'.
    1. 選擇  Install additional languages...
    1. 從列表中選擇'繁中'安裝即可.

* setting.json 設定

``` JS
{
    "update.mode": "none",
    "search.seedOnFocus": true,
    "window.zoomLevel": 1,
    "workbench.sideBar.location": "right",
    "editor.fontSize": 12,
    "workbench.iconTheme": "material-icon-theme",
    "editor.minimap.enabled": false,
    "editor.renderControlCharacters": true,
    "editor.renderWhitespace": "all",
    "markdownFormatter.codeAreaToBlock": "js",
    "markdownFormatter.formatOpt": {
        "indent": 4,
        "brace_style": "collapse-preserve-inline",
        "end_with_newline": false
    },
    "[markdown]": {
        // 快速补全
        "editor.quickSuggestions": {
            "other": true,
            "comments": true,
            "strings": true
        },
    },
}
```
