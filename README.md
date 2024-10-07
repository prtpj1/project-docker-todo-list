# 18º Projeto: Docker - Todo List
<p align="center">
  <img src="https://github.com/prtpj1/prtpj1/blob/main/Headers/18%20-%20DockerTodoList.png?raw=true" alt="Header" />
</p>

---
<p align="center">
<a href="#project-description">Project Description</a> •
<a href="#in-this-project-i-learned-and-put-into-practice">Learning</a> •
<a href="#according-to-the-project-requirements-designated-by-trybe-i-learned-how-to">Requirements</a> •
<a href="#stacks">Stacks</a> •
<a href="#how-to-run-the-application">How to run the application</a>
</p>

---
<p align="center">
<a href="#descrição-do-projeto">Descrição do Projeto</a> •
<a href="#nesse-projeto-aprendi-e-coloquei-em-prática">Aprendizado</a> •
<a href="#de-acordo-com-os-requisitos-do-projeto-designados-pela-trybe-aprendi-como">Requisitos</a> •
<a href="#tecnologias-utilizadas">Tecnologias Utilizadas</a> •
<a href="#como-rodar-a-aplicação">Rodar a Aplicação</a>
</p>

---
## Project Description
This was my first BackEnd project and the first time I worked with Docker, as well as my learning about Docker.

In this project, a fullstack Todo List app was provided by Trybe.

I learned the first steps of how to containerize an application using Docker.

## In this project, I learned and put into practice
- Containerizing applications
- Creating images for applications
- Configuring these images with docker-compose
- Using a variety of Docker commands with different levels of complexity

## According to the project requirements designated by Trybe, I learned how to
- ✅ Create a container in interactive mode, without running it, setting a name and using the `alpine` image version `3.12`
- ✅ Start the created container
- ✅ List the containers filtering by the name of the new container
- ✅ Execute the command `cat /etc/os-release` in the created container without attaching to it
- ✅ Remove the created container
- ✅ Download the `nginx` image with version `1.21.3-alpine` without creating or running a container
- ✅ Run a new container with the `nginx` image version `1.21.3-alpine` in the background, setting the name of the image and mapping its default access port to port `3000` of the host system
- ✅ Stop the container of the created image that is currently running
- ✅ Generate a build from the Dockerfile of the back-end of the `todo-app`, naming the image as `todobackend`
- ❌ Generate a build from the Dockerfile of the front-end of the `todo-app`, naming the image as `todofrontend`
- ❌ Generate a build from the Dockerfile of the tests of the `todo-app`, naming the image as `todotests`
- ❌ Start an orchestration in the background with `docker-compose` so that `backend`, `frontend`, and `tests` can communicate

_*NOTE: In some projects, some requirements were not completed due to the accelerated dynamics of the course and not because I didn't know how to do them. At the time, I just needed a little more time.*_

_*I have not yet decided whether it is better to leave it this way to demonstrate my progress during my learning or if it would be better to complete the missing requirements in the course projects.*_

_*Feedback is welcome.*_

## Stacks
### BackEnd
- Docker
- Node.js

<a href="https://nodejs.org/en/" target="_blank" rel="noreferrer"><img src="https://github.com/prtpj1/prtpj1/blob/main/Github Imgs/NodeJS2.png" width="50" height="50" alt="NodeJS Icon" /></a>
<a href="https://www.docker.com/" target="_blank" rel="noreferrer"><img src="https://github.com/prtpj1/prtpj1/blob/main/Github Imgs/Docker2.png" width="50" height="50" alt="Docker Icon" /></a>

## How to run the application?
- Make sure Docker is running on your machine
- Clone the repository: <br>
`git clone git@github.com:prtpj1/project-docker-todo-list.git`
- Access the project folder: <br>
`cd project-docker-todo-list`
- Install the dependencies: <br>
`npm install`
- Open VS Code: <br>
`code .` <br>
- Inside the folder `%/docker/docker-commands`, there will be 9 files with commands used by Docker 
- Copy the command line from the first file `command01.dc`, paste it into your terminal, and execute 
- Repeat the process following the numerical order of the files until you execute the last command

