# projeto-docker

Projeto para aprender dockerfile e docker-compose, subindo uma aplição node no nginx, tendo um dockerfile para o nginx e para o node e utilizando o docker compose para starta o projeto.

docker-compose up -d 
#starta os dois dockers o nginx e a do node

docker exec -it nomedocontainernode bash
#para entrar dentro do container do docker 

node index.js
#para iniciar a aplicação quando estiver dentro do docker

localhost:8080