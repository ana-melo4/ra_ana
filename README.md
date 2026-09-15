## Como rodar o projeto

Primeiro, instale as dependências:

```bash
npm i
```

crie o .env

DATABASE_URL="postgresql://postgres:senai@localhost:5432/ra_ana?schema=public"

Depois execute:
npx prisma generate
npx prisma migrate dev

Por último, inicie o projeto:
npm run dev

baixe o thunderclient
teste a api

rota: localhost:3000/treinos