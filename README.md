# :wrench: Dev Configs

Sempre tive o problema de achar um lugar que eu possa organizar as coisas que eu utilizo no dia-a-dia, e como gosto de compartilhar algumas das coisas que acabam por facilitar o meu dia-a-dia, decidi criar esse repositório para mostrar um pouco do que uso. <br />
Espero que assim como me ajuda, possa ajudar a alguém que esteja configurando seu ambiente para deixá-lo mais produtivo e organizado!

## :gear: Settings(JSON) do VSCode

Algo que facilita muito o meu dia-a-dia são algumas das configs que uso no VSCode, dentre elas são: 

```javascript
{
    "breadcrumbs.enabled": true, // Visualiza o caminho do arquivo no topo superior
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true 
    }, // Com isso é possível configurar ações ao salvar o arquivo (Alterações de ESLint por exemplo)
    "editor.fontFamily": "Fira Code",
    "editor.fontLigatures": true, // Gosto MUITO de usar ligatures, que seriam combinações para ===, !==, de forma visual
    "editor.fontSize": 14,
    "editor.parameterHints.enabled": false, // Evita que o VSCode sujira dicas para os parâmetros que está digitando
    "editor.renderLineHighlight": "gutter",
    "editor.rulers": [80, 120], // MUITO importante, organiza nosso código a não passar dos limites estabelecidos
    "editor.tabSize": 2,
    "emmet.includeLanguages": {
        "javascript": "javascriptreact",
    },
    "emmet.syntaxProfiles": {
        "javascript": "jsx",
    },  
    "explorer.compactFolders": false, // Quando se tem só uma página ou arquivo, evita o vscode a "encurtar" o caminho
    "javascript.suggest.autoImports": false, // O VSCode tente a sugerir imports, normalmente desabilito
    "javascript.updateImportsOnFileMove.enabled": "never", // Quando arrastar um arquivo, mudarmos os imports de forma manual
    "terminal.integrated.fontSize": 14, 
    "terminal.integrated.shell.osx": "/bin/zsh", // Integração com o OhMyZsh
    "window.zoomLevel": 0, // Zoom padrão da tela do VSCode
    "workbench.colorTheme": "Dracula Soft", // Tema que utilizo para o VsCode (fundo, cor de texto)
    "workbench.iconTheme": "material-icon-theme", // Grupo de icones para arquivos, pastas
    "workbench.startupEditor": "newUntitledFile", //Inicia com um arquivo em branco
}
```
## :crystal_ball: Extensões

### Dracula Official 
 Meu tema preferido no VS Code, deixa tudo muito explicito (Minha opinião)

### vs-styled-components
 Melhora a visualização do uso do Styled Components

### Prettier
 Melhora a visualização do código
 
### Eslint
