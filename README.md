# Tolerância a Falhas - Projeto Final
Implementação para o trabalho final da disciplina de Tolerância a Falhas, utilizando Docker.
Essa implementação foi feita com o intuito de utilizar um conceito visto em aula e largamente aplicado, que é o Balanceador de Carga. Assim, aliando a teoria com a prática entendemos melhor o seu funcionamento e a aplicabilidade no mundo real.

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
