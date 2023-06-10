# 18º Projeto: Docker - Todo List

<p align="center">
<img src="https://github.com/prtpj1/prtpj1/blob/main/Github%20Imgs/18%20-%20DockerTodoList.png" alt="Header" />
<hr/>

<p align="center">
<a href="#descrição-do-projeto">Descrição do Projeto</a> •
<a href="#nesse-projeto-aprendi-e-coloquei-em-prática">Aprendizado</a> •
<a href="#de-acordo-com-os-requisitos-do-projeto-designados-pela-trybe-aprendi-como">Requisitos</a> •
<a href="#tecnologias-utilizadas">Tecnologias Utilizadas</a> •
<a href="#como-rodar-a-aplicação">Rodar a Aplicação</a>
</p>
<hr/>

## Descrição do Projeto
Este foi meu primeiro projeto de BackEnd e a primeira vez que fiz qualquer coisa com Docker, assim como o aprendizado sobre Docker.<br>
Neste projeto, foi fornecido pela Trybe um projeto fullstack, um app de Todo List.<br>
E aprendi os primeiros passos de como containerizar uma aplicação utilizando Docker.<br>

## Nesse projeto, aprendi e coloquei em prática:
- Conteinerizar aplicações
- Criar as imagens para as aplicações
- Configurar essas imagens com o docker-compose
- Utilizar uma série de comandos do docker com diferentes níveis de complexidade

## De acordo com os requisitos do projeto designados pela Trybe aprendi como:
- Criar um container em modo interativo, sem rodá-lo, definindo um nome e utilizando a imagem alpine na versão 3.12 ✅
- Iniciar o container criado ✅
- Listar os containers filtrando pelo nome do novo container ✅
- Executar o comando "cat /etc/os-release" no container criado sem se acoplar a ele ✅
- Remover o container criado ✅
- Fazer o download da imagem nginx com a versão 1.21.3-alpine sem criar ou rodar um container ✅
- Rodar um novo container com a imagem nginx com a versão 1.21.3-alpine em segundo plano, definindo o nome da imagem e mapeando sua porta padrão de acesso para porta 3000 do sistema hospedeiro ✅
- Parar o container da imagem criada, que está em andamento ✅
- Gerar uma build a partir do Dockerfile do back-end do todo-app, nomeando a imagem para "todobackend" ✅
- Gerar uma build a partir do Dockerfile do front-end do todo-app, nomeando a imagem para "todofrontend" ❌
- Gerar uma build a partir do Dockerfile dos testes do todo-app, nomeando a imagem para "todotests" ❌
- Subir uma orquestração em segundo plano com o docker-compose de forma que backend, frontend e tests consigam se comunicar ❌
<br>
<hr/>

## Tecnologias Utilizadas

### BackEnd:
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
- Dentro da pasta `%/docker/docker-commands`, haverão 9 arquivos com comandos utilizados pelo Docker <br>
- Copie a linha de comando do primeiro arquivo `command01.dc`, cole no seu terminal e execute <br>
- Repita o processo seguindo a ordem numérica dos arquivos até executar o ultimo comando </br>
