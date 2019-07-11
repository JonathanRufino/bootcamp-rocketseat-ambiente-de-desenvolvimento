# Ambiente de Desenvolvimento - Bootcamp Rocketseat

Compilado de configurações recomendadas durante o Bootcamp da [Rocketseat](https://github.com/Rocketseat) para o desenvolvimento de aplicações Node, ReactJS e React Native.

> **Obs. 1**: Esse documento será atualizado a medida que o bootcamp for progredindo.

> **Obs. 2**: Alguns ajustes na configuração podem ser realizados para melhor atender à minha necessidade, nesses casos deixarei indicadas as minhas alterações

## VSCode

### Tema de Cores e Ícones

- `Dracula Official`
- `vscode-icons` ou `Material Icon Theme`

### Fontes

- [Fira Code](https://github.com/tonsky/FiraCode)

### Configurações VSCode

```json
{
  "workbench.startUpEditor": "newUntitledFile",
  "workbench.colorTheme": "Dracula",
  "workbench.iconTheme": "vscode-icons",
  "window.zoomLevel": 0,
  "editor.fontFamily": "Fira Code",
  "editor.fontLigatures": true,
  "editor.fontSize": 18,
  "editor.lineHeight": 24,
  "editor.formatOnSave": true,
  "editor.rulers": [80, 120],
  "editor.tabSize": 2,
  "editor.renderLineHighlight": "gutter",
  "terminal.integrated.fontSize": 14,
  "emmet.syntaxProfiles": {
    "javascript": "jsx"
  },
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "javascript.updateImportsOnFileMove.enabled": "never",
  "breadcrumbs.enabled": true,
  "editor.parameterHints.enabled": false,
  "prettier.eslintIntegration": true
}
```

### Extensões

- Dracula Official
- Color Highlight
- EditorConfig for VS Code
- ESLint
- Prettier - Code formatter
- Rocketseat ReactJS
- Rocketseat React Native

## Terminal

- [Hyper](https://hyper.is/)

## [Oh My ZSH](https://ohmyz.sh/)

### [Spaceship](https://github.com/denysdovhan/spaceship-prompt)

Após a instalação, abra o arquivo `~/.zshrc` e faça a seguinte atualização:

```bash
# Altere o tema para spaceship
ZSH_THEME="spaceship"

# Adicione esse trecho ao final do arquivo
SPACESHIP_PROMPT_ORDER=(
  user          # Username section
  dir           # Current directory section
  host          # Hostname section
  git           # Git section (git_branch + git_status)
  hg            # Mercurial section (hg_branch  + hg_status)
  exec_time     # Execution time
  line_sep      # Line break
  vi_mode       # Vi-mode indicator
  jobs          # Background jobs indicator
  exit_code     # Exit code section
  char          # Prompt character
)

SPACESHIP_PROMPT_ADD_NEWLINE=false
SPACESHIP_CHAR_SYMBOL="❯"
SPACESHIP_CHAR_SUFFIX=" "
```

### [Zplugin](https://github.com/zdharma/zplugin)

Após a instalação, adicione o seguinte código ao final do arquivo `~/.zshrc`:

```bash
zplugin light zdharma/fast-syntax-highlighting
zplugin light zsh-users/zsh-autosuggestions
zplugin light zsh-users/zsh-completions
```

## Extensões Google Chrome

- React Developer Tools
- Dracula DevTools Theme
- JSON Viewer

## Ferramentas

- [Insomnia](https://insomnia.rest/)
- [DevDocs](https://devdocs.egoist.sh/)
- [Docker](https://docs.docker.com/install/)
  - [postgres](https://hub.docker.com/_/postgres)
- [Postbird](https://electronjs.org/apps/postbird)
- [MongoDB Compass Community](https://www.mongodb.com/download-center/compass)

## Node

- [nvm](https://github.com/nvm-sh/nvm)
- [Yarn](https://yarnpkg.com/)

# Sites

- [md5online.org](https://www.md5online.org/)
- [mailtrap](https://mailtrap.io/)
- [Sentry](https://sentry.io/)
