# Back-end do CodeGenius
Esse back-end funciona por meio de funções serverless. Ele usa por padrão o nodejs versão 16, que até 2024 é a versão padrão mais recente do nodejs na maioria dos provedores de serverless.




## Arquivos relacionados à natureza serverless
- `src/index.ts`
- `src/swagger.ts`
- `serverless.yml`

- `package.json`


## Instalando dependências globais

```
npm install @nestjs/cli serverless -g
```


### Development
#### usando NestCLI

```
$ yarn start
```



#### use serverless-offline se preferir

```bash
$ sls offline
```



##  Deploy
```bash
$ yarn  build && sls deploy
```