---
## Descrição do Projeto
Este foi meu primeiro projeto de BackEnd e a primeira vez que fiz qualquer coisa com Docker, assim como o aprendizado sobre Docker.

Neste projeto, foi fornecido pela Trybe um projeto fullstack, um app de Todo List.

E aprendi os primeiros passos de como containerizar uma aplicação utilizando Docker.

## Nesse projeto, aprendi e coloquei em prática
- Conteinerizar aplicações
- Criar as imagens para as aplicações
- Configurar essas imagens com o docker-compose
- Utilizar uma série de comandos do docker com diferentes níveis de complexidade

## De acordo com os requisitos do projeto designados pela Trybe aprendi como
- ✅ Criar um container em modo interativo, sem rodá-lo, definindo um nome e utilizando a imagem `alpine` na versão `3.12`
- ✅ Iniciar o container criado
- ✅ Listar os containers filtrando pelo nome do novo container
- ✅ Executar o comando `cat /etc/os-release` no container criado sem se acoplar a ele
- ✅ Remover o container criado
- ✅ Fazer o download da imagem `nginx` com a versão `1.21.3-alpine` sem criar ou rodar um container
- ✅ Rodar um novo container com a imagem `nginx` com a versão `1.21.3-alpine` em segundo plano, definindo o nome da imagem e mapeando sua porta padrão de acesso para porta `3000` do sistema hospedeiro
- ✅ Parar o container da imagem criada, que está em andamento
- ✅ Gerar uma build a partir do Dockerfile do back-end do `todo-app`, nomeando a imagem para `todobackend`
- ❌ Gerar uma build a partir do Dockerfile do front-end do `todo-app`, nomeando a imagem para `todofrontend`
- ❌ Gerar uma build a partir do Dockerfile dos testes do `todo-app`, nomeando a imagem para `todotests`
- ❌ Subir uma orquestração em segundo plano com o `docker-compose` de forma que `backend`, `frontend` e `tests` consigam se comunicar

_*OBS: Em alguns projetos alguns requisitos não foram feitos devido a dinamica acelerada do curso e não por eu não saber como fazê-los. Na época eu apenas precisaria de um pouco mais de tempo.*_

_*Ainda não decidi se é melhor deixar desta forma para demonstrar o meu progresso durante meu aprendizado ou se seria melhor completar os requisitos que ficaram faltando nos projetos do curso.*_

_*Feedbacks são bem vindos.*_

## Tecnologias Utilizadas
### BackEnd
- Docker
- Node.js

<a href="https://nodejs.org/en/" target="_blank" rel="noreferrer"><img src="https://github.com/prtpj1/prtpj1/blob/main/Github Imgs/NodeJS2.png" width="50" height="50" alt="NodeJS Icon" /></a>
<a href="https://www.docker.com/" target="_blank" rel="noreferrer"><img src="https://github.com/prtpj1/prtpj1/blob/main/Github Imgs/Docker2.png" width="50" height="50" alt="Docker Icon" /></a>

## Como rodar a aplicação?
- Verifique se o Docker está rodando na sua máquina <br>
- Clone o repositório: <br>
`git clone git@github.com:prtpj1/project-docker-todo-list.git`
- Acesse a pasta do projeto: <br>
`cd project-docker-todo-list`
- Instale as dependências: <br>
`npm install`
- Abra o VS Code: <br>
`code .` <br>
- Dentro da pasta `%/docker/docker-commands`, haverão 9 arquivos com comandos utilizados pelo Docker 
- Copie a linha de comando do primeiro arquivo `command01.dc`, cole no seu terminal e execute 
- Repita o processo seguindo a ordem numérica dos arquivos até executar o ultimo comando 
