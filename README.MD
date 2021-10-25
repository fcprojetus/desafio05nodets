Node with Typescript

1. yarn init -y
2. yarn add express
3. yarn add typescript -D
4. yarn tsc —init
5. criar pasta src e arquivo server.ts
6. mudar as configurações do arquivo tsconfig.json "outDir: ./dist" e "rootDir: ./src"
7. yarn add @types/express
8. yarn add ts-node-dev -D (This library plays the same role as nodemon)
9. Criar scripts para rodar o projeto com typescrip

    "scripts": {
        "build": "tsc",
        "dev:server": "ts-node-dev --transpile-only --ignore-watch node_modules src/server.ts"
    },

10. Separação das rotas;
11. yarn add uuid (lib para lidar com ids);
12. yarn add date-fns
