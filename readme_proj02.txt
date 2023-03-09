1. npm create vite@latest
   nome: 02-ignite-timer
   react-ts
   
2. 
index.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ignite Times</title>
  </head>
  <body>
    <div id="root"></div>
    <script type="module" src="/src/main.tsx"></script>
  </body>
</html>

app.tsx
export function App() {
  return (
   <h1>Hello</h1>
  )
}

main.tsx
import React from 'react'
import ReactDOM from 'react-dom/client'
import { App } from './App'

ReactDOM.createRoot(document.getElementById('root') as HTMLElement).render(
  <React.StrictMode>
    <App />
  </React.StrictMode>,
)

3. npm install
   npm run dev
   http://127.0.0.1:5173/
   
4. npm install styled-components   
   npm install @types/styled-components -D
   
5. instalar a extensao no vscode vscode-styled-components  ( aplicar a sintaxe do css ) 
   
6. instalar a extensao no vscode ESlint
   npm install eslint -D
   npm install @rocketseat/eslint-config -D
   npx eslint --init  ( para criar o seu proprio padrao de projeto com eslint )
   