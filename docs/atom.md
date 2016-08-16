# Atom

## 插件列表 / Plugin List

```
Community Packages (49) /Users/willin/.atom/packages
├── activate-power-mode@0.7.4
├── atom-beautify
├── atom-jade@0.3.0
├── atom-material-syntax@0.4.6
├── atom-material-ui@1.3.3
├── atom-terminal-panel@4.4.4
├── atom-ternjs@0.14.2
├── atom-typescript@10.1.6
├── auto-update-packages@1.0.1
├── autoclose-html@0.23.0
├── autocomplete-modules@1.6.1
├── ava@0.7.0
├── color-picker@2.2.2
├── csslint@1.1.5
├── docblockr@0.8.2
├── editorconfig@1.4.1
├── file-icons@1.7.18
├── git-log@0.4.1
├── git-time-machine@1.5.3
├── highlight-selected@0.11.2
├── hyperclick@0.0.37
├── js-hyperclick@1.4.2
├── language-babel
├── language-dots@0.0.4
├── language-javascript-jsx@0.3.7
├── language-swigjs@0.3.1
├── linter@1.11.16
├── linter-eslint@7.2.4
├── linter-tslint@0.11.1
├── markdown-scroll-sync@2.1.2
├── merge-conflicts@1.4.4
├── minimap@4.24.7
├── minimap-git-diff@4.3.1
├── minimap-highlight-selected@4.4.0
├── minimap-pigments@0.2.1
├── open-in-browser@0.4.7
├── open-recent@5.0.0
├── pigments@0.31.2
├── project-manager@2.9.7
├── project-switcher@0.3.0
├── rest-client@1.2.1
├── screen-recorder@1.2.0
├── seti-ui@1.3.1
├── simplified-chinese-menu@3.4.11
├── sort-lines@0.14.0
├── terminal-plus@0.14.5
├── todo-show@1.7.0
├── tool-bar@1.0.1
└── tool-bar-config@0.1.0
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
      beautifyEntireFileOnSave: false
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
      "atom-beautify"
      "editorconfig"
    ]
    themes: [
      "atom-material-ui"
      "atom-material-syntax"
    ]
  editor:
    fontFamily: "'Source Code Pro for Powerline','Electrolize'"
    fontSize: 15
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
    errorPanelHeight: 71
    showErrorPanel: false
    showErrorTabLine: true
  "linter-eslint":
    fixOnSave: true
  "merge-conflicts": {}
  minimap:
    plugins:
      "git-diff": true
      "git-diffDecorationsZIndex": 0
      "highlight-selected": true
      "highlight-selectedDecorationsZIndex": 0
      pigments: true
      pigmentsDecorationsZIndex: 0
  "project-manager":
    sortBy: "last modified"
  "rest-client": {}
  "simplified-chinese-menu": {}
  "split-diff":
    diffWords: true
    ignoreWhitespace: true
    leftEditorColor: "red"
    rightEditorColor: "green"
    syncHorizontalScroll: true
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
  "tree-view":
    autoReveal: true
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
