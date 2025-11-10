## :notebook: Configuração do VSCode

O **README** mostra como configurar o vscode.

```bash
{
  "terminal.integrated.fontSize": 14,
  "workbench.colorTheme": "Dracula Refined",
  "workbench.iconTheme": "symbols",
  "editor.tabSize": 2,
  "editor.fontSize": 18,
  "editor.lineHeight": 24,
  "editor.fontLigatures": true,
  "files.exclude": {
    "**/.git": true,
    "**/.svn": true,
    "**/.hg": true,
    "**/CVS": true,
    "**/.DS_Store": true
    //"node_modules": true
  },
  "explorer.compactFolders": false,
  "editor.renderLineHighlight": "gutter",
  "workbench.editor.labelFormat": "short",
  "extensions.ignoreRecommendations": true,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "typescript.updateImportsOnFileMove.enabled": "never",
  "json.schemas": [
    {
      "$schema": "https://json.schemastore.org/jsconfig"
    }
  ],
  "breadcrumbs.enabled": true,
  "editor.parameterHints.enabled": false,
  "explorer.confirmDragAndDrop": false,
  "explorer.confirmDelete": false,
  "editor.rulers": [80, 120],
  "files.associations": {
    ".sequelizerc": "javascript",
    ".stylelintrc": "json",
    ".prettierrc": "json"
  },
  "[prisma]": {
    "editor.defaultFormatter": "Prisma.prisma",
    "editor.formatOnSave": true
  },
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[javascript]": {
    "editor.codeActionsOnSave": {
      "source.fixAll.eslint": "explicit"
    },
    // "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  },
  "[javascriptreact]": {
    "editor.codeActionsOnSave": {
      "source.fixAll.eslint": "explicit"
    },
    // "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  },
  "[typescriptreact]": {
    "editor.codeActionsOnSave": {
      "source.fixAll.eslint": "explicit"
    },
    // "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  },
  "emmet.syntaxProfiles": {
    "javascript": "jsx"
  },
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "gitlens.codeLens.recentChange.enabled": false,
  "gitlens.codeLens.authors.enabled": false,
  "gitlens.codeLens.enabled": false,
  "git.enableSmartCommit": true,
  "typescript.tsserver.log": "off",
  "javascript.suggest.autoImports": true,
  "git.autofetch": true,
  "editor.renameOnType": true,

  "git.ignoreRebaseWarning": true,
  "diffEditor.ignoreTrimWhitespace": false,
  "typescript.tsserver.watchOptions": {},
  "symbols.hidesExplorerArrows": false,
  "workbench.productIconTheme": "fluent-icons",
  "editor.language.colorizedBracketPairs": [],
  "editor.indentSize": "tabSize",
  "editor.language.brackets": [],
  "[javascript][javascriptreact][typescriptreact]": {
    "editor.codeActionsOnSave": {
      "source.fixAll.eslint": "explicit"
    }
  },
  "terminal.integrated.env.windows": {},
  "console-ninja.featureSet": "Community",
}

```

## :notebook: Principais Extensões do VSCode

- Auto close Tag
- Auto Rename Tag
- Dracula Refined
- GitHub Copilot
- GitHub Copilot Chat
- Live server
- Qodo: the AI Code Review
- Symbols
- Tailwind Css IntelliSense
- Eslint
- Prettier - Code formatter
