# React
Começar com React é uma excelente escolha na jornada de desenvolvimento Front-end

(Atualmente: 2026) Ferramenta padrão para iniciar React:
- Vite

## 1. Prepare o Ambiente (Pré-Requisitos)
- Node (Uso do NPM)
{ Para checar se está instalado: No terminal use "node -v ou npm -v" }

## 2. Crie o Projeto React
No terminal, navegue ate a pasta onde deseja salvar o seu projeto
- Digite: npm create vite@latest meu-primeiro-projeto -- --template react

## 3. Instale as Dependências e Inicie o Servidor
- cd meu-primeiro-projeto
- npm install
- npm run dev

## 4. Estrutura: Conceitos Básicos
A mágica do React acontece na pasta src. Aqui estão os arquivos mais importantes para você começar:
- => main.jsx: É o ponto de entrada da aplicação. Ele pega o seu aplicativo React e o injeta no HTML.
- => App.jsx: É o seu componente principal. Quase todo o código que você vai escrever no começo ficará aqui ou será chamado por aqui.
- => App.css e index.css: Arquivos de estilização.

## 5. Apresente-se ao Mundo!
Em App.jsx:

```jsx
import './App.css'

function App() {
  return (
    <div>
      <h1>Olá, Mundo!</h1>
      <p>Este é o meu primeiro aplicativo em React.</p>
    </div>
  )
}

export default App
