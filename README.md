# CSS

## Configurações

### Dependências

- Dependências do projeto
  - stylelint: A ferramenta de linting.
  - stylelint-scss: Plugin para adicionar suporte ao SCSS.
  - stylelint-config-standard-scss: Configuração recomendada para SCSS.

- Instalação

```bash
npm install
```

### Configurações do VS Code

Abra as configurações com `Ctrl + Shift + p`, e selecione Preferências Abrir as configurações do usuário (json), espere abrir o arquivo `settings.json` e cole as seguintes linhas:

```bash
"files.insertFinalNewline": true,
    "files.trimTrailingWhitespace": true,
    "editor.tabSize": 2,
    "editor.rulers": [
        100
    ],
    "editor.formatOnSave": true,
    "editor.codeActionsOnSave": {
        "source.fixAll": true,
    },
```

### Extensões vs code

- EditorConfig for vs code
- StyleLint

## Uso

```bash
npm run lint:scss
npm run lint:css
```
