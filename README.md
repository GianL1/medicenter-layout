Passo a passo para compilar o projeto

1-docker build -t html-server-image:v1 . 


docker container run -d \
 -p 88:80 \
 --name ctn-html \
 --restart=always \
 gyanlima/curso-docker

No Browser: 
http://localhost:88