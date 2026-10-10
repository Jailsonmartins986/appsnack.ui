# AppSnack UI

Interface web (mobile-first) do **AppSnack** - React 18 + Vite + React Router + Axios.
Consome a API `appsnack-api` (porta 3333).

## Como executar
```bash
npm install
npm run dev          # http://localhost:5173  (o Vite encaminha /api para localhost:3333)
npm run build        # gera a pasta dist/ para publicação
```
Suba antes a API (`npm run dev` na pasta appsnack-api) e rode `npm run seed` para ter dados de teste.

## Telas
Login - Cadastro - Cardápio (com detalhes do produto) - Carrinho - Checkout - Acompanhamento do pedido -
Histórico/Avaliação - Painel do fornecedor - Gestão de cardápio - Relatórios.
