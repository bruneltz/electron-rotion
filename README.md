# rotion

An Electron application with React and TypeScript

## Recommended IDE Setup

- [VSCode](https://code.visualstudio.com/) + [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) + [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

## Project Setup

### Install

```bash
$ npm install
```

### Development

```bash
$ npm run dev
```

### Build

```bash
# For windows
$ npm run build:win

# For macOS
$ npm run build:mac

# For Linux
$ npm run build:linux
```
### Info

Specific dependencies:

npm i clsx -> condicionais
npm i phosphor-react -> ícones
npm i cmdk -> opções que aparecem sob a tela

tiptap -> editor de texto
    npm i @tiptap/react @tiptap/starter-kit @tiptap/extension-document @tiptap/extension-placeholder @tiptap/extension-typography @titap/extension-highlit

tailwindcss:
    npm install -D @tailwindcss/typography -> fornece a classe 'prose' de customização que transforma o html em markdown

Radix-UI:
    npm install @radix-ui/react-collapsible

React-Query:
    - Simplifica a comunicação IpC, como o express para o node
    - Faz a aplicação parecer se comunicar em tempo real, por exemplo, sempre que o foco é refeito, a requisição é feita novamente
    npm i @tanstack/react-query

Sugestões de bancos:
    SQLite
    RxDB
    ElectronStore -> baseado em JSON, por isso é mais limitado. Bom para salvar preferências do usuário, app state, cache, etc
    - npm i electron-store


Integração de Paths custom com Electron:
    npm i -D vite-tsconfig-paths