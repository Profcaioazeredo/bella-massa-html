# Pizzaria Bella Massa | do HTML ao React

Repositorio base da aula de Desenvolvimento Frontend II (UVA).

## Estrutura
- `referencia-html/`: site original em HTML puro + Bootstrap (2 paginas)
- `src/`: projeto React + TypeScript (Vite) que vamos construir em aula
- `public/img/`: imagens ja copiadas para o React
- `netlify.toml`: configuracao do deploy

## Como comecar
1. Faca o fork deste repositorio no GitHub
2. Clone o seu fork:
   git clone https://github.com/SEU-USUARIO/pizzaria-bella-massa.git
3. Instale e rode:
   cd pizzaria-bella-massa
   npm install
   npm run dev
4. Abra http://localhost:5173 (React) e
   http://localhost:5173/referencia-html/index.html (site original)

## Como este projeto foi criado
npm create vite@latest pizzaria-bella-massa -- --template react-ts
npm install react-bootstrap bootstrap bootstrap-icons
