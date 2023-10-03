# upload-ai-api

## Rodando localmente

Clone o projeto

```bash
  git clone git@github.com:NicolasFreitas1/upload-ai-api.git
```

Entre no diretório do projeto

```bash
  cd upload-ai-api.git
```

Instale as dependências

```bash
  npm install
```

Inicie o banco de dados

```bash
  npx prisma migrate dev
```

Popule o banco de dados

```bash
  npx prisma db seed
```

Inicie a aplicação

```bash
  npm run dev
```

## Variáveis de Ambiente

Para rodar esse projeto, você vai precisar adicionar as seguintes variáveis de ambiente no seu .env

`OPENAI_KEY=""`

`DATABASE_URL="file:./dev.db"`

Para conseguir a chave de api da openai acesse [OPENAI](https://platform.openai.com/account/api-keys) e faça seu registro
