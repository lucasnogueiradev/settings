# settings
 Arquivos de configuração para organizar o código, padronizar o ambiente e acelerar o desenvolvimento. Inclui regras de formatação, lint, snippets e outras otimizações para projetos mais produtivos.
 
# 💻 VS Code Settings – Developer Productivity Pack

This repository contains a custom set of **`settings.json`** configurations for Visual Studio Code, tailored to improve code organization, editor behavior, formatting, and developer productivity — especially for projects using JavaScript, TypeScript, React, Prisma, and Prettier/ESLint.

## ✨ Features

- ✅ Emmet support for JSX/TSX
- ✅ Automatic import suggestions and updates
- ✅ Prettier as default formatter
- ✅ ESLint auto-fixes on save
- ✅ Cursor and editor UI customization
- ✅ Enhanced terminal appearance
- ✅ File associations for various config files
- ✅ Compact, distraction-free Explorer
- ✅ Themes and icon enhancements
- ✅ Git and SSH integrations

---

## 🛠️ Highlights

### Code Editing
- Font: `JetBrains Mono` with ligatures enabled
- Font size: `18px`, line height: `26`
- Minimap: **disabled** for cleaner workspace
- Cursor: `solid`, smooth animation, custom width

### Formatting & Linting
- `Prettier` set as the default formatter
- ESLint runs auto-fixes on save (`explicit`)
- Format on save and paste both enabled

### Emmet Enhancements
```json
"emmet.syntaxProfiles": {
  "javascript": "jsx",
  "typescript": "tsx",
  "javascriptreact": "jsx",
  "typescriptreact": "tsx"
}
