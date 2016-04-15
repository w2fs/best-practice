# Atom

## 插件列表 / Plugin List

```
Community Packages (40) /Users/willin/.atom/packages
├── activate-power-mode@0.4.1
├── atom-beautify@0.29.2
├── atom-material-syntax@0.4.6
├── atom-material-ui@1.2.10
├── atom-terminal-panel@4.4.4
├── atom-ternjs@0.13.2
├── auto-update-packages@1.0.1
├── autoclose-html@0.23.0
├── autocomplete-modules@1.4.1
├── ava@0.3.1
├── color-picker@2.1.1
├── csslint@1.1.4
├── docblockr@0.7.3
├── file-icons@1.7.2
├── git-log@0.4.1
├── highlight-selected@0.11.2
├── hyperclick@0.0.35
├── js-hyperclick@1.4.2
├── language-babel@2.17.2
├── language-dots@0.0.4
├── linter@1.11.4
├── linter-eslint@7.2.0
├── merge-conflicts@1.4.1
├── minimap@4.21.0
├── minimap-git-diff@4.2.0
├── minimap-highlight-selected@4.4.0
├── minimap-pigments@0.2.0
├── open-in-browser@0.4.7
├── open-recent@5.0.0
├── pigments@0.26.0
├── project-manager@2.9.7
├── project-switcher@0.3.0
├── rest-client@1.0.0
├── seti-ui@0.9.2
├── simplified-chinese-menu@3.4.11
├── sort-lines@0.14.0
├── terminal-plus@0.14.5
├── todo-show@1.4.0
├── tool-bar@0.4.0
└── tool-bar-config@0.0.2
```

## config.cson

```
"*":
  "activate-power-mode":
    particles:
      size: {}
      spawnCount: {}
      totalCount: {}
    screenShake: {}
  "atom-beautify":
    apex: {}
    arduino: {}
    c: {}
    cfml: {}
    coffeescript:
      indent_size: 2
    cpp: {}
    cs: {}
    css: {}
    d: {}
    ejs: {}
    erb: {}
    fortran: {}
    general:
      _analyticsUserId: "ea162638-166c-40b5-835b-108ef72f93f3"
      analytics: false
    gherkin: {}
    handlebars: {}
    html:
      end_with_newline: true
      indent_inner_html: true
      indent_size: 2
      max_preserve_newlines: 1
    jade: {}
    java: {}
    js:
      beautify_on_save: true
      brace_style: "collapse-preserve-inline"
      end_with_comma: true
      end_with_newline: true
      indent_size: 2
      keep_function_indentation: true
    json:
      beautify_on_save: true
      indent_size: 2
    jsx: {}
    latex: {}
    less: {}
    marko: {}
    mustache: {}
    objectivec: {}
    pawn: {}
    perl: {}
    php: {}
    python: {}
    riot: {}
    ruby: {}
    rust: {}
    sass: {}
    scss: {}
    spacebars: {}
    sql: {}
    svg: {}
    swig: {}
    tss: {}
    twig: {}
    typescript: {}
    vala: {}
    visualforce: {}
    xml: {}
    xtemplate: {}
  "autoclose-html": {}
  autosave:
    enabled: true
  core:
    disabledPackages: [
      "atom-terminal-panel"
      "symbols-view"
    ]
    themes: [
      "atom-material-ui"
      "atom-material-syntax"
    ]
  editor:
    fontFamily: "'Source Code Pro for Powerline'"
    invisibles: {}
    showIndentGuide: true
    softWrap: true
  "exception-reporting":
    userId: "69f2bdd3-5fcf-f92b-ecd5-461248e4bd3f"
  "file-icons":
    onChanges: true
  "highlight-selected": {}
  "js-hyperclick": {}
  linter:
    errorPanelHeight: 32
    showErrorTabLine: true
  "linter-eslint": {}
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
  "terminal-plus":
    core:
      mapTerminalsTo: "Folder"
    style:
      fontFamily: "'Source Code Pro for Powerline'"
  "todo-show":
    ignoreThesePaths: [
      "**/node_modules/"
      "**/vendor/"
      "**/bower_components/"
      "**/public/"
    ]
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

## keymap.cson

(`快捷键`根据个人喜好和习惯设定 / up to your habit)


```
'atom-text-editor':
  'cmd-alt-l': 'atom-beautify:beautify-editor'
  'cmd-shift-l': 'atom-beautify:beautify-editor'
  'cmd-alt-j': 'activate-power-mode:toggle'
  'cmd-shift-j': 'activate-power-mode:toggle'
  'cmd-`': 'terminal-plus:toggle'
  'cmd-alt-up': 'pane:split-up'
  'cmd-alt-down': 'pane:split-down'
  'cmd-alt-left': 'pane:split-left'
  'cmd-alt-right': 'pane:split-right'
  'cmd-alt-shift-up':'window:focus-pane-on-up'
  'cmd-alt-shift-down':'window:focus-pane-on-down'
  'cmd-alt-shift-left':'window:focus-pane-on-left'
  'cmd-alt-shift-right':'window:focus-pane-on-right'
  'cmd-k':'pane:close'
  'cmd-1':'todo-show:find-in-project'
```
