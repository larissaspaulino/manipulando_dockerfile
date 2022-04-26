
# Criando uma imagem no docker

Manipulando o dockerfile e criando uma imagem no docker.

Para contruir o container, rode esses comandos no terminal:

- docker build -t hello_world_express_node .
- docker run --name express_node -p 3000:3000 -d hello_world_express_node