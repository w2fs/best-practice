# Atom

插件列表

```
/Users/willin/.atom/packages (32)
├── activate-power-mode@0.4.1
├── atom-beautify@0.28.26
├── autoclose-html@0.23.0
├── autocomplete-modules@1.4.1
├── color-picker@2.1.1
├── csslint@1.1.4
├── file-icons@1.6.18
├── git-log@0.4.1
├── highlight-selected@0.11.2
├── hyperclick@0.0.35
├── js-hyperclick@1.4.1
├── language-babel@2.16.0
├── language-dots@0.0.4
├── linter@1.11.3
├── linter-eslint@7.1.1
├── merge-conflicts@1.3.7
├── minimap@4.21.0
├── minimap-git-diff@4.2.0
├── minimap-highlight-selected@4.4.0
├── minimap-pigments@0.2.0
├── open-recent@5.0.0
├── pigments@0.24.5
├── project-manager@2.7.6
├── project-switcher@0.3.0
├── rest-client@1.0.0
├── simplified-chinese-menu@3.4.11
├── sort-lines@0.14.0
├── terminal-plus@0.14.5
├── todo-show@1.4.0
├── tool-bar@0.4.0
└── tool-bar-config@0.0.2
```

config.cson

```
"*":
  "activate-power-mode":
    particles:
      size: {}
      spawnCount: {}
      totalCount: {}
    screenShake: {}
  "atom-beautify":
    js_end_with_newline: true
  autosave:
    enabled: true
  core:
    disabledPackages: [
      "symbols-view"
    ]
  editor:
    invisibles: {}
    softWrap: true
  "highlight-selected": {}
  "js-hyperclick": {}
  linter: {}
  "merge-conflicts": {}
  minimap:
    plugins:
      "git-diff": true
      "git-diffDecorationsZIndex": 0
      "highlight-selected": true
      "highlight-selectedDecorationsZIndex": 0
      pigments: true
      pigmentsDecorationsZIndex: 0
  "rest-client": {}
  "simplified-chinese-menu": {}
  "tool-bar":
    position: "Left"
  "tool-bar-config": [
    {
      icon: "document"
      iconSet: "ion"
      title: "New File"
      callback: "application:new-file"
    }
    {
      icon: "folder"
      iconSet: "ion"
      title: "Open..."
      callback: "application:open-folder"
    }
    {
      icon: "archive"
      iconSet: "ion"
      title: "Save"
      callback: "core:save"
    }
    {
      icon: "spacer"
    }
    {
      icon: "search"
      iconSet: "ion"
      title: "Find in Buffer"
      callback: "find-and-replace:show"
    }
    {
      icon: "shuffle"
      iconSet: "ion"
      title: "Replace in Buffer"
      callback: "find-and-replace:show-replace"
    }
    {
      icon: "spacer"
    }
    {
      icon: "navicon-round"
      iconSet: "ion"
      title: "Toggle Command Palette"
      callback: "command-palette:toggle"
    }
    {
      icon: "gear-a"
      iconSet: "ion"
      title: "Open Settings View"
      callback: "settings-view:open"
    }
    {
      icon: "spacer"
    }
    {
      icon: "refresh"
      iconSet: "ion"
      title: "Reload Window"
      callback: "window:reload"
    }
  ]
  welcome:
    showOnStartup: false
```

keymap.cson (`快捷键`根据个人喜好和习惯设定)

```
'atom-text-editor':
  'cmd-alt-l': 'atom-beautify:beautify-editor'
  'cmd-alt-j': 'atom-beautify:beautify-editor'
  'cmd-alt-i': 'activate-power-mode:toggle'
  'cmd-`': 'terminal-plus:toggle'
```
