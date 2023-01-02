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
  }
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

Disabled

- 50 Shades of Purple
- Azure Shades
- Code Runner
- Deepdark Material Theme
- Electron Highlighter Syntax
- jest
