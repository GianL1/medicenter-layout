
COMANDOS PARA COMPILCAR ESTE PROJETO

No diretório do deste projeto faça:

1- Para compilar a imagem Docker:
 
    BAIXAR IMAGEM DOCKER: docker pull gyanlima/curso-docker:0.0.1 


    BUILDAR IMAGEM docker build -t gyanlima/curso-docker:0.0.1 .

 
2- Comando para criar o conteiner Docker:
 
    bash
    docker container run -d \
    -p 88:80 \
    --name ctn-html \
    --restart=always \
    gyanlima/curso-docker


3- No Browser: 
    http://localhost:88


4- Para subir a imagem no docker Hub

Enviando a imagem para o Docker Hub:
 
bash
docker login -u gyanlima
  
docker container commit -m "MENSAGEM_COMMIT" ctn-html gyanlima/curso-docker:0.0.1


docker commit -m "MENSAGEM_COMMIT" ctn-html gyanlima/curso-docker:0.0.1

docker image push gyanlima/curso-docker:0.0.1


docker push gyanlima/curso-docker:0.0.1