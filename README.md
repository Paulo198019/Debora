# Débora Kulczar Advocacia

Este projeto é um site profissional desenvolvido com **React + Vite + TailwindCSS** para apresentar informações sobre o escritório Débora Kulczar Advocacia.

## ✅ Estrutura do Projeto
```
debora-kulczar-advocacia/
├── index.html
├── package.json
├── vite.config.ts
├── tsconfig.json
├── tsconfig.node.json
├── public/
│   └── assets/
│       ├── logo.png
│       └── debora-profile.png
├── src/
│   ├── main.tsx
│   ├── App.tsx
│   ├── styles/
│   │   └── globals.css
│   └── components/
│       ├── Header.tsx
│       ├── Hero.tsx
│       ├── About.tsx
│       ├── PracticeAreas.tsx
│       ├── Team.tsx
│       ├── Contact.tsx
│       ├── Footer.tsx
│       └── figma/
│           └── ImageWithFallback.tsx
```

## ✅ Pré-requisitos
- Node.js instalado
- NPM ou Yarn

## ✅ Instalação
```bash
npm install
```

## ✅ Executar em modo desenvolvimento
```bash
npm run dev
```
Acesse: [http://localhost:5173](http://localhost:5173)

## ✅ Build para produção
```bash
npm run build
```
Os arquivos finais estarão na pasta `dist/`.

## ✅ Publicar no GitHub Pages
Instale a dependência:
```bash
npm install gh-pages --save-dev
```
Adicione no `package.json`:
```json
"scripts": {
  "deploy": "gh-pages -d dist"
}
```
Execute:
```bash
npm run deploy
```

## ✅ Substituir Imagens
- Coloque o logotipo em `public/assets/logo.png`
- Coloque a foto da Dra. Débora em `public/assets/debora-profile.png`

## ✅ Observações
- Substitua todos os imports `figma:asset/...` pelos caminhos locais indicados.
- Ajuste os textos conforme necessário.

---
**Contato:**
- Telefone: (11) 92222-8326
- E-mail: debora.kulczar@dkulczar.adv.br
