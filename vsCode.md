# VSCODE settings and plugins

## VSCODE plugins :
```
- Active File in StatusBar
- Apache Conf
- Beautify
- Better Align
- Better Comments
- BootStrap 4 snippets
- Bracket Pair Colorizer
- Code Runner (Useful for JS development)
- Code Spell Checker
- CSS compressor
- CSS Peek
- Debugger for Chrome
- HandleBars (Useful for JS development)
- HTML CSS Support
- HTML Snippets
- indent-rainbow
- IntelliSense for CSS classNames
- JavaScript Code Snippets
- jQuery Code Snippets
- Live SASS compiler
- Live Server
- Material Icon Theme
- Pola Code
- px to rem
- SCSS intellisence
- SonarLint
- SPA js
- Trailing Spaces
- Web Snippets
```

## VSCODE Settings :

```json
{
"window.zoomLevel" : 0,
"window.titleBarStyle" : "custom",
"breadcrumbs.enabled" : true,
"workbench.startupEditor" : "newUntitledFile",
"workbench.statusBar.visible" : true,
"files.defaultLanguage" : "html",
"files.autoSave" : "off",
"editor.tabSize" : 2,
"editor.insertSpaces" : true,
"editor.minimap.enabled" : false,
"editor.tabCompletion" : "on",
"editor.renderWhitespace" : "all",
"editor.renderControlCharacters" : true,
"editor.multiCursorModifier" : "alt",
"emmet.triggerExpansionOnTab" : true,
"html.format.wrapAttributes" : "aligned-multiple",
"liveServer.settings.wait" : 500,
"liveServer.settings.port" : 0,
"liveServer.settings.NoBrowser" : false,
"liveServer.settings.CustomBrowser" : "chrome",
"liveServer.settings.donotShowInfoMsg" : true,
"liveServer.settings.ChromeDebuggingAttachment" : false,
"liveServer.settings.ignoreFiles" : [ ".vscode/**", "**/*.scss", "**/*.sass", "**/*.ts", "**/*.json" ],
"[javascript]" : { "editor.formatOnSave": false },
"[html]" : { "editor.formatOnSave": false },
"[css]" : { "editor.formatOnSave": false },
"[scss]" : { "editor.formatOnSave": false },
"trailing-spaces.trimOnSave" : true,
"editor.fontSize" : 18,
"update.mode" : "manual",
"workbench.iconTheme" : "material-icon-theme",
"editor.fontFamily" : "Consolas",
"editor.wordWrap" : "bounded",
"editor.wordWrapColumn" : 200,
"files.trimTrailingWhitespace" : true,
"terminal.integrated.fontSize" : 18,
"liveSassCompile.settings.generateMap" : false,
"liveSassCompile.settings.formats" : [ { "format": "compressed", "extensionName": ".css", "savePath": "/styles/" } ],
"liveSassCompile.settings.autoprefix" : null,
"alignment.surroundSpace" : { "colon": [ 1, 1 ] },
"html-css-class-completion.enableEmmetSupport" : true,
"git.ignoreLimitWarning" : true,
"editor.defaultFormatter" : "HookyQR.beautify",
"better-comments.highlightPlainText" : true,
"code-runner.clearPreviousOutput" : true,
"scss.lint.duplicateProperties" : "error",
"scss.lint.float" : "warning",
"scss.lint.idSelector" : "error",
"scss.lint.important" : "warning",
"scss.lint.unknownVendorSpecificProperties" : "warning",
"scss.lint.zeroUnits" : "warning",
"terminal.integrated.fontWeightBold" : "500",
"terminal.integrated.cursorBlinking" : true,
"workbench.panel.defaultLocation" : "right",
"workbench.colorCustomizations" : { "activityBar.activeBackground": "#1E1E1E", "activityBar.activeBorder": "#252526", "editor.lineHighlightBackground": "#121610", "editor.lineHighlightBorder": "#00796b", "tab.activeBorderTop": "#f5f5f5" },
"sonarlint.ls.javaHome" : "C:\\Program Files (x86)\\Java\\jre1.8.0_60",
"sonarlint.rules" : { "Web:BoldAndItalicTagsCheck": { "level" : "off" }, "Web:S5256": { "level" : "off" }, "Web:TableWithoutCaptionCheck": { "level" : "off" } },
"javascript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyParenthesis" : true,
"javascript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyBrackets" : true,
"css.lint.idSelector" : "warning",
"less.lint.idSelector" : "error",
"css.lint.duplicateProperties" : "error",
"less.lint.duplicateProperties" : "error",
"css.lint.emptyRules" : "error",
"css.lint.fontFaceProperties": "error",
"css.lint.unknownVendorSpecificProperties" : "warning",
"css.lint.zeroUnits" : "warning",
"cSpell.allowCompoundWords" : true,
"liveSassCompile.settings.showOutputWindow" : false,
"workbench.editor.limit.enabled" : true,
"workbench.editor.limit.value" : 16,
"editor.definitionLinkOpensInPeek" : true,
"emmet.preferences" : { "css.intUnit" : "rem", "css.floatUnit" : "rem" },
"editor.cursorBlinking" : "smooth",
"terminal.integrated.cursorStyle" : "line",
"terminal.integrated.cursorWidth" : 2,
"editor.renderLineHighlightOnlyWhenFocus" : true,
"editor.lineHeight" : 26,
"liveServer.settings.donotVerifyTags" : true,
"workbench.editor.enablePreviewFromQuickOpen" : false,
"workbench.editor.enablePreview" : false,
"css.lint.float": "warning",
"beautify.config": "C:\\Users\\jgopi01\\.vscode\\.jsbeautifyrc",
"CleanCSS.options": {
"format": {
	"breaks": { "afterRuleEnds": true },
	"spaces": { "aroundSelectorRelation": true, "beforeValue": true },
	"level" : 2
}
},
"editor.smoothScrolling": true,
"terminal.integrated.shell.windows": "cmd.exe",
"terminal.integrated.env.windows": {
"CMDER_ROOT": "C:\\Cmder"
},
"terminal.integrated.shellArgs.windows": [
"/k",
"C:\\Cmder\\vendor\\bin\\vscode_init.cmd"
],
}
```

## VSCODE keyboard shortcuts :
```json
[
  {
	"key": "ctrl+s",
	"command": "workbench.action.files.saveAll"
  },
  {
	"key": "ctrl+k s",
	"command": "-workbench.action.files.saveAll"
  },
  {
	"key": "ctrl+tab",
	"command": "workbench.action.nextEditor"
  },
  {
	"key": "ctrl+pagedown",
	"command": "-workbench.action.nextEditor"
  },
  {
	"key": "ctrl+shift+/",
	"command": "editor.action.blockComment",
	"when": "editorTextFocus && !editorReadonly"
  },
  {
	"key": "shift+alt+a",
	"command": "-editor.action.blockComment",
	"when": "editorTextFocus && !editorReadonly"
  },
  {
	"key": "ctrl+shift+a",
	"command": "wwm.aligncode",
	"when": "editorTextFocus && !editorReadonly"
  },
  {
	"key": "alt+u",
	"command": "editor.action.transformToUppercase"
  },
  {
	"key": "shift+alt+u",
	"command": "editor.action.transformToLowercase"
  },
  {
	"key": "ctrl+shift+d",
	"command": "editor.action.addSelectionToPreviousFindMatch"
  },
  {
	"key": "ctrl+shift+j",
	"command": "editor.action.formatSelection",
	"when": "editorHasDocumentSelectionFormattingProvider && editorHasDocumentSelectionFormattingProvider && editorTextFocus && !editorReadonly"
  },
  {
	"key": "ctrl+k ctrl+f",
	"command": "-editor.action.formatSelection",
	"when": "editorHasDocumentSelectionFormattingProvider && editorHasDocumentSelectionFormattingProvider && editorTextFocus && !editorReadonly"
  },
  {
	"key": "ctrl+k ctrl+f",
	"command": "workbench.files.action.collapseExplorerFolders"
  },
  {
	"key": "ctrl+shift+f",
	"command": "search.action.openNewEditor"
  },
  {
	"key": "ctrl+r",
	"command": "rerunSearchEditorSearch"
  },
  {
	"key": "ctrl+j",
	"command": "editor.action.joinLines"
  }
]
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTAwOTE1MjgzNF19
-->