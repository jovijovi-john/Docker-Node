# Utilizando Node com Docker 

> docker build -t john21k/dockernode . 
Vai servir para criar a imagem

> docker run -p 3000:3000 -d john21k/dockernode
Vai servir para startar a aplicação, o -d é para rodar em background

O conceito de VOLUME é que ele vai espelhar uma pasta para dentro do container. Ou seja, sempre que houver modificação nessa pasta, acontecerá tanto no container quanto no diretório que ela está na nossa máquina