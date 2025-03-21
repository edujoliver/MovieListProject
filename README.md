# MovieListProject

Este projeto é uma aplicação React para listar filmes populares e permitir a busca de filmes. Os usuários também podem adicionar filmes aos seus favoritos.

## Tecnologias Utilizadas

- **React**
- **React Router**
- **Context API**
- **CSS**
- **Fetch API**
- **Vite**

## Estrutura do Projeto

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

## Como Rodar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/edujoliver/MovieListProject
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd MovieListProject
   ```
3. Instale as dependências:
   ```bash
   npm install vite@latest
   ```
4. Inicie o servidor de desenvolvimento:
   ```bash
   npm run dev
   ```

## Funcionalidades

- Listar Filmes Populares
- Buscar Filmes
- Adicionar aos Favoritos
- Navegação entre páginas

## Estrutura de Componentes

- `App.jsx`
- `NavBar.jsx`
- `Home.jsx`
- `Favorites.jsx`
- `MovieCard.jsx`
- `MovieContext.jsx`

## Estilização

- `App.css`
- `Home.css`
- `MovieCard.css`
- `Favorites.css`
- `index.css`

## API

A aplicação consome uma API de filmes para exibir os filmes populares e realizar buscas. As requisições estão em `src/services/api.js`.

## Contribuição

Se quiser contribuir, abra uma **issue** ou envie um **pull request**.
