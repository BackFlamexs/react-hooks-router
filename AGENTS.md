# AGENTS.md

## Projeto

Este projeto é um laboratório de estudo em React com foco em três tópicos:

1. **Context API** — compartilhamento de estado global (ex.: tema, favoritos) via `src/context/ThemeContext.jsx`.
2. **Hooks Customizados** — reutilização de lógica em `src/hooks/useCounter.js` e `src/hooks/useLocalStorage.js`.
3. **React Router** — navegação entre páginas/exercícios em `src/pages/`.

## Estrutura

- `src/main.jsx` — ponto de entrada.
- `src/App.jsx` — layout principal (sidebar + conteúdo) e rotas.
- `src/styles.css` — estilização global (layout, tema claro/escuro).
- `src/context/` — contextos (ThemeContext).
- `src/hooks/` — hooks customizados (useCounter, useLocalStorage).
- `src/pages/` — páginas/exercícios:
  - `Home.jsx` — página inicial.
  - `Ex01Titulo.jsx` — exercício 1 (título/document title).
  - `Ex02Resize.jsx` — exercício 2 (resize listener).
  - `Ex03Context.jsx` — exercício 3 (Context API).
  - `Ex04Counter.jsx` — exercício 4 (hook customizado useCounter).
  - `Ex05Favoritos.jsx` — exercício 5 (favoritos com useLocalStorage).

## Convenções

- Estilização centralizada em `src/styles.css`; não criar CSS por componente.
- Componentes de página em `src/pages/`, hooks em `src/hooks/`, contextos em `src/context/`.
- Manter componentes simples e didáticos, priorizando clareza sobre abstração.
- Idioma da UI e comentários: português (pt-BR).

## Comandos

- `npm run dev` — servidor de desenvolvimento (Vite).
- `npm run build` — build de produção.
- `npm run lint` — lint (ESLint).
- `npm run preview` — preview do build.
