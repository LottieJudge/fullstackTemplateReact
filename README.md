# Full-stack template

This is a starter template to get you going with the must-have libraries for every project.

The starter includes the following libraries:
- `@tanstack/react-query`
- `axios`
- `tailwind`
- `classnames`
- `tailwind-merge`
- `eslint` 
- `prettier`
- `React Router`
- `Jest`

Also, relative paths are setup in the `tsconfig.json` file so that you can easily import anything you need relatively.

## How to use this starter

---
Clone the repository:
```
https://github.com/Tenacity-Dev/vite-react-ts-tailwind-tanstack-query-eslint-prettier.git
```

cd into the repository:
```
cd vite-react-ts-tailwind-tanstack-query-eslint-prettier
```

To make this repository yours:
```
rm -rf .git && git init 
git remote add origin <your repos name here>
git remote -v (to ensure you're in the right repo)
git add .
git commit -m "Initial commit"
```

Install dependencies:
```
npm install
```

Start the local server:
```
npm run web
```

# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
