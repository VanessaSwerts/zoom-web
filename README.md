<p align="center"> 
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/VanessaSwerts/zoom-web?color=%2304D361">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/VanessaSwerts/zoom-web">
  
  <a href="https://github.com/VanessaSwerts/zoom-web/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/VanessaSwerts/zoom-web">
  </a>   
  
</p>

<h4 align="center"> 
	🚧 Zoom Web Clone - Concluído 🚧
</h4>

<p align="center">
 <a href="#-sobre-o-projeto">Sobre</a> •
 <a href="#-layout">Layout</a> • 
 <a href="#-como-executar-o-projeto">Como executar</a> • 
 <a href="#-autora">Autor</a> 
</p>


## 💻 Sobre o projeto

Este é um clone web do Zoom feito com Javascript, utilizando conceitos de Peer-to-Peer e WebRTC, feito sob tutela do [ErickWendel](https://github.com/ErickWendel) no seu treinamento [Semana JS Expert](https://www.youtube.com/watch?v=zAEu5Smx5h4&list=PLqFwRPueWb5c0z0-MOSbxzrRtZI9nwXgv&index=1) .

No desenvolvimento da aplicação, são vistos conceitos de comunicação em tempo real, com a implementação de salas de conferência de vídeo/audio, geração de arquivos e download de binários. Os códigos também são criados utilizando patterns de camadas e divisão de responsabilidades, com algumas boas práticas de organização.

---
## 🎨 Layout
	
#### :point_right: Home Page
<p align="center">
  <img alt="Home" src="./public/prints/home.png" width="70%;">    
</p>

#### :point_right: Room
<p align="center">
   <img alt="Room" src="./public/prints/room.png" width="70%;">
</p>

## 🚀 Como executar o projeto

### Existem três serviços no projeto:

- **Public**: Frontend da aplicação, onde estão as salas e onde é possível conversar com seus amiguinhos pela aplicação.
- **Server**: Este é o servidor de sockets, onde os usuários se conectam através do frontend para poder se comunicar e compartilhar eventos na rede.
- **Peer-Server**: Este é o servidor peer-to-peer, que possibilita chamadas diretas entre dois usuários, para a transmissão de áudio e vídeo.

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/).

**Obs**: É recomendável que a aplicaçãos eja usada no Navegador Google Chrome.

#### Executando o projeto

##### 🧭 Rodando a aplicação Frontend

   ```bash
    # Clone este repositório
    $ git clone https://github.com/VanessaSwerts/zoom-web.git

    # Acesse a pasta do projeto no seu terminal/cmd
    $ cd zoom-web
    
    # Acesse a pasta do fron end projeto no seu terminal/cmd
    $ cd public

    # Instale as dependências
    $ npm install

    # Execute a aplicação
    $ npm start   

    # O servidor inciará na porta:8080 - acesse http://localhost:8080 .
   ```
##### 🧭 Rodando a aplicação Server

   ```bash  
    # Acesse a pasta do server projeto no seu terminal/cmd
    $ cd server

    # Instale as dependências
    $ npm install

    # Execute a aplicação
    $ npm start ou npm run dev   

   ```

##### 🧭 Rodando a aplicação Peer Server

   ```bash 
    # Acesse a pasta do fron end projeto no seu terminal/cmd
    $ cd peer-server

    # Instale as dependências
    $ npm install

    # Execute a aplicação
    $ npm start

   ```

---

## 🦸 Autora

<table>
  <tr>   
    <td align="center"><a href="https://github.com/vanessaSwerts/"><img style="border-radius: 50%;" src="https://avatars2.githubusercontent.com/u/57146734?v=4" width="100px;" alt=""/><br /><sub><b>Vanessa Swerts</b></sub></a></td>  
  </tr>
</table>


---

## :clap: Créditos

- Layout da home foi baseada no codepen do [Nelson Adonis Hernandez](https://codepen.io/nelsonher019/pen/eYZBqOm)
- Layout da room foi adaptado a partir do repo do canal [CleverProgrammers](https://github.com/CleverProgrammers/nodejs-zoom-clone/blob/master/views/room.ejs)
