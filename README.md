# serverless-graphql-starter

## Install

```bash
git clone https://github.com/ysfmag/serverless-graphql-starter.git
cd serverless-graphql-starter
yarn 
yarn start
```

## Test Graphql

```bash
curl -d '{"query":"{posts{id title} author(id: 1) { firstName lastName} }"}' -H "Content-Type: application/json" -X POST http://localhost:3000/graphql
```
