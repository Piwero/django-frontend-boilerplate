# Django boilerplate project
- Use it to quickly create Django-React projects with Poetry and linting on pre-commit.

# Set up Frontend
## Option 1 React
run the next commands
`npm create vite@latest frontend -- --template react`
`cd frontend`
`npm install`
`npm run dev`

## Option 2 React-TypeScript
run the next commands
`npm create vite@latest frontend -- --template react-ts`
`cd frontend`
`npm install`
`npm run dev`

## Add dependencies
### Tailwind css
`npm install -D tailwindcss postcss autoprefixer`
Follow more instructions on https://tailwindcss.com/docs/guides/vite
### Jest
`npm install --save-dev jest`
### eslint
`npm init @eslint/config`
## Prettier
`npm install --save-dev --save-exact prettier`
`echo {}> .prettierrc.json`
## Storybook
`npx sb init --builder @storybook/builder-vite`
`npm run storybook`

