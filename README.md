## :page_with_curl: Projeto

![Pizza Shop Gif]()

> <b>Pizza Shop</b> É uma aplicação de gestão de pedidos de restaurantes feito no Ignite da [Rocketseat](https://github.com/Rocketseat). Nessa aplicação o intuito foi fazer tanto o backend e o frontend, ou seja, é uma aplicação full-stack, feita de ponta a ponta. No backend foi utilizado o Bun, ele é uma alternativa ao Node, mas o grade diferencial do Bun para o Node é que ele é feito em cima do do motor do Safari o JavaScriptCore(JS-Core) já o Node é feito em cima da V8 do Chrome, ou seja são dois motores JavaScript diferentes, um dos grandes diferencias de desenvolver com bun além da performance que é superior ao Node, nós temos que configurar muitos menos a parte ferramental, ou seja, nós perdemos muito menos tempo configurando quando se utiliza o bun. Também estamos utilizando o Drizzle ORM no backend, por não estarmos utilizando o Node, foi utilizado o drizzle que não depende de nenhuma API especifica do Node, ele é um ORM agnósticos de run-time, ou seja, ele pode ser executado em qualquer run-time(ambiente) que execute JavaScript diferente do Prisma ORM, outro diferencial do drizzle é que ele não criar uma ponte entre a aplicação e o banco de dados, como por exemplo no Prisma quando executamos qualquer tipo de operação no banco de dados, essa operação não vai direto para o banco de dados, a nossa aplicação envia um binário que é feito em Rust criado pelo time do Prisma e esse binário interpreta a nossa query e envia ela para o banco de dados, ou seja, existe uma ponte no meio que está fazendo o repasse da comunicação entre a nossa aplicação e o banco de dados, basicamente apesar do drizzle ser um ORM ele segue uma API muito mais proxima de um query builder onde nós escrevemos as nossas queries assim muito proximo do que é um SQL.
> Na parte do frontend foi utilizado React com Vite, e react-query para fazer toda a parte cache das requisições.
> Na parte de testes no frontend foi utilizado o Vitest para testes unitários e para testes E2E foi utilizado o Playwright que diferente do Cypress no playwright é possível rodar os testes em simultâneo, no cypress quando rodamos os testes E2E ele sobe um navegador e esse navegador vai rodar os testes em sequencia, já no playwright ele consegue subir várias instâncias do navegador e fazer vários testes ao mesmo tempo e outro diferencial, é que eu consigo rodar os teste em vários navegadores, assim cobrir a mesma funcionalidade em vários navegadores.

## 🚀 Tecnologias/Bibliotecas utilizadas

<a href="https://www.typescriptlang.org/" target="_blank"> <img src="https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=TypeScript&logoColor=white" alt="TypeScript"> </a>
<a href="https://bun.sh/" target="_blank"> <img src="https://img.shields.io/badge/-Bun-14151a?style=flat-square&logo=Bun&logoColor=white" alt="Bun"> </a>
<a href="https://orm.drizzle.team/" target="_blank"> <img src="https://img.shields.io/badge/-Drizzle-120E0E?style=flat-square&logo=drizzle&logoColor=c5f74f" alt="Drizzle"> </a>
<a href="https://pt-br.reactjs.org/" target="_blank"> <img src="https://img.shields.io/badge/-ReactJS-61DAFB?style=flat-square&logo=React&logoColor=white" alt="React"> </a>
<a href="https://vitejs.dev/" target="_blank"> <img src="https://img.shields.io/badge/-Vite-41d1ff?style=flat-square&logo=Vite&logoColor=white" alt="Vite"> </a>
<a href="https://tailwindui.com/documentation" target="_blank"> <img src="https://img.shields.io/badge/-Tailwind-0EA5E9?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind"> </a>
<a href="https://react-hook-form.com/" target="_blank"> <img src="https://img.shields.io/badge/-React%20Hook%20Form-%23EC5990?style=flat-square&logo=reacthookform&logoColor=white" alt="React Hook Form"> </a>
<a href="https://tanstack.com/query/latest/" target="_blank"> <img src="https://img.shields.io/badge/-React%20Query-FF4154?style=flat-square&logo=react%20query&logoColor=white" alt="React Query"> </a>
<a href="https://vitest.dev/" target="_blank"> <img src="https://img.shields.io/badge/-Vitest-86B91A?style=flat-square&logo=vite&logoColor=white" alt="Vitest"> </a>
<a href="https://playwright.dev/" target="_blank"> <img src="https://img.shields.io/badge/-Playwright-58C15D?style=flat-square&logo=playwright&logoColor=white" alt="Playwright"> </a>

## :construction_worker: Executando

```bash
# Clone o Repositório
$ git@github.com:Rodrigo001-dev/pizza-shop.git
```

```bash
# Acesse a pasta do projeto(api)
$ cd pizza-shop/api
```

```bash
# Baixe as dependências(api)
$ bun i
```

```bash
# Execute(api)
$ bun run dev
```

```bash
# Acesse a pasta do projeto(web)
$ cd pizza-shop/web
```

```bash
# Baixe as dependências(web)
$ pnpm i
```

```bash
# Execute(web)
$ pnpm run dev
```

## 💻 Autor

Feito com 💜 by Rodrigo Rael

<a href="https://www.linkedin.com/in/rodrigo-rael-a7a4b51a9/" target="_blank"> <img src="https://img.shields.io/badge/-RodrigoRael-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https" alt="Linkedin Rodrigo"> </a>
<a href="https://img.shields.io/badge/-rodrigorael53@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:rodrigorael53@gmail.com" target="_blank"> <img src="https://img.shields.io/badge/-rodrigorael53@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:rodrigorael53@gmail.com" alt="Gmail Rodrigo"> </a>
