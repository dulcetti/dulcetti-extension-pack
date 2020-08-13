# Dulcetti Extension Pack

<img src="logo.png" alt="Brand" style="display: block; margin: 0 auto;" />

Conjunto de plugins do VS Code que eu uso nos meus projetos pessoais e nos que faço na [Wooza](https://github.com/woozabr).

## Lista com as extensões

Fiquei com preguiça de explicar o que cada uma faz, qualquer coisa entra no link e veja o README =P

- [clinyong.vscode-css-modules](https://marketplace.visualstudio.com/items?itemName=clinyong.vscode-css-modules)
- [donjayamanne.githistory](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
- [eamodio.gitlens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [eg2.vscode-npm-script](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script)
- [flowtype.flow-for-vscode](https://marketplace.visualstudio.com/items?itemName=flowtype.flow-for-vscode)
- [formulahendry.auto-close-tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
- [kumar-harsh.graphql-for-vscode](https://marketplace.visualstudio.com/items?itemName=kumar-harsh.graphql-for-vscode)
- [Mikael.Angular-BeastCode](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode)
- [ms-azuretools.vscode-docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
- [ms-python.python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
- [msjsdiag.debugger-for-chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)
- [NuclleaR.vscode-extension-auto-import](https://marketplace.visualstudio.com/items?itemName=NuclleaR.vscode-extension-auto-import)
- [ritwickdey.LiveServer](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
- [robinbentley.sass-indented](https://marketplace.visualstudio.com/items?itemName=robinbentley.sass-indented)
- [vscode-icons-team.vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
- [wgenial.html-snippets](https://marketplace.visualstudio.com/items?itemName=wgenial.html-snippets)
- [wix.vscode-import-cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
- [EditorConfig for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
- [VS Code ESLint extension](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Prettier Formatter for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
- [vscode-duplicate](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-duplicate)
- [VSCode Advanced New File](https://marketplace.visualstudio.com/items?itemName=patbenatar.advanced-new-file)
- [Microsoft Visual Studio Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
- [Apollo GraphQL for VS Code](https://marketplace.visualstudio.com/items?itemName=apollographql.vscode-apollo)
- [vscode-styled-components](https://marketplace.visualstudio.com/items?itemName=jpoissonnier.vscode-styled-components)
- [VS Code JavaScript (ES6) snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)
- [vscode-jest-snippets](https://marketplace.visualstudio.com/items?itemName=andys8.jest-snippets)
- [JS JSX Snippets](https://marketplace.visualstudio.com/items?itemName=skyran.js-jsx-snippets)
- [Snippets úteis para NextJS](https://marketplace.visualstudio.com/items?itemName=PulkitGangwar.nextjs-snippets)
- [One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme)
- [JavaScript and TypeScript Nightly](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-next)
- [Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)

## Koé Dulça, curti esse fodasse ae. Posso usar?

Mas é claro, meu nobre. É só buscar no seu VS Code e instalar essa extensão que ela instala tudo que estiver na lista acima.

Caso queira usar somente algumas extensões, não tem problema, é só clonar esse repositório e editar o arquivo package.json. Aí você remove os fodasses, quer dizer, extensões, que não quiser do nó extensionPack e depois siga os procedimentos abaixo para instalar localmente.

### Instalando localmente

- Clone o repositório:

```bash
git clone git@github.com:dulcetti/dulcetti-extension-pack.git
```

- Instale globalmente o pacote vsce

```bash
npm install -g vsce
```

- Crie o pacote local da Dulcetti extension (caralho, brinquei no inglês agora =P)

```bash
vsce package
```

- Instale a extensão através do arquivo .vsix

Só seguir mais uns pequenos passos e tudo estará instalado:

1. Abra o VS Code
1. Selecione `Extensions` do menu
1. Clique em `More > Install from VSIX...`
1. Selecione o arquivo `dulcetti-extension-pack-x.x.x.vsix`
1. Clique em `Reload Now` para recarregar o VS Code

## Tá olhando o quê? Contribua também!

Aceito sugestões, vira e mexe descubro novas extensões que eu curto e nem sabia da existência. Para fazer isso [é só entrar no repositório](https://github.com/dulcetti/dulcetti-extension-pack) e abrir um Pull Request com as extensões que quiser sugerir ;)

Beijo na alcatra.
