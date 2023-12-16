Passo a passo para compilar o projeto

1-docker build -t html-server-image:v1 .
2-docker run -d -p 80:88 html-server-image:v1