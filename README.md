<h1 align="center">
    <img alt="Proffy" title="Proffy" src=".github/logo.svg" width="220px" />
</h1>

<br>

<p align="center">
  <img alt="Ecoleta" src=".github/layout.png" width="100%">
</p>

## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [React](https://reactjs.org)

## 💻 Projeto

**Proffy** - Plataforma de estudos online onde alunos podem se conectar com professores.

## 🔖 Layout

Você pode visualizar o layout do projeto no Figma, ele está dividido em duas versões:

- <div style="display:flex;align-items:center;">
      Layout do projeto web <img src="https://img.shields.io/badge/-Figma-rebeccapurple?&logo=Figma&logoColor=white&link=https://www.notion.so/Layout-Proffy-3d5f45f54ec54ef9b2103565b7cce4e1)" style="margin-left:8px;"/>
  </div>

- <div style="display:flex;align-items:center;margin-top:12px;">
      Layout do projeto mobile <img src="https://img.shields.io/badge/-Figma-purple?&logo=Figma&logoColor=white&link=https://www.notion.so/Layout-Proffy-3d5f45f54ec54ef9b2103565b7cce4e1)" style="margin-left:8px;"/>
  </div>

## 🚀 Como rodar o projeto

Podemos considerar este projeto como sendo divido em três partes:

1. Front End (pasta web)

💡

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/).
Além disto é bom ter um editor para trabalhar com o código como _VSCode_

## Clonando o projeto

Comece realizando um clone deste projeto, se preferir você também pode baixar como um .zip acessando o site do GitHub

```bash
# Clone este repositório
$ git clone https://github.com/leon-carvalho/proffy

# Acesse a pasta do projeto no seu terminal/cmd
$ cd proffy
```

## Rodando o back end (servidor)

```bash
# Vá para a pasta da aplicação Front End
$ cd server

# Instale as dependências
$ npm install
# Ou use Yarn se preferir
$ yarn

# Rode as migrations do banco de dados
$ npm run knex:migrate
# Ou use Yarn
$ yarn knex:migrate

# Execute a aplicação em modo de desenvolvimento
$ npm run start
# Ou use Yarn se preferir
$ yarn start

# A aplicação será aberta na porta:3333
```

### Rodando a aplicação web (Front End)

```bash
# Vá para a pasta da aplicação Front End
$ cd web

# Instale as dependências
$ npm install
# Ou use Yarn se preferir
$ yarn

# Execute a aplicação em modo de desenvolvimento
$ npm run start
# Ou use Yarn se preferir
$ yarn start

# A aplicação será aberta na porta:3000 - acesse http://localhost:3000
```

### Rodando a aplicação mobile

```bash
  ...em breve
```

## 🤔 Como contribuir

- Faça um fork desse repositório;
- Cria uma branch com a sua feature: `git checkout -b minha-feature`;
- Faça commit das suas alterações: `git commit -m 'feat: Minha nova feature'`;
- Faça push para a sua branch: `git push origin minha-feature`.

Depois que o merge da sua pull request for feito, você pode deletar a sua branch.

## 📝 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

## 🙌 Agradecimentos

- [Time da RocketSeat](https://rocketseat.com.br/)
- [Diego Fernandes, CTO e Instrutor da Rocketseat](https://github.com/diego3g)

---

Feito com ♥ por Leonardo Carvalho

<a href="https://www.linkedin.com/in/leonardo-dev/">
  <img alt="Made by leon-carvalho" src="https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/leonardo-dev/">
</a>

<a href="https://github.com/leon-carvalho" style="margin-left: 8px;">
  <img alt="Made by leon-carvalho" src="https://img.shields.io/badge/-GitHub-grey?style=flat&logo=GitHub&logoColor=white&link=https://github.com/leon-carvalho">
</a>
