# Shopping App

A small React shopping interface project with components for cart totals, selected items, and delivery location. The codebase uses React Context as the starting point for shared shopping state.

> **Project status:** The repository is currently a starter project. The main `App` component renders an empty container, and the context and screens need to be connected before the shopping flow is usable.

## Tech stack
- React 18 and Create React App
- React Context and `useReducer`
- Bootstrap 5 and React Icons

## Getting started
```bash
git clone https://github.com/IbrahemMohammad09/kduia-shopping-app.git
cd kduia-shopping-app
npm install
npm start
```

Open [http://localhost:3000](http://localhost:3000) after the development server starts.

## Available scripts
- `npm start` — run the app locally.
- `npm test` — run tests in watch mode.
- `npm run build` — create a production build.
- `npm run eject` — expose the Create React App configuration (one-way).

## Project structure
- `src/components/` — cart, item selection, expenses, and location components.
- `src/context/AppContext.js` — shared application state (in progress).

## License
See [LICENSE](LICENSE) for the project's license terms.
