# .config

### VS CODE

settings.json

```json
{
  "editor.formatOnSave": true,
  "window.zoomLevel": 3,
  "workbench.iconTheme": "vscode-icons",
  "workbench.activityBar.visible": false,
  "editor.stickyScroll.enabled": true,
  "editor.minimap.enabled": false,
  "breadcrumbs.enabled": false,
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs": "active",
  "[javascript]": {
    "editor.defaultFormatter": "rome.rome"
  },
  "workbench.colorTheme": "Gruvbox Dark (Hard)",
  "vim.easymotion": true,
  "vim.sneak": true,
  "vim.useSystemClipboard": true,
  "vim.hlsearch": true,
  // "vim.useCtrlKeys": true,
  "vim.insertModeKeyBindings": [
    {
      "before": ["k", "j"],
      "after": ["<Esc>"]
    }
  ],
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.fontFamily": "'Droid Sans Mono', 'monospace', monospace"
}
```

---

keybindings.json

```json
// Place your key bindings in this file to override the defaultsauto[]
[
  {
    "key": "shift+alt+down",
    "command": "editor.action.copyLinesDownAction",
    "when": "editorTextFocus && !editorReadonly"
  },
  {
    "key": "ctrl+shift+alt+down",
    "command": "-editor.action.copyLinesDownAction",
    "when": "editorTextFocus && !editorReadonly"
  },
  {
    "key": "tab",
    "command": "tab",
    "when": "editorTextFocus && !editorTabMovesFocus"
  },
  {
    "key": "shift+tab",
    "command": "outdent",
    "when": "editorTextFocus && !editorTabMovesFocus"
  },
  {
    "key": "alt+j",
    "command": "workbench.action.togglePanel"
  }
]
```

---

### Extensions

Enabled:

- Erro Lens
- Gruvbox Themes
- IntelliCode
- IntelliCode API Usage Examples
- Prettier
- Resource Monitor
- Rome
- Vim
- vscode-icons

Disabled:

- 50 Shades of Purple
- Azure Shades
- Code Runner
- Deepdark Material Theme
- Electron Highlighter Syntax
- jest

### 2023

```json
{
  "editor.fontSize": 16,
  "editor.fontLigatures": true,
  "editor.lineHeight": 1.5,
  // "editor.tabSize": 4,
  "editor.fontFamily": "'JetBrains Mono','Hack NF',Consolas, 'Courier New', monospace",
  "[typescript][javascript][javascriptreact][typescriptreact]": {
    "editor.defaultFormatter": "rome.rome"
  },
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "window.commandCenter": false,
  "window.menuBarVisibility": "compact",
  "workbench.layoutControl.enabled": false,
  "editor.scrollbar.horizontal": "hidden",
  "editor.scrollbar.vertical": "hidden",
  "workbench.colorTheme": "One Dark Pro Flat",
  "workbench.colorCustomizations": {
    "peekView.border": "#E50A69AB",
    "peekViewTitle.background": "#002b36",
    "peekViewResult.background": "#00212b",
    "peekViewEditor.background": "#002b36",
    "peekViewEditor.matchHighlightBackground": "#00212bAB"
  },
  "workbench.iconTheme": "vscode-great-icons",
  "workbench.startupEditor": "none"
}
```

### Extensions

- Aura Theme - Dalton Menezes
- Auto Close Tag - Jun Han
- Auto Rename Tag - Jun Han
- Better Comments - Aaron Bond
- Better Solarized - ginfuru
- ES7+ Recct/Redux... - dszbajder
- One Dark Pro - binaryify
- Rome - Rome
- Tailwind CSS Inteligent - Tailwind Labs
- Theme - Oceanic Next - Sergii N
- VSCode Great Incons - Emmanuel Beziat
- GitLens - GitKraken
- One Dark Ocean - George Aidonidis
- Might add - ESLint, npm Intellisense
