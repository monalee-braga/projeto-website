# Projeto WebSite com Vue 3 e Tailwind

Criação de uma landing page de uma loja fictícia de produtos de cosméticos, utilizando conceitos de layouts responsivos e aprimorando com Vue 3 e Tailwind para reforçar conhecimentos de front-end criando uma aplicação web.

## Setup

Para utilizar Vue.js e Tailwind CSS em uma aplicação front-end, primeiro você precisa criar um novo projeto Vue.js usando a CLI (Command Line Interface) do Vue. Você pode fazer isso executando o seguinte comando no terminal:

```
npm install -g @vue/cli
```

Depois de instalado, você pode criar um novo projeto Vue.js executando:

```
vue create nome-projeto
```

Agora vamos instalar o Tailwind CSS e suas dependências (autoprefixer e postcss) em nosso projeto Vue.

```
npm install tailwindcss postcss
```

É necessário criar os arquivos de configuração para o Tailwind CSS e postcss, o comando abaixo gera automaticamente:

```
npx tailwindcss init -p
```

Vamos editar o arquivo **tailwind.config.js** para adicionar os caminhos das páginas e componentes
que contém conteúdo.

```jsx
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ['./index.html', './src/**/*.{vue,js,ts,jsx,tsx}'],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

Na pasta **src** teremos que que criar o arquivo **app.css** :

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Esse arquivo será utilizado no arquivo **main.js** para que o estilo seja respeitado na aplicação:

```jsx
import { createApp } from 'vue';
import App from './App.vue';
import router from './router';
import store from './store';

import './styles/app.css';

createApp(App).use(store).use(router).mount('#app');
```

### Compiles

```
npm run serve
```

### Pré-requisitos

- Node.js
- npm (gerenciador de pacotes do Node.js)

### Instalação

1. Clone o repositório:

```bash
git clone https://github.com/monalee-braga/projeto-website

```

2. Instalar as dependências

```
npm install

```

3. Ambiente de Desenvolvimento

Para iniciar o servidor de desenvolvimento:

```
npm run serve
```

Acesse a aplicação em http://localhost:8080.

4. Ambiente de Produção

Para compilar e minificar os arquivos para produção:

```
npm run build
```

Os arquivos serão gerados no diretório dist/.

### Dúvidas

Se você tiver alguma dúvida ou problema, procure ajuda em:

- [Vue.js](https://cli.vuejs.org/guide/creating-a-project.html)
- [Tailwind CSS](https://tailwindui.com/documentation)
