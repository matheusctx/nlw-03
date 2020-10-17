<h1 align="center">Happy</h1>
<p align="center">😀 Faça o dia de uma criança mais feliz! Com o Happy você encontra orfanatos para visitas mais próximo de você.</p>

<p align="center">
  <a href="https://github.com/matheusctx/nlw-03/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/matheusctx/nlw-03">
  </a>
  
   <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen"> 
   
   <a href="https://www.twitter.com/matheusctx/">
    <img alt="Siga no Twitter" src="https://img.shields.io/twitter/url?url=https%3A%2F%2Fgithub.com%2Ftgmarinho%2FREADME-ecoleta">
  </a>
</p>

![happy](https://user-images.githubusercontent.com/64803412/96346699-9ad70b80-1073-11eb-8cac-2308a639bcfc.png)


<h4 align="center"> 
	👩🏼‍🤝‍🧑🏼 Happy: Concluído 🚀 🙂
</h4>

<p align="center">
 <a href="#-sobre-o-projeto">Sobre</a> •
 <a href="#-funcionalidades">Funcionalidades</a> • 
 <a href="#-como-executar-o-projeto">Como executar</a> • 
 <a href="#-tecnologias">Tecnologias</a> • 
 <a href="#-autor">Autor</a> • 
 <a href="#user-content--licença">Licença</a>
</p>


## 💻 Sobre o projeto

👩🏼‍🤝‍🧑🏼 Happy - é uma forma de conectar você a orfanatos próximos para realizar a visitação, tornando assim o dia de uma criança ainda mais feliz!


Projeto desenvolvido durante a **NLW - Next Level Week - 3ª edição** oferecida pela [Rocketseat](https://rocketseat.com.br).
O NLW é uma experiência online com muito conteúdo prático, desafios e hacks onde o conteúdo fica disponível durante uma semana.

---

## ⚙️ Funcionalidades

- [x] Happy 1.0
- [x] Whatsapp para contato
- [ ] Happy 2.0

---

## 🚀 Como executar o projeto

Este projeto é divido em três partes:
1. Backend (pasta backend) 
2. Frontend (pasta web)
3. Mobile (pasta mobile)

💡 Tanto o Frontend quanto o Mobile precisam que o Backend esteja sendo executado para funcionar.

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/) e o [Yarn](https://yarnpkg.com/). 
Ademais, é aconselhável ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/).

#### 🎲 Rodando o Backend (servidor)

```bash

# Clone este repositório
$ git clone git@github.com:matheusctx/nlw-03.git

# Acesse a pasta do projeto no terminal/cmd
$ cd nlw-03

# Vá para a pasta backend
$ cd backend

# Instale as dependências
$ yarn

# Execute a aplicação em modo de desenvolvimento
$ yarn dev

# O servidor inciará na porta:3333 - acesse http://localhost:3333 

```


#### 🧭 Rodando a aplicação web (Frontend)

```bash

# Clone este repositório
$ git clone git@github.com:matheusctx/nlw-03.git

# Acesse a pasta do projeto no seu terminal/cmd
$ cd nlw-03

# Vá para a pasta da aplicação Front End
$ cd web

# Instale as dependências
$ yarn

# Execute a aplicação em modo de desenvolvimento
$ yarn start

# A aplicação será aberta na porta:3000 - acesse http://localhost:3000

```
#### 📱 Rodando a aplicação mobile (Mobile)

```bash

# Clone este repositório
$ git clone git@github.com:matheusctx/nlw-03.git

# Acesse a pasta do projeto no seu terminal/cmd
$ cd nlw-03

# Vá para a pasta da aplicação Front End
$ cd mobile

# Instale as dependências
$ yarn

# Execute a aplicação em modo de desenvolvimento
$ yarn start

# A aplicação será aberta no Expo - acesse http://localhost:19002

```

---

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

#### **Website**  ([React](https://reactjs.org/)  +  [TypeScript](https://www.typescriptlang.org/))

-   **[React Router Dom](https://github.com/ReactTraining/react-router/tree/master/packages/react-router-dom)**
-   **[React Icons](https://react-icons.github.io/react-icons/)**
-   **[Axios](https://github.com/axios/axios)**
-   **[Leaflet](https://react-leaflet.js.org/en/)**
-   **[React Leaflet](https://react-leaflet.js.org/)**

> Veja o arquivo  [package.json](https://github.com/matheusctx/nlw-03/blob/master/web/package.json)

#### **Backend**  ([NodeJS](https://nodejs.org/en/)  +  [TypeScript](https://www.typescriptlang.org/))

-   **[Express](https://expressjs.com/)**
-   **[CORS](https://expressjs.com/en/resources/middleware/cors.html)**
-   **[TypeORM](https://typeorm.io/)**
-   **[SQLite](https://github.com/mapbox/node-sqlite3)**
-   **[ts-node](https://github.com/TypeStrong/ts-node)**
-   **[Multer](https://github.com/expressjs/multer)**
-   **[Yup](https://github.com/jquense/yup)**

> Veja o arquivo  [package.json](https://github.com/matheusctx/nlw-03/blob/master/backend/package.json)

#### **Mobile**  ([React Native](http://www.reactnative.com/)  +  [TypeScript](https://www.typescriptlang.org/))

-   **[Expo](https://expo.io/)**
-   **[Expo Google Fonts](https://github.com/expo/google-fonts)**
-   **[React Navigation](https://reactnavigation.org/)**
-   **[React Native Maps](https://github.com/react-native-community/react-native-maps)**
-   **[Expo Fonts](https://docs.expo.io/versions/latest/sdk/font/)**
-   **[Axios](https://github.com/axios/axios)**

> Veja o arquivo  [package.json](https://github.com/matheusctx/nlw-03/blob/master/mobile/package.json)

#### **Utilitários**

-   Protótipo:  **[Figma](https://www.figma.com/)**  →  **[Protótipo Web](https://www.figma.com/file/mDEbnoojksG4w8sOxmudh3/Happy-Web)** →  **[Protótipo Mobile](https://www.figma.com/file/X27FfVxAgy9f5IFa7ONlph/Happy-Mobile)**
-   Maps:  **[Leaflet](https://react-leaflet.js.org/en/)**
-   Editor:  **[Visual Studio Code](https://code.visualstudio.com/)**  → Extensions:  **[SQLite](https://marketplace.visualstudio.com/items?itemName=alexcvzz.vscode-sqlite)**
-   Teste de API:  **[Insomnia](https://insomnia.rest/)**
-   Ícones:  **[Feather Icons](https://feathericons.com/)**,  **[Font Awesome](https://fontawesome.com/)**
-   Fontes:  **[Nunito](https://fonts.google.com/specimen/Nunito)**


---

## 💪 Como contribuir para o projeto

1. Faça um **fork** do projeto.
2. Crie uma nova branch com as suas alterações: `git checkout -b my-feature`
3. Salve as alterações e crie uma mensagem de commit contando o que você fez: `git commit -m "feature: My new feature"`
4. Envie as suas alterações: `git push origin my-feature`
> Caso tenha alguma dúvida confira este [guia de como contribuir no GitHub](./CONTRIBUTING.md)

---

## 🦸 Autor

 <img style="border-radius: 50%;" src="https://avatars0.githubusercontent.com/u/64803412?s=460&u=88bfa07a4898a7bb76f4dc0f9ab560242cfa8c8a&v=4" width="120px;" alt=""/>

[![Twitter Badge](https://img.shields.io/badge/-@matheusctx-1ca0f1?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/matheusctx)](https://twitter.com/matheusctx)
<br />
[![Linkedin Badge](https://img.shields.io/badge/-Matheus_Teixeira-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/matheusctx/)](https://www.linkedin.com/in/matheusctx/)
<br />
[![Gmail Badge](https://img.shields.io/badge/-mathcardosoteixeira@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:mathcardosoteixeira@gmail.com)](mailto:mathcardosoteixeira@gmail.com)

---

## 📝 Licença

Este projeto esta sobe a licença [MIT](./LICENSE).

Feito com ❤️ por Matheus Teixeira 👋🏽 [Entre em contato!](https://www.linkedin.com/in/matheusctx/)
