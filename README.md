# React.js e Next.js

Criar projeto React com `typescript`:

```
yarn create react-app moveit --template=typescript
yarn start
```

Criar projeto Next:

```
yarn create next-app moveit-next

yarn add typescript @types/react @types/react-dom @types/node -D
yarn dev
```

## Figma do Projeto Moveit

[Projeto no Figma](https://www.figma.com/file/eEHh4UQWeiAG0KVyydfmhk/Move.it-2.0-(Copy)?node-id=149854%3A100)

## Cookies

```
yarn add js-cookie
yarn add @types/js-cookie -D
```

##  Deploy na vercel

```
yarn global add vercel
```

Adicionar no PATH (`.zshrc`):

```
export PATH=$PATH:$(yarn global bin)
```

Login: `vercel login`
Deploy: `vercel`
Deploy em Produção: `vercel --prod`