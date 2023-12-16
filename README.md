
COMANDOS PARA COMPILAR ESTE PROJETO

cd medicenter-layout

1- Para compilar a imagem Docker:
 
    BAIXAR IMAGEM DOCKER: docker pull gyanlima/curso-docker:0.0.1 


    BUILDAR IMAGEM docker build -t gyanlima/curso-docker:0.0.1 .

 
2- Comando para criar o conteiner Docker:
 
    
    docker container run -d \
    -p 88:80 \
    --name ctn-html \
    --restart=always \
    gyanlima/curso-docker:0.0.1


3- No Browser: 

    http://localhost:88


4- Enviando a imagem para o Docker Hub:


    docker login -u gyanlima



    docker push gyanlima/curso-docker:0.0.1