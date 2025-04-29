# .config

### VS Code configurations

- Extensions for VS Code

  - **Tools**

  1. Biome
  2. Code Spell Checker
  3. Color Highlight
  4. ENV
  5. Error Lens
  6. Github Copilot
  7. Log File Highlighter
  8. npm Intellisense
  9. Prettier
  10. REST Client
  11. Thunder Client
  12. TODO Highlight
  13. Todo Tree
  14. Turbo Console Log
  15. TypeScript Hero

  - **Themes**

  1. Andromeda
  2. Anysphere Dark
  3. Catppuccin for VSCode
  4. Catppuccin vscode theme
  5. Github Theme
  6. Horizon Legacy
  7. Material Icon Theme
  8. NeoOsaka Theme
  9. One Dark Pro
  10. POP! Icon Theme
  11. Ruby Sea
  12. Sharp Icons
  13. Solarized Osaka
  14. Sonomin
  15. Symbols
  16. VSCode Great Icons
  17. vscode-icons

- `settings.json`: VS Code settings.

```json
{
  "editor.fontFamily": "'JetBrains Mono','GeistMono NF', 'Zed Mono', 'Dank Mono'",
  "terminal.integrated.fontFamily": "JetBrains Mono",
  "terminal.integrated.fontLigatures": true,
  // "terminal.integrated.fontFamily": "'Zed Mono', 'GeistMono NF', 'CaskaydiaCove NFP', 'Zed Mono', 'Dank Mono'",
  "editor.lineHeight": 1.5,
  // "editor.lineHeight": 1.3,
  // "editor.fontSize": 14,
  "editor.fontSize": 16,
  "editor.fontLigatures": true,
  "editor.smoothScrolling": true,
  // "editor.fontSize": 20,
  // "terminal.integrated.defaultProfile.windows": "Ubuntu (WSL)",
  "editor.scrollbar.horizontal": "hidden",
  "editor.scrollbar.vertical": "hidden",
  "editor.minimap.autohide": true,
  "editor.codeActionsOnSave": {
    "source.organizeImports.biome": "always"
  },
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[javascript][typescript][javascriptreact][typescriptreact]": {
    "editor.defaultFormatter": "biomejs.biome"
    // "editor.defaultFormatter": "dprint.dprint"
  },
  // "dprint.path": "C:\\Users\\JP PHOTOGRAPHY\\AppData\\Roaming\\npm\\node_modules\\dprint\\node_modules\\@dprint\\win32-x64\\dprint.exe",
  "typescript.updateImportsOnFileMove.enabled": "always",
  "workbench.editor.customLabels.patterns": {
    "**/app/**/page.jsx": "${dirname} - Page",
    "**/app/**/layout.jsx": "${dirname} - Layout",
    "**/app/**/*id*/layout.jsx": "${dirname} - Layout",
    "**/app/**/*id*/page.jsx": "${dirname(1) - ID Page",
    // For TypeScriptReact
    "**/app/**/page.tsx": "${dirname} - Page",
    "**/app/**/layout.tsx": "${dirname} - Layout",
    "**/app/**/*id*/layout.tsx": "${dirname} - Layout",
    "**/app/**/*id*/page.tsx": "${dirname(1) - ID Page"
  },
  "workbench.layoutControl.enabled": false,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "editor.stickyScroll.enabled": false,
  "workbench.iconTheme": "material-icon-theme",
  "workbench.list.smoothScrolling": true,
  "git.autofetch": true,
  "workbench.startupEditor": "none",
  "explorer.fileNesting.patterns": {
    "*.ts": "${capture}.js",
    "*.js": "${capture}.js.map, ${capture}.min.js, ${capture}.d.ts",
    "*.jsx": "${capture}.js",
    "*.tsx": "${capture}.ts",
    "tsconfig.json": "tsconfig.*.json",
    "package.json": "package-lock.json, yarn.lock, pnpm-lock.yaml, bun.lockb",
    "*.sqlite": "${capture}.${extname}-*",
    "*.db": "${capture}.${extname}-*",
    "*.sqlite3": "${capture}.${extname}-*",
    "*.db3": "${capture}.${extname}-*",
    "*.sdb": "${capture}.${extname}-*",
    "*.s3db": "${capture}.${extname}-*"
  },
  // "workbench.colorTheme": "EnvoyOS Theme",
  // "[markdown]": {
  //   "editor.defaultFormatter": "DavidAnson.vscode-markdownlint"
  // },
  "files.associations": {
    "*.env.development": "env",
    "*.env.production": "env"
  },
  "editor.bracketPairColorization.enabled": true,
  // "workbench.productIconTheme": "feather-vscode",
  "[typescriptreact]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  // "github.copilot.editor.enableAutoCompletions": false,
  "biome.lsp.bin": "C:\\Users\\JP PHOTOGRAPHY\\AppData\\Roaming\\npm\\node_modules\\@biomejs\\biome\\bin",
  "github.copilot.enable": {
    "*": false,
    "plaintext": false,
    "markdown": true,
    "scminput": false
  },
  "[prisma]": {
    "editor.defaultFormatter": "Prisma.prisma"
  }
  // "workbench.activityBar.location": "hidden",
}
// {
//     "files.associations": {
//         "*.ejs": "html",
//         "*.env.development": "env",
//         "*.env.production": "env",
//         "JavaScript JSX": "javascriptreact",
//         "TypeScript JSX": "typescriptreact"
//     },
//     "editor.defaultFormatter": "esbenp.prettier-vscode",
//     "editor.bracketPairColorization.enabled": true,
//     "editor.guides.bracketPairs": "active",
//     "editor.smoothScrolling": true,
//     "editor.cursorSmoothCaretAnimation": "on",
//     "editor.minimap.autohide": true,
//     "editor.mouseWheelZoom": true,
//     "editor.scrollbar.vertical": "hidden",
//     "editor.scrollbar.horizontal": "hidden",
//     "editor.lineHeight": 1.4,
//     // "editor.fontFamily": "CaskaydiaCove NFM",
//     "editor.fontLigatures": true,
//     "workbench.startupEditor": "none",
//     "workbench.layoutControl.enabled": false,

//     "turboConsoleLog.logMessagePrefix": ">>>",
//     "turboConsoleLog.includeFileNameAndLineNum": true,
//     "typescript.updateImportsOnFileMove.enabled": "always",
//     "javascript.updateImportsOnFileMove.enabled": "always",
//     // "editor.codeActionsOnSave": {
//     // "source.organizeImports.biome": "explicit"
//     // },
//     "errorLens.enabledDiagnosticLevels": ["warning", "info", "error"],
//     "terminal.integrated.cursorStyle": "line",
//     // "terminal.integrated.fontFamily": "'FiraCode Nerd Font','Hack Nerd Font','JetBrains Mono Nerd Font', Hack Nerd Font",
//     "terminal.integrated.lineHeight": 1.3,

//     "editor.occurrencesHighlight": "multiFile",
//     "workbench.tree.enableStickyScroll": true,

//     "terminal.integrated.scrollback": 100000,

//     "[env]": {
//         "editor.defaultFormatter": "IronGeek.vscode-env"
//     },
//     "editor.accessibilitySupport": "off",
//     // "window.title": "${dirty}${activeEditorShort}${separator}${rootName}${separator}${profileName}${separator}${appName}"
//     "window.title": "${rootName}",
//     // "workbench.editor.showTabs": "none",
//     "workbench.editor.editorActionsLocation": "hidden",
//     // "editor.inlayHints.fontFamily": "JetBrains Mono",
//     "editor.fontVariations": true,
//     // "errorLens.fontFamily": "Hack Nerd Font",
//     "errorLens.fontWeight": "400",
//     "errorLens.fontStyleItalic": false,
//     // "chat.editor.fontFamily": "Hack Nerd Font",
//     // "editor.codeLensFontFamily": "Hack Nerd Font",
//     "prettier.tabWidth": 4,
//     "prettier.printWidth": 160,
//     "editor.renderWhitespace": "trailing",
//     "github.copilot.enable": {
//         "*": false,
//         "plaintext": false,
//         "markdown": true,
//         "scminput": false
//     },
//     "[markdown]": {
//         "editor.formatOnSave": true,
//         "editor.formatOnPaste": true
//     },
//     "editor.codeActionsOnSave": {
//         "source.fixAll.markdownlint": "explicit",
//         "source.organizeImports.biome": "explicit"
//     },
//     "inlineChat.showGutterIcon": "always",
//     "[javascript][typescript][javascriptreact][typescriptreact]": {
//         "editor.defaultFormatter": "biomejs.biome"
//     },
//     "symbols.hidesExplorerArrows": false,
//     "workbench.iconTheme": "symbols",
//     "editor.linkedEditing": true,
//     "editor.stickyScroll.enabled": false,
//     // "breadcrumbs.enabled": false,
//     "[prisma]": {
//         "editor.defaultFormatter": "Prisma.prisma"
//     },
//     "editor.formatOnSave": true,
//     "editor.fontSize": 18,
//     "terminal.integrated.fontSize": 14,
//     "editor.fontFamily": "'Geist Mono', 'Hack Nerd Font','MesloLGL Nerd Font','Hack Nerd Font', Consolas, 'Courier New', monospace",
//     "terminal.integrated.fontFamily": "'Geist Mono', 'Hack Nerd Font', 'RobotoMono Nerd Font', 'MesloLGL Nerd Font'",
//     // "editor.wordWrap": "on",
//     "workbench.list.smoothScrolling": true,
//     "terminal.integrated.smoothScrolling": true,
//     "terminal.integrated.stickyScroll.enabled": false,
//     "notebook.stickyScroll.enabled": false,
//     "workbench.editor.customLabels.patterns": {
//         "**/app/**/page.jsx": "${dirname} - Page",
//         "**/app/**/layout.jsx": "${dirname} - Layout",
//         "**/app/**/*id*/layout.jsx": "${dirname} - Layout",
//         "**/app/**/*id*/page.jsx": "${dirname(1) - ID Page",
//         // For TypeScriptReact
//         "**/app/**/page.tsx": "${dirname} - Page",
//         "**/app/**/layout.tsx": "${dirname} - Layout",
//         "**/app/**/*id*/layout.tsx": "${dirname} - Layout",
//         "**/app/**/*id*/page.tsx": "${dirname(1) - ID Page"
//     },
//     "diffEditor.ignoreTrimWhitespace": false,
//     "prisma.showPrismaDataPlatformNotification": false,
//     "github.copilot.editor.enableAutoCompletions": true,
//     "workbench.sideBar.location": "right",
//     "workbench.colorTheme": "Nord"
// }

// {
//     // "window.zoomLevel": 1,
//     "editor.wordWrap": "off",
//     "editor.wordWrapColumn": 250000,
//     "editor.scrollbar.verticalScrollbarSize": 7,
//     "editor.overviewRulerBorder": false,
//     "editor.cursorBlinking": "smooth",
//     "editor.smoothScrolling": true,
//     "workbench.list.smoothScrolling": true,
//     "terminal.integrated.smoothScrolling": true,
//     "editor.fastScrollSensitivity": 5,
//     "editor.cursorSmoothCaretAnimation": "on",
//     "editor.cursorStyle": "block",
//     "editor.fontFamily": "'Zed mono','Droid Sans Mono', 'monospace', monospace",
//     "editor.fontWeight": 500,
//     "editor.fontSize": 15,
//     "editor.fontLigatures": true,
//     "editor.snippetSuggestions": "none",
//     "diffEditor.renderSideBySide": false,
//     "editor.gotoLocation.multipleDefinitions": "goto",
//     "editor.gotoLocation.multipleReferences": "goto",
//     "workbench.colorTheme": "One Dark Pro Mix",
//     // "window.titleBarStyle": "native",
//     "window.customTitleBarVisibility": "auto",
//     // "workbench.statusBar.visible": false,
//     // "workbench.activityBar.location": "hidden",
//     // "workbench.sideBar.location": "right",
//     "editor.lineNumbers": "off",
//     "editor.lineHeight": 1.6,
//     "editor.minimap.autohide": true,
//     "breadcrumbs.enabled": false,
//     "workbench.editor.editorActionsLocation": "hidden",
//     // "workbench.editor.showTabs": "none",
//     // "editor.renderWhitespace": "boundary",
//     "editor.renderWhitespace": "trailing",
//     "terminal.integrated.fontFamily": "Zed Mono",
//     "terminal.integrated.fontSize": 16,
//     "terminal.integrated.fontWeight": 500,
//     // "window.menuBarVisibility": "toggle",
//     "editor.stickyScroll.enabled": false,
//     "workbench.tree.enableStickyScroll": false,
//     "window.title": "${rootName}",
//     "workbench.iconTheme": "vscode-jetbrains-icon-theme-2023-dark",
//     "editor.mouseWheelZoom": true,
//     "editor.padding.top": 10,
//     "terminal.integrated.stickyScroll.enabled": false,
//     "git.autofetch": true,
//     "editor.scrollbar.horizontal": "hidden",
//     "editor.scrollbar.vertical": "hidden",
//     "editor.formatOnSave": true,
//     "editor.codeActionsOnSave": {
//         "source.organizeImports.biome": "explicit"
//     },
//     "editor.defaultFormatter": "esbenp.prettier-vscode",
//     "prettier.tabWidth": 4,
//     "prettier.printWidth": 180,
//     "[javascript][typescript][javascriptreact][typescriptreact]": {
//         "editor.defaultFormatter": "biomejs.biome"
//     },
//     // "symbols.hidesExplorerArrows": false,
//     "workbench.startupEditor": "none",
//     "symbols.hidesExplorerArrows": false,
//     "diffEditor.ignoreTrimWhitespace": false,
//     "window.menuBarVisibility": "classic"
// }

/*

javascript and typescript nightly
jetbrains icon theme
prettier
atom one dark coal
auto clos tag
biome
bootstrap intellisense
code spell check 
disable ligatures
ENV
eslint
error lens
github copilot
github theme
highlight on copy
javascript debugger (nightly)
material icon theme
mongodb for vscode
Nord
npm intellisense
one dark pro
path intellisense
prettier eslint
rest client
symbols
tailwind css intellisense
thunder client
tokyo night
turbo console log
apc customize UI++
css peak 
esj language support
git blame
git graph
git history
html to jsx

*/
```
