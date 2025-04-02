## asus

- settings.json

```json
{
  "editor.fontSize": 16,
  "editor.tabSize": 2,
  "editor.stickyScroll.enabled": false,
  "editor.mouseWheelZoom": true,
  "editor.guides.bracketPairs": "active",
  "editor.wordSeparators": "`~!@#$%^&*()=+[{]}\\|;:'\",.<>/?",
  "editor.foldingStrategy": "indentation",
  "editor.acceptSuggestionOnCommitCharacter": false,
  "editor.smoothScrolling": true,
  "editor.detectIndentation": false,
  "editor.hideCursorInOverviewRuler": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.unicodeHighlight.ambiguousCharacters": false,
  "editor.minimap.enabled": false,
  "editor.quickSuggestionsDelay": 100,
  "editor.hover.delay": 1000,

  "workbench.editor.wrapTabs": true,
  "workbench.startupEditor": "none",
  "workbench.layoutControl.enabled": false,
  "workbench.editor.enablePreview": false,
  "workbench.navigationControl.enabled": false,

  "files.eol": "\n",
  "files.trimTrailingWhitespace": true,

  "window.newWindowProfile": "Default",
  "window.menuBarVisibility": "classic",
  "window.title": "${dirty}${remoteName}${separator}${rootNameShort}",

  "terminal.integrated.defaultProfile.windows": "PowerShell",
  "terminal.integrated.suggest.enabled": true,

  // git
  "git.blame.editorDecoration.enabled": true,
  "git.blame.statusBarItem.enabled": true,
  "git.branchSortOrder": "alphabetically",
  "diffEditor.ignoreTrimWhitespace": false,

  "liveServer.settings.donotShowInfoMsg": true,

  // prettier rules
  "prettier.semi": false,
  "prettier.endOfLine": "auto",
  "prettier.printWidth": 100,
  "prettier.trailingComma": "none",
  "prettier.singleQuote": true,

  // vue
  "vue.autoInsert.dotValue": true,
  "[vue]": {
    "editor.defaultFormatter": "Vue.volar"
  },

  // markdown
  "markdown.preview.markEditorSelection": false,
  "markdown-preview-github-styles.darkTheme": "dark_dimmed",
  "[markdown]": {
    "files.trimTrailingWhitespace": false
  },

  "emmet.variables": {
    "lang": "zh-CN"
  },

  "projectManager.openInNewWindowWhenClickingInStatusBar": true,

  "github.copilot.enable": {
    "*": true,
    "plaintext": false,
    "markdown": true,
    "scminput": false
  }
}
```
