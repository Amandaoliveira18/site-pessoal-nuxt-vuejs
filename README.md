🎵 Amanda Website

📌 Objetivo do Projeto

Este projeto é um portfólio pessoal desenvolvido com Vue.js e Tailwind CSS. Ele apresenta links para redes sociais e um modal interativo que exibe uma playlist do Spotify.

🚀 Tecnologias Utilizadas

Vue.js 3

Vite

Tailwind CSS

Spotify Embed API

📂 Estrutura do Projeto

📁 src
 ├── 📁 components
 │   ├── 📄 ModalSpotify.vue  # Componente do modal de músicas
 │   ├── 📄 ButtonAction.vue # Componente para o button e lógica para abertura do Modal
 │    
 ├── 📁 pages
 |   ├── 📄 index.vue  # Componente principal


💻 Como Rodar o Projeto Localmente

📌 Pré-requisitos

Antes de começar, certifique-se de ter instalado:

Node.js 

Git

NPM ou Yarn

🔧 Passos para execução

Clone o repositório:

git clone https://github.com/Amandaoliveira18/site-pessoal-nuxt-vuejs
cd site-pessoal-nuxt-vuejs

Instale as dependências:

npm install  # ou yarn install

Inicie o servidor de desenvolvimento:

npm run dev  # ou yarn dev

Acesse no navegador:

O projeto será iniciado em http://localhost:3000/

📦 Como Fazer o Build do Projeto

Para gerar os arquivos otimizados para produção, execute:

npm run build  # ou yarn build

Os arquivos otimizados ficarão na pasta dist/.

🚀 Como Entregar o Projeto em Produção

Realize o build do projeto (npm run build).

Faça o deploy do conteúdo da pasta dist/ em uma plataforma como:

Vercel

Netlify

GitHub Pages (com adaptador de SPA)

Hospedagem própria com Nginx/Apache


