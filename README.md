# MovieListProject

Este projeto é uma aplicação React para listar filmes populares e permitir a busca de filmes. Os usuários também podem adicionar filmes aos seus favoritos.

---

## 🚀 Tecnologias Utilizadas

- **React**: Biblioteca JavaScript para construção de interfaces de usuário.
- **React Router**: Biblioteca para roteamento em aplicações React.
- **Context API**: Para gerenciamento de estado global.
- **CSS**: Para estilização dos componentes.
- **Fetch API**: Para fazer requisições HTTP para a API de filmes.
- **Vite**: Ferramenta de build rápida para desenvolvimento de aplicações web modernas.

---

## 📁 Estrutura do Projeto

```
movielist/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── MovieCard.jsx
│   │   ├── NavBar.jsx
│   ├── contexts/
│   │   └── MovieContext.jsx
│   ├── css/
│   │   ├── App.css
│   │   ├── Home.css
│   │   ├── MovieCard.css
│   │   ├── Favorites.css
│   │   └── index.css
│   ├── pages/
│   │   ├── Home.jsx
│   │   └── Favorites.jsx
│   ├── services/
│   │   └── api.js
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── .gitignore
├── package.json
└── README.md
```

---

## ▶️ Como Rodar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/movielist.git
   ```

2. **Navegue até o diretório do projeto:**
   ```bash
   cd movielist
   ```

3. **Instale as dependências:**
   ```bash
   npm install
   ```

4. **Inicie o servidor de desenvolvimento:**
   ```bash
   npm run dev
   ```

---

## ✨ Funcionalidades

- **Listar Filmes Populares**: A página inicial exibe uma lista de filmes populares.
- **Buscar Filmes**: Os usuários podem buscar filmes pelo título.
- **Adicionar aos Favoritos**: Os usuários podem adicionar filmes aos seus favoritos.
- **Navegação**: A aplicação possui navegação entre a página inicial e a página de favoritos.

---

## 🧩 Estrutura de Componentes

- `App.jsx`: Componente principal que configura o roteamento e o provedor de contexto.
- `NavBar.jsx`: Componente de navegação.
- `Home.jsx`: Página inicial que exibe filmes populares e permite a busca de filmes.
- `Favorites.jsx`: Página que exibe os filmes favoritos do usuário.
- `MovieCard.jsx`: Componente que exibe as informações de um filme individual.
- `MovieContext.jsx`: Contexto para gerenciamento de estado global dos filmes.

---

## 🎨 Estilização

- `App.css`: Estilos globais para a aplicação.
- `Home.css`: Estilos específicos para a página inicial.
- `MovieCard.css`: Estilos para o componente de cartão de filme.
- `Favorites.css`: Estilos para a página de favoritos.
- `index.css`: Estilos globais e reset de CSS.

---

## 🌐 API

A aplicação faz requisições para uma API de filmes para obter a lista de filmes populares e buscar filmes pelo título.  
As funções de requisição estão definidas em `src/services/api.js`.

---

## 🤝 Contribuição

Se você quiser contribuir para este projeto, sinta-se à vontade para abrir uma **issue** ou enviar um **pull request**.

---

## 📄 Licença

Este projeto está licenciado sob a **Licença MIT**. Veja o arquivo `LICENSE` para mais detalhes.
