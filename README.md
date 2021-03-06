# api-nps - EM CONSTRUÇÃO

```bash
#código de terminal utilizados

> criar um package.json
yarn init -y

> instalar o express
yarn add express

> instalar a depedência types para entender o import
yarn add @types/express -D

> instalar o typescript
yarn add typescript -D

> inicializar o typescript na aplicação
yarn tsc --init

> instalar a dependência ts-node-dev para converter JS em TS
yarn add ts-node-dev -D

> executar um arquivo em typescript depois de ter colocado scripts no package.json
yarn dev

> rodar o projeto
yarn dev run 
yarn dev

> depois que importar o ./database no server.ts e criar o objeto database no ormconfig.json (irá criar um baco de dados).
yarn dev

> verificar os comandos de uma migration depois que criar o objeto typeorm no objeto scripts em package.json
yarn typeorm

> criar um migration depois que criar o objeto migrationsDir no objeto cli em ormconfig.json
yarn typeorm migration:create -n CreateUsers

> rodar a migration
yarn typeorm migration:run

> dar um rollback (vai rodar somente a ultima migration)
yarn typeorm migration:revert

> criar um uuid (id) no banco de dados
yarn add uuid
> adicionar os tipos de uuid (id)
yarn add @types/uuid -D
```
