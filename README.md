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

☕Comando para criar e executar um contêiner MySQL no Docker<br>
docker run -e MYSQL_ROOT_PASSWORD=minha-senha --name db -v /app:/var/lib/mysql -d mysql:latest

-------------------------------------------------------------------------

☕Comando para criae e executar um contêiner Joomla no Docker
docker run -e JOOMLA_DB_USER=root -e JOOMLA_DB_PASSWORD=minha-senha --name joomla --link db:mysql -p 8080:80 -d joomla:php8.0


<img src="https://github.com/ItaloBasilio/Container-docker/blob/master/app_dockerfile/img.png?raw=true" >
