# Stier Bier — Sistema de Delivery

Sistema de controle de delivery (barris, chopeiras, entregas e recolhas) da Stier Bier.

## Como funciona
- `index.html` — todo o sistema (front-end), hospedado como site estático.
- Os dados (pedidos, usuários, financeiro etc.) ficam no **Firebase Firestore**, separado da hospedagem.

## Como publicar uma atualização
1. Substitua o arquivo `index.html` desta pasta pela versão mais nova.
2. Suba a mudança pro GitHub (commit + push).
3. O Vercel detecta o push automaticamente e publica a nova versão em segundos — sem precisar arrastar arquivo de novo.
