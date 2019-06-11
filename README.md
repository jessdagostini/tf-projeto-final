# Tolerância a Falhas - Projeto Final
Implementação para trabalho final da disciplina de Tolerancia a Falhas

### O que é?
Este é um balanceador de carga criado com os servidores web Nginx e Apache, rodando em Docker.

### Quais são suas configurações?
Há 3 servidores backend contendo a aplicação, e um servidor frontend executando o balanceador de carga.

### Configurações de execução
Para executar, é necessário instalar o Docker e o Docker Compose na máquina. Feito isso, primeiramente cria uma rede para o projeto:

`docker network create fault-tolerance`

Em seguida, suba os containers através do comando

`docker-compose up`

Acesse http://localhost:8080/app/index.php

E veja funcionando :smile:
