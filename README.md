# Projeto Docker

Esse projeto foi realizado para exercitar o que foi aprendido no Bloco 19 do Módulo de Back End do curso da [Trybe](https://www.betrybe.com/), no qual foi sobre `Docker`.

Neste projeto foi feito:

1. **_Conteinerização_** de aplicações;
1. Conexão entre elas;
1. Orquestração para seu funcionamento.

Temos uma aplicação full-stack neste repositório: um **aplicativo de tarefas**! Esta aplicação precisa ser conteinerizada para funcionar. Para isso, foi desenvolvido os arquivos `Dockerfile` para configuração de cada frente específica: `Front-end`, `Back-end` e, no nosso caso, para um aplicativo de `teste` que valida se as aplicações estão se comunicando (estão em `./docker/todo-app`).

Também foi desenvolvido o arquivo `docker-compose` para fazer a orquestração dos containers.

Além disso, foram feitos alguns outros comandos Docker em `./docker/docker-commands` para consolidar o aprendizado.

## Como executar

Clone o projeto e acesse a pasta do mesmo.

```bash
$ git clone git@github.com:Lucas-Almeida-SD/Trybe-Projeto_21-Docker.git
$ cd Trybe-Projeto_21-Docker/docker
```

Para iniciá-lo, siga os passos abaixo:
```bash
# Iniciar o projeto
$ docker-compose up -d
```
O app estará disponível no seu browser pelo endereço http://localhost:3000.