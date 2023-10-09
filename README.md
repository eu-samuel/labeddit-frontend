<img src="https://i.ibb.co/DVLMDr2/image.png" alt="Logo da Labeddit"/>

## Labeddit: A rede social da Labenu

## Índice

• Descrição
<br>
• Layout
<br>
• Como rodar este projeto
<br>
• Linguagens utilizadas
<br>

## Descrição
O projeto Labeddit é parte da última etapa do curso de Desenvolvimento Web Full Stack da escola de programação "Labenu". Trata-se de um pequeno clone da rede social "Reddit" que leva o desenvolvedor a colocar em prática seus conhecimentos em ambas as stacks. Os usuários da Labeddit podem criar suas contas e interagir entre si no fórum único da aplicação através de tópicos e comentários dentro dos mesmos. Caso desejem, os usuários podem alterar seus dados ou deletar a conta (o que, claro, não queremos que vocês façam 😭).

## Layout
Em conjunto com o tailwind.css, o Labeddit foi criado visando o modelo mobile-first, com a responsividade sendo voltada para adaptar o projeto para desktops e tablets. Alguns componentes foram customizados através de Charka UI porém. 

#### Tela de cadastro
<img src="https://i.ibb.co/d7yF6fL/image.png" alt="Tela de cadastro"/>

#### Tela de login
<img src="https://i.ibb.co/Bnmj1hS/image.png" alt="Tela de login"/>

#### Fórum 
<img src="https://i.ibb.co/T8N8NTH/image.png" alt="Fórum"/>

#### Página da postagem com comentários

<img src="https://i.ibb.co/7kF7dF1/image.png" alt="Postagem"/>

(Não é possível editar comentários)

#### Página para alteração de dados do usuário

<img src="https://i.ibb.co/8271Mt0/image.png" alt="Página de alterar dados"/>

#### Página para o usuário deletar a conta (favor, não querer usá-la 😭)

<img src="https://i.ibb.co/7NKsYVs/image.png" alt="Página para deletar a conta"/>


## Como rodar este projeto

#### Faça o fork deste repositório para o seu perfil clicando no link abaixo.
<a href="https://github.com/eu-samuel/labeddit-frontend/fork"><img alt="Static Badge" src="https://img.shields.io/badge/FORK-frontend?color=red"></a>

#### Em seu editor de código, faça o clone do repositório forkado.
$ git clone https://github.com/seuUsuario/labeddit-frontend.git

#### Acesse a pasta do repositório no terminal git/git bash
$ cd labeddit-frontend

#### Instale as dependências utilizadas no mesmo
````
$ npm install
$ npm i react-icons
$ npm i @chakra-ui/react @emotion/react @emotion/styled framer-motion
$ npm install -D tailwindcss
$ npm i postcss autoprefixer
````

O tailwind.css já está configurado, então você precisará apenas o instalar via terminal.

#### Execute a aplicação
````
$ npm run dev
````
Obs: O projeto rodará na porta 5173. Para acessar em seu navegador, utilize o link: 
**https://localhost:5173**


#### Rodando localmente

Caso deseje rodar todas as funcionalidades localmente, devido a instabilidade do servidor, você terá que utilizar o repositório do back-end. Este repositório é relativo ao front-end da aplicação, para conferir o repositório da API, acesse clicando na badge a seguir:

<a href="http://github.com/eu-samuel/labeddit-backend"><img alt="Static Badge" src="https://img.shields.io/badge/BACKEND-backend?color=blue"></a>

Após seguir os passos de instalação de dependências do backend, entre na pasta do backend e faça o comando a seguir:

````
$ npm run dev
````

O back-end roda na porta 3003, você terá que alterar a BASE_URL da api do frontend para http://localhost:3003 pelo seguinte caminho:

````
src/assets/scripts/Functions.js
````

<img src="https://i.ibb.co/CMwD391/image.png" alt="Caminho para alterar a BASE_URL"/>

e procurar pela variável BASE_URL ao fim do código.

<img src="https://i.ibb.co/0JwZ1X7/image.png" alt="constante BASE_URL"/>

## Linguagens utilizadas 

### Editor de código utilizado

![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
 
### Front-end

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)

### Back-end

![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Jest](https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white)
![Render](https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white)


