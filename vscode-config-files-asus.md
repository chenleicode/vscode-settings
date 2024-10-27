## asus

- settings.json

```json
{
  "editor.fontSize": 18,
  "editor.tabSize": 2,
  "editor.stickyScroll.enabled": false,
  "editor.mouseWheelZoom": true,
  "editor.guides.bracketPairs": "active",
  "editor.wordSeparators": "`~!@#$%^&*()=+[{]}\\|;:'\",.<>/?",
  "editor.foldingStrategy": "indentation",
  "editor.acceptSuggestionOnCommitCharacter": false,
  "editor.smoothScrolling": true,
  "editor.detectIndentation": false,
  "editor.minimap.enabled": false,
  "editor.hideCursorInOverviewRuler": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.unicodeHighlight.ambiguousCharacters": false,

  "workbench.startupEditor": "none",
  "workbench.layoutControl.enabled": false,
  "workbench.editor.enablePreview": false,
  "diffEditor.ignoreTrimWhitespace": false,
  "files.eol": "\n",
  "files.trimTrailingWhitespace": true,

  // markdown settings
  "[markdown]": {
    "files.trimTrailingWhitespace": false
  },
  "markdown-preview-github-styles.darkTheme": "dark_dimmed",
  "markdown.preview.markEditorSelection": false,

  "liveServer.settings.donotShowInfoMsg": true,
  "vue.autoInsert.dotValue": true,

  // prettier rules
  // 需要手动格式化文档，不会自动格式化文档
  "prettier.semi": false,
  "prettier.endOfLine": "auto",
  "prettier.printWidth": 100,
  "prettier.trailingComma": "none",
  "prettier.singleQuote": true,

  "[vue]": {
    "editor.defaultFormatter": "Vue.volar"
  },
  "window.newWindowProfile": "Default"
}
```
