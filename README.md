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
git@github.com:LottieJudge/fullstackTemplateReact.git
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

#File Tree Template

```sh
src
|
+-- app               # application layer containing:
|   |                 # this folder might differ based on the meta framework used
|   +-- routes        # application routes / can also be pages
|   +-- app.tsx       # main application component
|   +-- provider.tsx  # application provider that wraps the entire application with different global providers - this might also differ based on meta framework used
|   +-- router.tsx    # application router configuration
+-- assets            # assets folder can contain all the static files such as images, fonts, etc.
|
+-- components        # shared components used across the entire application
|
+-- config            # global configurations, exported env variables etc.
|
+-- features          # feature based modules
|
+-- hooks             # shared hooks used across the entire application
|
+-- lib               # reusable libraries preconfigured for the application
|
+-- stores            # global state stores
|
+-- testing           # test utilities and mocks
|
+-- types             # shared types used across the application
|
+-- utils             # shared utility functions
```


