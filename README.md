# Criando o primeiro container Docker

🚀Meu primeiro container Docker
<br>

-------------------------------------------------------------------------

☕Comando utilizado para construir o container:<br>
docker build -t minha-app .
<br>

-------------------------------------------------------------------------

☕Comando para acessar o container<br>
docker exec -it 8c0037ef5a8e bin/bash<br>
docker exec -it <nome_do_container> <comando>

-------------------------------------------------------------------------

☕Comando utilizado para visualizar uma lista de comandos no CMD:<br>
docker --help
<br>

-------------------------------------------------------------------------

☕Comando para criar uma rede:<br>
docker network create --driver bridge --subnet 192.168.1.0/24 --gateway 192.168.1.1 minha-rede

-------------------------------------------------------------------------

<img src="https://github.com/ItaloBasilio/Container-docker/blob/master/app_dockerfile/img.png?raw=true" >
