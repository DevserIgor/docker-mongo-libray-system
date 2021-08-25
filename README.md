# alura-docker
Projeto do curso de Docker

Getstarted
- 1 primeiro instale a imagem do mongo.
~~~docker
docker run -d --name meu-mongo --network minha-rede mongo    
~~~

- 2 Instale a imagem da aula.
~~~docker
docker pull douglasq/alura-books:cap05 
~~~


- 3 sobe o container mongo
~~~
docker run -d --name meu-mongo --network minha-rede mongo    
~~~

- 4 sobe o container da app.
~~~
docker run --network minha-rede -d -p 8080:3000 douglasq/alura-books:cap05   
~~~
 
