Passo a passo para compilar o projeto

1-docker build -t html-server-image:v1 .
2-docker run -d -p 88:80 html-server-image:v1 --name ctn-html

No Browser: 
http://localhost:88