

Comando para compilar a imagem Docker:
 
bash
cd medicenter
docker pull gyanlima/curso-docker:0.0.1
docker build -t gyanlima/curso-docker:0.0.1 .

 
Comando para criar o conteiner Docker:
 
bash
docker container run -d \
 -p 88:80 \
 --name ctn-html \
 --restart=always \
 gyanlima/curso-docker


 No Browser: 
http://localhost:88